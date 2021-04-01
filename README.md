# Brain-Tumor-Detection-And-Classification-Using-Standard-CNN-Architectures
This work is mainly focused on the brain tumor detection and classifying various brain tumors such as Meningioma tumor, Glioma tumor, Pituitary Tumor. The framework was utilized for detection and classification of varioos brain tumors are standard CNN architectures.

#### Dataset
[Brain Tumor Data](https://figshare.com/articles/dataset/brain_tumor_dataset/1512427)

Cheng, Jun (2017): brain tumor dataset. figshare. Dataset. https://doi.org/10.6084/m9.figshare.1512427.v5 

#### Dataset Details
The data collection for this brain tumour include 3064 images of contrast-intensed T1 in 233 patients with three forms of brain tumours: 708 slices of meningioma, 1426 slots of glioma, and 930 slices of hypophysical tumours. Thanks to the archive file size max, the entire dataset is divided into 4 subset files in 4 .zip files with a total of 766 slices for each.zip file. There are also 5  cross-validation indexes.

This data is arranged in the form of matlab data (.mat file). The following image fields are stored on each file in a struct:

cjdata.label: 1 meningioma, 2 glioma, 3 hypophytes.
Patient ID: cjdata.PID:
gif: image data cjdata.image:
Cjdata.tumorBorder: vector that stores discrete coordonnades on the border of tumours.

The tumour boundary was produced manually. It was produced. This is why it can use it to create a binary tumour mask image.
cjdata.tumorMask: a tumour region indicator binary 1s picture;

#### Libraries Used:
1. os
2. numpy
3. h5py
4. cv2
5. tensorflow
6. sklearn
7. matplolib

#### Standrd CNN architectures utilized:
1. VGG-16
2. Inception-V3
3. ResNet50

#### Metrics utilized for evaluating performance of the framework:
1. Accuracy
2. Precision
3. Recall
4. F1-score

