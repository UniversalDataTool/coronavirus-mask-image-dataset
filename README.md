# COVID19 Mask Image Dataset

> Note: This dataset links to images on Instagram. We do not store or own the images on Instagram.

Image dataset from Instagram of people wearing medical masks, no mask, or a non-medical (DIY) mask. Created using the [Universal Data Tool](https://github.com/UniversalDataTool/universal-data-tool) for fun :)

![Examples from Dataset](https://user-images.githubusercontent.com/1910070/78955540-8a831a00-7aad-11ea-9977-d9c1b5ae141b.png)

## How to View

Download the `mask_labels.udt.csv` file and open it at [universaldatatool.com](https://universaldatatool.com)

## How to Use

[Check out this notebook](https://github.com/UniversalDataTool/coronavirus-mask-image-dataset/blob/master/FastAI%20Classification%20Model.ipynb) to see how to use the dataset with [fast.ai](https://fast.ai). You could also download the [mask_labels.udt.csv](https://github.com/UniversalDataTool/coronavirus-mask-image-dataset/blob/master/mask_labels.udt.csv) file to use whatever framework you want.

We were able to achieve 93% accuracy on the dataset (see confusion matrix below):

![confusion matrix](https://user-images.githubusercontent.com/1910070/78955623-c8803e00-7aad-11ea-898e-d167a7e42ed0.png)

