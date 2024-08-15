# 102-Flower-Classification-Using-ResNet50
Fine-tuning a pre-trained ResNet-50 on the Oxford 102 Flowers dataset, using the fastai library. Written for Fellowship.ai's Computer Vision Code Challenge, Cohort 32 application.

**Computer Vision (CV) Challenge:** Use a pre-trained ResNet50 and train on the Flowers dataset.
- **Dataset:** Oxford 102 Flower Database
- **Source:**  https://www.robots.ox.ac.uk/~vgg/data/flowers/102

This set contains images of flowers belonging to 102 different categories. Training was done using the `fastai` library, and the data pre-processing primarily using `Pandas`.

## Notes
For this project, I used the images from the file `102flowers.tgz` and the images labels `imagelabels.mat`, available at the link provided. Unzip `102flowers.tgz`, and rename the resulting `jpg` file to `unsorted_images`. Ensure that this folder, `imagelabels.mat`, and the Jupyter Notebook are in the same folder before running the code cells.
