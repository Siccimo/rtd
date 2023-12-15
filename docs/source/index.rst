.. Image Classification Application Documentation

Introduction
=============

The Image Classification application is an integral part of the GIIADS platform, designed to streamline image classification tasks by providing users with a versatile and user-friendly environment. As a key component within the GIIADS platform, our Image Classification application simplifies the complexities associated with image classification tasks, offering users a simple no code solution.

Key Components
---------------

The Image Classification application on the GIIADS platform is structured into three main components: Data Importation, Model, and Prediction.

1. **Data Importation:**
   Users can seamlessly import their data in the initial phase. This process offers two options: direct image uploads or utilizing an Excel file with image URLs.

2. **Model:**
   The Model component empowers users to tailor their experience by providing multiple options:
   - Construct a custom model from scratch.
   - Upload a pre-existing model.
   - Leverage one of the four available pretrained models.

3. **Prediction:**
   The Prediction component, although covered separately, is the final step in applying trained models to new data for predictions.

Project Structure
------------------

This concise project structure ensures a user-friendly and versatile environment for a diverse range of image classification tasks. The flexibility offered in data importation, model creation, and prediction makes the Image Classification application on the GIIADS platform an empowering tool for users with varied preferences.

Feel free to explore the detailed documentation for each component to maximize the benefits of the Image Classification application within the GIIADS platform.


.. Image Classification


Image Classification
=====================

This section covers the key aspects of the Image Classification process, divided into four main components: Data Importation, Model Selection, Model Training, and Prediction.

Data Importation
-----------------

### Importing Data

Before delving into model selection, the user needs to import data for classification. Two convenient methods are offered:

a. **Importing Images Directly:**
   Users can upload images directly into the application.

b. **Importing from an Excel File:**
   Alternatively, users can import data from an Excel file containing image URLs.

Ensure your data is correctly formatted and follows the guidelines provided in the application.

### Data Exploration

After importing the data, an exploration page is displayed, providing statistics on the imported data, including the number of images and URLs. Additionally, charts are available to explore each class.

Model Selection
-----------------

Once data is imported, it's time to choose a model for classification. The application provides three distinct options:

a. **Build Your Own Model:**
   - Construct a custom model from scratch.
   - Select layers and configure the architecture based on preferences.

b. **Upload Your Model:**
   - If you already have a trained model, choose this option.
   - Upload an h5 file or a zipped file containing the h5 model file.

c. **Choose Pretrained Model:**
   - Explore four pre-trained models.
   - Select a model that suits your image classification task.

Model Training
----------------

After selecting the model, the next crucial step is training it on your data to enhance its predictive capabilities.

### Choose Layers for Training

Customize the training process by choosing specific layers for training. You can opt to train the entire model or focus on specific layers for fine-tuning.

### Set Hyperparameters

Fine-tune the training process by configuring hyperparameters:
- **Learning Rate:** Determines the step size during the optimization process.
- **Batch Size:** Specifies the number of data points used in each iteration.
- **Number of Epochs:** Defines the number of times the model iterates over the entire dataset.

### Monitoring the Training

During training, the application provides real-time feedback on progress, including loss metrics, accuracy, and other relevant indicators. This allows you to gauge the performance of your model and make adjustments if necessary.

Prediction
----------------

Coming soon
-----------

