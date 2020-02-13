# Summary

When motion is detected on a Nest cam an email alert is sent out to the Nest user email.

Using the gmail API we can read this message.

When we get this message we need to then call the Leviton API to turn on lights.

We could potentially do other things.

Why are we doing this? Well unfortunately IFTTT is not working w/ Nest since they merged with Google.

## Gmail API

Using the REST based option isn't viable as it requires the gmail user to accept the access each time the code runs
What we can use the is push notifications feature it seems which is much better and more real time alerting
- https://cloud.google.com/pubsub/docs/quickstart-console 