# sentiment-analysis_Django_webapp
 
Run the folowing command in the shell to start new project:
       
       Django-admin startproject 'project name'

After creating the project , create application in the project folder, run following command:
      
      python manage.py startapp 'app name'

Create new urls.py file in app directory and include it in the main urls.py file in project directory.

Getsentiment method in views.py file in 'sentimentanalysis application directory' takes __Text__(Tweet) as the request and apply trained LSTM model(sentiment.h5) on it and gives the response back as positive or negative sentiment.

https://github.com/GurudasKarale/sentiment-analysis_Django_webapp/blob/master/img/sentiment.PNG
