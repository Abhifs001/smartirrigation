# Introduction
This project is based on the Soil Moisture Prediction according the crop name so that the farmer can schedule the irrigation in advance for 3-4 days

# Current Status 
the route to '/predict_soil_moisture' will not work because MoistPredModel also takes crop name as arguement. Add crop name in the request body in frontend and make changes accordingly in the backend as same as in '/predictmoisture' 

# Directory details
1. client contains UI
2. server contains pickle files, column file and app.py file 
3. Models folder contains different Machine Learning Models 

# To start the flask server, run the following command
cd server
python app.py

# To test server with POSTMAN
send POST request to url http://[your local host ]/predictmoisture with request form having following fields
1. crop name 
2. time
3. tempreture
4. air moisture
5. pressure
6. wind speed


