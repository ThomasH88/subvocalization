# Subvocalization
Identify when to turn on and off the lights using subvocalization.
### Project Description
The subject used the [OpenBCI Ganglion](https://shop.openbci.com/products/pre-order-ganglion-board?variant=13461804483) with 4 electrodes placed on the subject's neck and chin and then proceeded to record 1000 samples of [silent speech](https://en.wikipedia.org/wiki/Subvocalization). 500 samples of "Lights-on" and 500 of "Turn-off".

The goal is to use this data to build a model that can recognize when the subject is subvocalizing "Lights-on" and "Turn-off" in order to be able to control a device e.g. a lamp, the way you would using Alexa, Siri or Google Home but without the need to articulate the commands.
### Data
- The dataset contains 1000 measurements of sEMG using the [OpenBCI Ganglion](https://shop.openbci.com/products/pre-order-ganglion-board?variant=13461804483) and 4 channels
- 500 were recorded subvocalizing "Lights-on"
- 500 were recorded subvocalizing "Turn-off"
- Special thanks to [Taylor Yang](https://github.com/rdmcolorz) who made the dataset
### Process
- The data was converted to a csv file for easy importing
- The data was then converted to multiple spectrograms
- The spectrograms where then used to train a ConvNet
- Achieved 98% accuracy on the test set
