
**Visual Search Project**
This project represents the initial step toward implementing a visual search system for images of specific products, with a focus on carpets. 
Visual search involves using an image as a query to retrieve related information, find similar images, or identify objects.

*Project Overview:*

The goal was to build a multi-label image classification model to predict attributes like type, color, style, and usage from product images. The process included:

*Data Preparation:*

Cleaning and formatting an Excel dataset by removing irrelevant columns, replacing missing values, and linking image paths to labels.
Encoding attributes: binary encoding for type, color, and style, and one-hot encoding for usage.

*Model Development:*

A custom Convolutional Neural Network (CNN) was created to handle multi-label classification (sigmoid activation) for type, color, and style, 
and multi-class classification (softmax activation) for usage.Images were resized, normalized, and fed into the CNN.
The model was trained over 10 epochs with appropriate loss functions: Binary Crossentropy and Categorical Crossentropy.

*Evaluation:*

The model's performance was assessed using accuracy, precision, recall, and F1 score.
Additional features like extract_dominant_colors and predict_single_image were implemented to extract image features and make predictions.

*Notes:*

The project serves as a foundation for further development in visual search systems. The current code can be improved and may contain errors, particularly in 
image recognition, which requires significant refinement and optimization for practical applications.






