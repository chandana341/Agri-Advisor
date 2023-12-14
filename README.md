# AGRIADVISOR 🌿
#### An ML and DL based website which recommends the best crop to grow, fertilizers to use and the diseases caught by your crops.

## MOTIVATION 💪
- Farming is one of the major sectors that influences a country’s economic growth. 

- In country like India, majority of the population is dependent on agriculture for their livelihood. Many new technologies, such as Machine Learning and Deep Learning, are being implemented into agriculture so that it is easier for farmers to grow and maximize their yield. 

- In this project, we present a website in which the following applications are implemented; Crop recommendation, Fertilizer recommendation and Plant disease prediction, respectively. 

    - In the crop recommendation application, the user can provide the soil data from their side and the application will predict which crop should the user grow. 
    
    - For the fertilizer recommendation application, the user can input the soil data and the type of crop they are growing, and the application will predict what the soil lacks or has excess of and will recommend improvements. 
    
    - For the last application, that is the plant disease prediction application, the user can input an image of a diseased plant leaf, and the application will predict what disease it is and will also give a little background about the disease and suggestions to cure it.

## DATA SOURCE 📊
- [United States Department of Agriculture](https://www.nass.usda.gov/Data_and_Statistics/index.php)
- [Disease detection dataset](https://www.kaggle.com/vipoooool/new-plant-diseases-dataset)

# Built with 🛠️
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/python/python.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/html/html.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/css/css.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/javascript/javascript.png"></code>
<code><img height="30" src="https://github.com/tomchen/stack-icons/raw/master/logos/bootstrap.svg"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/git/git.png"></code>
<code><img height="30" src="https://symbols.getvecta.com/stencil_80/56_flask.3a79b5a056.jpg"></code>
<code><img height="30" src="https://cdn.iconscout.com/icon/free/png-256/heroku-225989.png"></code>

<code><img height="30" src="https://raw.githubusercontent.com/numpy/numpy/7e7f4adab814b223f7f917369a72757cd28b10cb/branding/icons/numpylogo.svg"></code>
<code><img height="30" src="https://raw.githubusercontent.com/pandas-dev/pandas/761bceb77d44aa63b71dda43ca46e8fd4b9d7422/web/pandas/static/img/pandas.svg"></code>
<code><img height="30" src="https://matplotlib.org/_static/logo2.svg"></code>
<code><img height="30" src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/05/Scikit_learn_logo_small.svg/1280px-Scikit_learn_logo_small.svg.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/pytorch/pytorch/39fa0b5d0a3b966a50dcd90b26e6c36942705d6d/docs/source/_static/img/pytorch-logo-dark.svg"></code>

## Architecture
AgriAdvisor is built as a web application with a modular architecture, allowing for easy integration of various components. The core components include the web application, machine learning models for crop recommendations and disease predictions, and an interactive chatbot powered by OpenAI GPT.

## Technologies Used
Web Development
The frontend of AgriAdvisor is developed using HTML, CSS, and JavaScript. The application leverages a responsive and intuitive user interface to enhance user experience. It incorporates modern web development practices, including client-side rendering for dynamic content updates.

Machine Learning Models
Crop Recommendations
AgriAdvisor utilizes machine learning models for personalized crop recommendations. The following models are employed:

Support Vector Machine (SVM): SVM is used for classifying crops based on features such as soil type, climate, and geographical location. It excels in handling complex decision boundaries.

XGBoost: XGBoost is employed to enhance the precision of crop recommendations. This gradient boosting algorithm is effective in optimizing decision trees and improving predictive accuracy.

Disease Predictions
Disease prediction is accomplished using a convolutional neural network (CNN) based on the ResNet architecture. This model is trained on a diverse dataset of crop disease images, enabling accurate identification of diseases from input images.

## Chatbot Integration 🤖
Motivation
The integration of an interactive chatbot within AgriAdvisor aims to enhance user engagement and provide a seamless experience for users seeking information or assistance related to agriculture. The chatbot is powered by OpenAI GPT, allowing it to generate contextually relevant responses to user queries.

Technical Implementation
To achieve chatbot functionality, the following steps were undertaken:

OpenAI GPT Integration: The OpenAI GPT API was utilized to enable natural language processing and generation of responses. API calls were made to the OpenAI GPT endpoint, sending user queries and processing model-generated responses.

User Interaction: The chatbot was designed to be interactive, allowing users to ask questions, seek advice, and receive instant responses. The chatbot's responses are tailored to provide valuable information on crop recommendations, fertilizer suggestions, and disease predictions.

Error Handling: Robust error handling mechanisms were implemented to ensure smooth user interactions. The chatbot is capable of handling a variety of queries and providing informative responses even in cases where the user input is ambiguous or unclear.

Usage
Users can engage with the chatbot by navigating to the designated chat interface on the AgriAdvisor website. The chatbot is responsive and capable of understanding a wide range of queries related to agriculture. Users can seek advice on crop selection, inquire about fertilizer recommendations, and obtain information about plant diseases.

## Disease Prediction Page 🌱🔍
Motivation
The Disease Prediction functionality in AgriAdvisor plays a crucial role in helping farmers identify and address potential issues affecting their crops. By leveraging deep learning techniques, the system can analyze images of plant leaves to determine whether the crop is healthy or diseased. This empowers farmers with timely information to take preventive measures and mitigate the impact of diseases.

Technical Implementation
The Disease Prediction Page involves the following key components:

Convolutional Neural Network (CNN): A CNN based on the ResNet architecture was employed for disease prediction. The model was trained on a diverse dataset of crop disease images, allowing it to recognize patterns associated with various diseases.

Image Upload and Processing: Users can upload images of plant leaves through the AgriAdvisor interface. The system processes these images, extracts relevant features, and passes them through the trained CNN for disease prediction.

User Feedback: The system provides users with feedback on the health status of their crops, indicating whether the plant is healthy or showing signs of disease. In case of disease detection, the system offers insights into the specific disease and provides recommendations for prevention or cure.

Usage
Farmers and users interested in monitoring the health of their crops can utilize the Disease Prediction Page by uploading images of plant leaves. The system will promptly analyze the images and deliver information on the health status of the crops, along with actionable recommendations for addressing any identified diseases.
