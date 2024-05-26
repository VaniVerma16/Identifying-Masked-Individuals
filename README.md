# Masked-Robber-or-Not
This notebook allows you to classify images and determine if they depict a masked robber man.

## How it works:

### Setting Up:
* Installation: The notebook installs required libraries like fastai and fastbook.
* Image Search: It searches the web for images of "masked robber man" and "man" using DuckDuckGo.
* Download Images: It downloads a sample of the retrieved images to your Google Drive.
  
### Data Preparation:
* Creates folders in your Drive for masked robber man and man images.
* Resizes downloaded images for better processing.
* Removes corrupted images.
### Model Training: 
* It splits the data into training and validation sets and trains a deep learning model (ResNet18) to distinguish between masked robber man and man images.
### Prediction: 
* You can provide an image path, and the model will predict if it shows a masked robber man and provide a confidence score.
  
## Using the Notebook:

* Run the notebook in Google Colab.
* Mount your Google Drive: This allows the notebook to access your Drive for storing downloaded images.
* Replace the image path: In cell [24], update the fpath variable with the path to your image.
* Run cell [24]: This will predict the image and display the classification result and confidence score.
  
## Note:
- This is a basic example. Training on a larger dataset can improve accuracy.
- Ensure you have permission to download images from the web before running the script.
