# Virtual Green Screen Example App
This app uses semantic segmentation to segment out a person from background noise in a video stream and replace the background with an image or blur it out. This app builds off of a methodology for segmenting out areas of interested, which can be found at the following link: https://learn.alwaysai.co/how-to-detect-pedestrians-and-bicyclists-in-a-cityscape-video. This app also demonstrates how to separate your app configuration information into a separate JSON file. For more details on this aspect of the app, please see the original blog: https://medium.com/@jalakoo_83320/using-a-computer-vision-classifier-to-sort-images-333d5090c0b4

## Requirements
To run this app, you will need an alwaysAI account. Please register at https://alwaysai.co/auth?register=true

## Setup
Easy start up guides can be found following registration. Please see the docs page for more information: https://alwaysai.co/docs/getting_started/introduction.html

### Models
The semantic segmentation model used is the 'alwaysai/fcn_alexnet_pascal_voc' model, and more details can be found at https://alwaysai.co/model-catalog?model=alwaysai/fcn_alexnet_pascal_voc


You can alter the code to used different detection and classification models: https://alwaysai.co/docs/application_development/changing_the_model.html


## Troubleshooting
If you are having trouble connecting to your edge device, use the CLI configure command to reset the device. Please see the following page for more details: https://alwaysai.co/docs/reference/cli_commands.html

You can also post questions and comments on our Discord Community at: https://discord.gg/R2uM36U