# Create an IBM Cloud Node-RED Web Starter

- Create a [Node-RED Web Starter](https://console.bluemix.net/catalog/starters/node-red-starter)
- Name your **Orion-Onyx-<yourname>** Node-RED starter
- Create and Connect Watson AI services (Don't restage them individually, restage after connecting all of them to your Node-RED Starter)
  - Speech to Text
  - Text to Speech
  - Watson Assistant
  - Language Translator
  - Natural Language Understanding
  - Tone Analyzer
  - Twilio


### Create a IBM Cloud Toolchain
  - Enter the Git Repo
  - Edit **package.json** and add the following Node-RED Nodes:
```
"node-red-dashboard":"2.x",
"node-red-contrib-web-worldmap":"1.x",
"node-red-contrib-orion":"1.x"
```
For example
```
{
    "name"         : "node-red-bluemix",
    "version"      : "0.8.0",
    "dependencies": {
        "when": "~3.x",
        "nano": "6.2.x",
        "bcrypt": "1.0.2",
        "cfenv":"~1.0.0",
        "express":"4.x",
        "body-parser":"1.x",
        "http-shutdown":"1.2.0",
        "node-red": "0.x",
        "node-red-bluemix-nodes":"1.x",
        "node-red-node-watson":"0.x",
        "node-red-node-openwhisk":"0.x",
        "node-red-node-cf-cloudant":"0.x",
        "node-red-contrib-scx-ibmiotapp":"0.x",
        "node-red-nodes-cf-sqldb-dashdb":"0.x",
        "node-red-dashboard":"2.x",
        "node-red-contrib-web-worldmap":"1.x",
        "node-red-contrib-orion":"git+"
        },
    "scripts": {
        "start": "node --max-old-space-size=180 index.js --settings ./bluemix-settings.js -v"
    },
    "engines": {
        "node": "8.x"
    }
}
```
Now finally restage your application by committing the above changes.
---

[Home](/README.md) | [Node-RED](/PART1.md) | **Setup** | [Onyx](/PART3.md) | [Connect](/PART4.md) | [Speech](/PART5.md) | [Sentiment](/PART6.md) | [Tone](/PART7.md) | [NLU](/PART8.md) | [Translate](/PART9.md) | [SMS](/PART10.md) | [ChatBot](/PART11.md) | [Cloudant](/PART12.md) | [Map](/PART13.md) | [Blockchain](/PART14.md) 


---
