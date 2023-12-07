# googleform-flask-webhook

## tutorial for Getting Webhook / sending data:
https://medium.com/@eyalgershon/sending-a-webhook-for-each-google-forms-submission-a0e73f72b397 

## for local deployment, can use NGROK 
- https://ngrok.com/
- after running flask app, run `ngrok http 5000 `if you are running on port 5000, then take the provided URL and update that in the gforms_webhook.js file 