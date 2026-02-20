Data Collection and Preparation



Data Collection

Use datasets from:

Kaggle

Smart Internz provided dataset

Classes:

Fresh fruits/vegetables

Rotten fruits/vegetables

Data Preparation

Resize images (e.g., 224×224)

Normalize pixel values

Data augmentation:

Rotation

Zoom

Flip

 Purpose: Improve model accuracy and avoid overfitting.

 Step 2: Split Data and Model Building

Data Splitting

Training data: 70–80%

Testing data: 20–30%

Model Building (Transfer Learning)

Load pre-trained model (e.g., MobileNet)

Freeze initial layers

Add:

Dense layer

Dropout

Output layer (Fresh / Rotten)

Compile the model


→ Faster training + better performance with less data.

 Step 3: Testing Model & Data Prediction

Test the model with unseen images

Check:

Accuracy

Loss

Predict output:

“Fresh”

“Rotten”

 You can visualize predictions using sample images.

 Step 4: Application Building
Frontend

Simple HTML/CSS

Image upload option

Backend

Flask (Python)

Load trained model

Accept image input

Show prediction result

 Final output:

“This fruit is Fresh ”
or
“This fruit is Rotten