# Botkit-Starter-Socket

This is a nlp smart bot using botkit and express server. This app enables webhook as a channel to connect to botkit.

# Let do some talking

To start the botkit server, clone this repo and do <code>npm install</code> followed by <code>npm start</code>. 
Now you will have botkit server running at http://localhost:3005/botkit/receive, go ahead and start talking.

# Sample Request

For talking to the botkit, you would need to make POST requests to botkit server. The sample request would look something like this,   
<code>
  `{
      type : "text",  
      text : "I said hello fella",  
      user : "user-unique-secret-id"   
      channel : "webhook"  
  }`
</code>
