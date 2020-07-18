# OpenAI API Voice Interface

### You need an OpenAI API Key to run this example!

This is a simple little voice-to-voice example app for the OpenAI API.  

Simply paste your secret key into the URL field, click through the alert (user interaction is necessary to activate voice synthesis), and enable your microphone.  

**(This has only been tested on Windows in Chrome 83 and is unlikely to work in other browsers)**

This example only depends on [sse.js](https://github.com/mpetazzoni/sse.js) to POST authorization credentials through an EventSource.

This is not meant to serve as an example for how to use the API; it was put together very quickly as a proof of concept.  More work will be needed to ensure robustness, improve compatibility with other browsers, and to improve the back and forth time in conversations.

The best thing to ask it is to "Tell me a story (complete)".

----

Core code by John Selstad: https://twitter.com/johnselstad

Design & styling by David Holz: https://twitter.com/DavidSHolz
