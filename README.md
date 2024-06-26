# Azure Computer Vision API with JS Client SDK

Simple usage of Computer Vision API with Express JS and swagger documentation.
This Demo will analyze a .jpg or .png URL and give you a caption, confidence level, and tags of the image.

Endpoint for Swagger Docs: /docs 

API Endpoints being used for this project (UI: /, generates caption: /caption, generates confidence score: /confidence, generates tags: /tag)


### Usage

1) Create a Computer Vision Resource on Azure, get the subscription key and end point.

2) Go to project directory and run the following command to install dependencies.

```
npm install
```

3) Create a folder called .env in the root folder Copy and paste the two lines of code below into the .env file and add your subscription key and enpoint as indicated.
APIKEY="<yourapikey>"
AZUREENDPOINT="<yourendpoint>"
    
4) run the application on localhost:3000

```
npm start
```

### Resources
[Computer Vision JS Client SDK](https://docs.microsoft.com/en-us/azure/cognitive-services/computer-vision/quickstarts-sdk/client-library?tabs=visual-studio&pivots=programming-language-javascript)
