SpaceNet Buildings Exploration

This is a fork of avanettan's original repository with some updates.

Transform SpaceNet geojson buidling labels data into raster masks.
Download data via:

    aws s3api get-object --bucket spacenet-dataset \
    --key AOI_1_Rio/processedData/processedBuildingLabels.tar.gz \
    --request-payer requester processedBuildingLabels.tar.gz

Download spacenet utilities from:
   https://github.com/SpaceNetChallenge/utilities/tree/spacenetV3 

For further details, see:
    https://medium.com/the-downlinq/getting-started-with-spacenet-data-827fd2ec9f53

Example outputs are included in the example_outputs directory

![Alt text](/example_outputs/all_demo/013022223130_Public_img54.png?raw=true "Figure 1")
