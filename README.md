# FlaskWebService
Flask implementation of web server for query a ML model for personalize user behavior 

## Description:
deploy_model.py: implements a Python Flask based Web Application that reads data from google analytics 
                 claulate features from that data and uses a pre trained model (using Pickle) to detect
                 users according to special charactristics. it updates a data base according to the findings 
                 of that ml model.
                 the data is then used to analize the classification according to the user session 
                 and check if it follows google score.
                 The Ml model is Random Forest based. Train and tested to detect user behevior.
                 
                python Flask is handeling the http requset and response in the module

