# Subvocalization
Identify when to turn on and off the lights using subvocalization.
### Data
- The dataset contains 1000 measurements of sEMG using the [OpenBCI Ganglion](https://shop.openbci.com/products/pre-order-ganglion-board?variant=13461804483)
- 500 were recorded subvocalizing "Lights-on"
- 500 were recorded subvocalizing "Turn-off"
- Special thanks to [Taylor Yang](https://github.com/rdmcolorz) who made the dataset
### Process
- The data was converted to a csv file for easy importing
- The data was then converted to multiple spectrograms
- The spectrograms where then used to train a ConvNet
- Achieved 98% accuracy on the test set
