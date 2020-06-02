This app details creating a facebook messenger chatbot using Python and Flask. App will be deployed using Heroku.

To run the app:
1. Install the requirements: pip3 install -r requirements.txt
2. Install flask: pip3 install flask
3. Create a environment variable: FLASK_APP=app
3. Run the app locally: flask run

Heroku URL: https://morning-coast-38951.herokuapp.com/
Verify Token: 1234ae56

Heroku Deployment Steps:
1. cd into project folder and run heroku create
2. Run: heroku local
3. Then, in your browser, visit http://localhost:5000/ and you should see “Hello world”.
4. Kill the local server with Ctrl+C. To deploy this endpoint to Heroku: git push heroku master
5. Enter: heroku open in command line
6. Then we get a working webhook URL that we will use to setup our bot
7. The URL to our app is "https://morning-coast-38951.herokuapp.com/"
