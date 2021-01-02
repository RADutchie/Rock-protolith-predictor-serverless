Serverless version of the rock protolith prediction app 
==============================

ML model trained to predict if a rock is igneous or sedimentary based on major element geochemistry.

This model is provided as a web app which can be found at: http://protolith-app.ap-southeast-2.elasticbeanstalk.com/

To run locally 
------------
Please see the dockerized version of this app at https://github.com/RADutchie/Rock_protolith_predictor

Thanks to the very excellent [serverless-framework](https://www.serverless.com/), this modified version of the app is now running live on AWS using AWS lambda and AWS S3 static hosting.

For more details on the model and training please refer to the above repo

Attribution and training data
------------
This predictor is a reformulation of the original work published by Hasterok et al 2019. 
*Chemical identification of metamorphic protoliths using machine learning methods*. Computers and Geosciences. **132**, 56-68

The source data for training can be found at: https://zenodo.org/record/2586461#.XvwL8cgzZPY

--------


