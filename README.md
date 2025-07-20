An interactive web app that lets you search for houses based on location and price range. It shows house pictures along with details like street address, price, number of bedrooms, bathrooms, and square footage.

This project combines machine learning predictions with a beautiful HTML interface generated directly from Jupyter Notebook.

 Project Structure
graphql
Copy
Edit
House Pricing/
├── archive (1)/
│   ├── socal2.csv                # House dataset (with price, location, etc.)
│   ├── socal2/
│   │   └── socal_pics/           # Folder with house images (0.jpg, 1.jpg, ...)
│   └── cnn_features.npy          # Cached CNN features (optional)
├── house_search.html             # Generated HTML search page
└── House_Price_Prediction.ipynb  # Jupyter Notebook with ML and HTML code
 Features
 Search houses by city/location
 Filter results by minimum & maximum price
 View house images and details (street, price, beds, baths, sqft)
 Works offline (if socal_pics folder is present)
 Fully generated from Jupyter Notebook

 Tech Stack
Python (Pandas, Matplotlib, TensorFlow, XGBoost)

Jupyter Notebook

HTML, CSS, JavaScript

Pre-trained CNN (DenseNet121 or ResNet50) for image feature extraction

 Setup Instructions
Clone or download the project

Ensure the dataset (socal2.csv) and images (socal_pics/) are in:

makefile
Copy
Edit
C:\Users\sagni\Downloads\House Pricing\archive (1)\
Open House_Price_Prediction.ipynb in Jupyter Notebook.

Run all cells to:

Train ML model

Generate house_search.html

Go to:

makefile
Copy
Edit
C:\Users\sagni\Downloads\House Pricing
and double-click house_search.html to open in your browser.

 Example
Input	Output
Location: Brawley	Shows 6 matching house images and details
Price: ₹200,000–₹400,000	
