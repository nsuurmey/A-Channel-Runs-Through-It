# A-Channels-Runs-Through-It
Workflow that takes seismic horizons and generates a labeled seismic volume to be used for deep learning techniques.

The solution takes in two surfaces (i.e. top_channel, base_channel) and the extent of the original seismic volume and outputs an array in the same shape of the seismic survey with 1's between the two surfaces and 0's everywhere else.

We hope that this workflow can be used to help progress deep learning seismic solutions by making real world interpretations available for training.

Next Steps: More export formats for different deep learning formats, multiple horizons.
