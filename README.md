# COVID19 Mask Image Dataset

> Note: This dataset links to images on Instagram. We do not store or own the images on Instagram.

Image dataset from Instagram of people wearing medical masks, non-medical (DIY) masks, or no mask. Created using the [Universal Data Tool](https://github.com/UniversalDataTool/universal-data-tool) for fun :) The dataset currently has roughly ~1,205 image samples.

This dataset could be used to build a face mask detector for selfie-type photos.

![Examples from Dataset](https://user-images.githubusercontent.com/1910070/78955958-da161580-7aae-11ea-9eb0-4d8bd9070a3e.png)

## Getting the Data

[Click this to download mask_labels.udt.csv](https://github.com/UniversalDataTool/coronavirus-mask-image-dataset/raw/master/mask_labels.udt.csv). (you might have to "Save Page As" to save it)

It looks kinda like this:

| path      | . | imageUrl                       | output           |
| --------- | - | ------------------------------ | ---------------- |
| samples.0 | . | https://example.com/image1.jpg | medical_mask     |
| samples.1 | . | https://example.com/image2.jpg | no_mask          |
| samples.2 | . | https://example.com/image3.jpg | non_medical_mask |

## How to View

Download the [mask_labels.udt.csv](https://github.com/UniversalDataTool/coronavirus-mask-image-dataset/raw/master/mask_labels.udt.csv) file and open it at [universaldatatool.com](https://universaldatatool.com)

## How to Use

[Check out this notebook](https://github.com/UniversalDataTool/coronavirus-mask-image-dataset/blob/master/FastAI%20Classification%20Model.ipynb) to see how to use the dataset with [fast.ai](https://fast.ai). You could also download the [mask_labels.udt.csv](https://github.com/UniversalDataTool/coronavirus-mask-image-dataset/blob/master/mask_labels.udt.csv) file to use whatever framework you want.

We were able to achieve 93% accuracy prediction accuracy on the dataset (see confusion matrix below):

![confusion matrix](https://user-images.githubusercontent.com/1910070/78955623-c8803e00-7aad-11ea-898e-d167a7e42ed0.png)

