About Dataset:

The EMNIST dataset is a set of handwritten character digits derived from the NIST Special Database 19 and converted to a 28x28 pixel image format and dataset structure that directly matches the MNIST dataset. Further information on the dataset contents and conversion process can be found in the paper available at https://arxiv.org/abs/1702.05373v1.

Format
There are six different splits provided in this dataset and each are provided in two formats:

Binary (see emnist_source_files.zip)
CSV (combined labels and images)
Each row is a separate image
785 columns
First column = class_label (see mappings.txt for class label definitions)
Each column after represents one pixel value (784 total for a 28 x 28 image)
ByClass and ByMerge datsets
The full complement of the NIST Special Database 19 is available in the ByClass and ByMerge splits. These two datasets have the same image information but differ in the number of images in each class. Both datasets have an uneven number of images per class and there are more digits than letters. The number of letters roughly equate to the frequency of use in the English language.

train: 697,932
test: 116,323
total: 814,255
classes: ByClass 62 (unbalanced) / ByMerge 47 (unbalanced)

Balanced dataset
The EMNIST Balanced dataset is meant to address the balance issues in the ByClass and ByMerge datasets. It is derived from the ByMerge dataset to reduce mis-classification errors due to capital and lower case letters and also has an equal number of samples per class. This dataset is meant to be the most applicable.

train: 112,800
test: 18,800
total: 131,600
classes: 47 (balanced)


Visual breakdown of EMNIST datasets
Please refer to the EMNIST paper for details on the structure of the dataset https://arxiv.org/abs/1702.05373v1.
EMNIST datasets breakdown

Acknowldgements
Cohen, G., Afshar, S., Tapson, J., & van Schaik, A. (2017). EMNIST: an extension of MNIST to handwritten letters.

Dataset retrieved from https://www.nist.gov/itl/iad/image-group/emnist-dataset

Gregory Cohen, Saeed Afshar, Jonathan Tapson, and Andre van Schaik
The MARCS Institute for Brain, Behaviour and Development
Western Sydney University
Penrith, Australia 2751
