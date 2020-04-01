# Phonebot with IBM Voice Agent and Backend Integration

Phonebots ca help businesses to provide information and answer simple questions. This tutorial can be used to build a first prototype, develop the phone dialog, and test the components.

## Solution Overview
The solution consist of the following components
- the Voice Agent (Watson Assistant service, Speech-to-Text service, Text-to-Speech service)
- the Twilio platform (other platforms possible)
- a basic backend application
- a database (not yet implemented)

![Phonebot Architecture](Slide1.jpeg)

## Prerequisites
- IBM Cloud account
- Twilio account
- basic knowledge of the components being used

## Instructions
(to be completed)
- get a Twilio phone number
- install Node-RED on the IBM Cloud and import the [flow](Node-RED-Flow.json)
- create a Watson Assistant service and import the Watson Assistant skill file [skill-Phonebot.json](skill-Phonebot.json)
- modify the webhook address , which is the address of the Node-RED instance
- install the IBM Voice Agent service as described in this [video](https://www.youtube.com/watch?v=ztOme26gVuA&t=308s) and on this [guide](https://cloud.ibm.com/docs/services/voice-agent?topic=voice-agent-getting-started)

I chose the option to create all in one step and could select the existing Watson Assistant service and skill.


