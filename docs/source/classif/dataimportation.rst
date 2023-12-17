Data Importation
++++++++++++++++++



Data importation is a crucial initial step in the image classification process, where users bring their datasets into the application for further analysis and model training. This phase provides two primary methods for importing data:


1. **Importing Images Directly:**
------------------------

  Users can seamlessly upload images directly into the application. This method is straightforward and user-     friendly. To successfully import images, users should follow these steps:

      - Navigate to the application's interface.
      - Look for the "Create new Dataset" option.
      - Enter the name of the classes to classify.
      - Select the desired images from local storage.
      - Confirm the importation process.

  The application will then proceed to preprocess the uploaded images for subsequent analysis.


2. **Importing from an Excel Files:**
------------------------

  Alternatively, users have the option to import data from an Excel file containing image URLs. This     
  method is   convenient for users who maintain image information in a structured Excel format. To use 
  this feature:

      - Prepare an Excel file with a column containing image URLs.
      - Navigate to the application's interface.
      - Select the "Import from Excel" option.
      - Upload a prepared zip file that contains the folder of data.
      - The application will extract image URLs from the file and proceed with data processing.
      
  Ensure your data adheres to the specified format and follows the guidelines provided in the application    for a smooth importation process.


Data Exploration
------------------------


Once the data has been successfully imported, users are presented with an exploration page that offers valuable insights into the dataset. This exploration page is designed to provide users with key statistics and visualizations that aid in understanding the characteristics of the imported data. The following components are included in the data exploration page:

-Overview Statistics:

    -Total number of images.
    -Total number of unique URLs.
    -Total number of unique classes.
    -Distribution of images across different classes.

-Class images Charts:

    -Bar Charts: Illustrating image count per class.
    -Information about image dimensions.
 
Understanding the distribution of URLs adds an extra layer of insight into how images are sourced and categorized.

      **Note:**  Refer to the `chart js documentation <https://www.chartjs.org/docs/latest/>`_  for more details on customizing and extending the chart functionalities.

The exploration page provides a comprehensive overview, enabling users to assess dataset composition, identify class imbalances, and make informed decisions for preprocessing and model selection in their image classification project.
