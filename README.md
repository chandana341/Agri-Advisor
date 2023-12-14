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

Chatbot Integration
AgriAdvisor integrates an interactive chatbot using OpenAI GPT. The chatbot enhances user engagement by providing instant responses to user queries. The technical implementation involves making API calls to the OpenAI GPT API, sending user queries, and processing the model-generated responses.

## How to use 💻
- Crop Recommendation system ==> enter the corresponding Soil type and location then the algorithm will suggest the best crops that can be grown in the field. Refer [this website](https://www.gardeningknowhow.com/garden-how-to/soil-fertilizers/fertilizer-numbers-npk.htm) for more information.
Note: When you enter the city name, make sure to enter mostly common city names. Remote cities/towns may not be available in the [Weather API](https://openweathermap.org/) from where humidity, temperature data is fetched.

- Fertilizer suggestion system ==> Enter the nutrient contents of your soil and the crop you want to grow. The algorithm will tell which nutrient the soil has excess of or lacks. Accordingly, it will give suggestions for buying fertilizers.

- Disease Detection System ==> Upload an image of leaf of your plant. The algorithm will tell the crop type and whether it is diseased or healthy. If it is diseased, it will tell you the cause of the disease and suggest you how to prevent/cure the disease accordingly.

- Interactive Chatbot
To enhance user experience, AgriAdvisor features an interactive chatbot powered by OpenAI GPT. Users can ask questions, seek advice, and receive instant responses, making the platform more accessible and user-friendly.

## How to run locally 🛠️
- Before the following steps make sure you have [git](https://git-scm.com/download), [Anaconda](https://www.anaconda.com/) or [miniconda](https://docs.conda.io/en/latest/miniconda.html) installed on your system
- Clone the complete project with `git clone` or you can just download the code and unzip it.
- Once the project is cloned, open anaconda prompt in the directory where the project was cloned and paste the following block
  ```
  conda create -n agriadvisor python=3.6.12
  conda activate agriadvisor
  pip install -r requirements.txt
  ```
- And finally run the project with
  ```
  python app.py
  ```
- Open the localhost url provided after running `app.py` and now you can use the project locally in your web browser.
