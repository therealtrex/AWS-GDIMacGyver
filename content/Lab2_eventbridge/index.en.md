# Setup EventBridge to send Amazon GuardDuty logs to Splunk using native EventBridge PUSH method
In this workshop you will learn how to create Splunk destination as EventBridge Target and configure EventBridge Rules to ingest events from Amazon GuardDuty into Splunk.

This lab will go through the following: 
- Create a HEC token to use for EventBridge
- Setup Splunk as a API destination in EventBridge
- Setup EventBridge Rule for Amazon GuardDuty events
- Validate data is streaming into Splunk from Amazon GuardDuty

## Architecture Diagram 
Below is the high level architecture that you will deploy for this lab:

![image001](/static/40_eventbridge/architecture-eventbridge.png)

### Click <a>[Next](/content/Lab2_eventbridge/setup_splunk.md)</a> to continue or click <a>[Back](/README.md) to go back to the beginning</a>