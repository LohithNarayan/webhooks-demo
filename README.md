# Webhook Notifications

Download and edit a .env file

Download our env-template and save it as a file named .env.

Edit your newly downloaded .env file, setting its variables with the proper values for the app you created above.
RC_CLIENT_ID - set to the Client ID of the app you created above
RC_CLIENT_SECRET - set to the Client Secret of the app you created above
RC_JWT - set to the JWT credential you created for yourself
WEBHOOK_DELIVERY_ADDRESS - the full address where notifications will be sent to. If you run the code on your local machine, you can use ngrok service to obtain a tunnel address to your localhost. E.g. https://1058-69-181-202-2.ngrok-free.app

# Install RingCentral Python SDK
$ pip install ringcentral python-dotenv

# Run your code

 Open 2 terminal windows and run your script in each terminal in the order below: Note: Running the demo code requires Python 3.x

$ python3 webhook-server.py
$ python3 webhook-notification.py