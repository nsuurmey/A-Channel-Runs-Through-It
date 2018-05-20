# A-Channel-Runs-Through-It

Summary: This workflow takes two horizons and generates a labeled seismic volume to be used for deep learning techniques.

It was created by Graham Brew, Nam Pham, and Nathan Suurmeyer at the 2018 Subsurface Hackathon in Salt Lake City hosted by Agile Scientific.

The workflow needs two surfaces (i.e. top_channel, base_channel) and the extent of the original seismic volume.  It outputs an array in the same dimensions as of the interpreted seismic survey with 1's between the two surfaces and 0's everywhere else.

We hope that this workflow can be used to help progress deep learning seismic solutions by converting real interpretations into training datasets.

Next Steps: More export formats for different deep learning techniques, multiple horizons, multiple geobodies.

Thank you to Evan Bianco, Diego Castañeda, and the Open Seismic Repository.
https://www.opendtect.org/osr/

![alt text](https://github.com/nsuurmey/A-Channel-Runs-Through-It/blob/images-results/Seismic_with_geobody_array.PNG)
