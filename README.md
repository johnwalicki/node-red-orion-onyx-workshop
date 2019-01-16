# Node-RED Orion Onyx Workshop

Node-RED and Watson AI examples using the Orion Labs Onyx smart wearable

This repository contains Node-RED flow examples that demonstrate how to connect the Orion Onyx smart wearable to the IBM Cloud and integrate with Watson AI services.

## Introduction

The [Orion Labs Onyx](https://www.orionlabs.io/orion-onyx/) smart walkie-talkie lets users communicate hands-free over the Internet.  The voice messages are securely stored in the cloud and, using [Node-RED](http://nodered.org) and the [node-red-contrib-orion](https://flows.nodered.org/node/node-red-contrib-orion) nodes, can be decoded.  Once decoded, the message wav file can be transcribed using [Watson Speech to Text](https://console.bluemix.net/catalog/services/speech-to-text). The text can then be integrated with other Watson AI services in interesting and productive ways.  This repository will demonstrate how to combine these technologies.  The combination of the Onyx and Watson AI are perfect for first responders, call centers and AI enabled team collaboration.

## How this git repository is organized

To help you get familiar with Node-RED and how to integrate with the Orion Onyx this git repository is split into a number of sections.

## Sections

1. [Learn about Node-RED](/PART1.md)
2. [Create an IBM Cloud Node-RED Web Starter](/PART2.md)
3. [Install the Orion mobile app and and Pair the Onyx](/PART3.md)
4. [Node-RED Example: Orion - Receive Data](/PART4.md)
5. [Node-RED Example: Orion - Watson Speech to Text](/PART5.md)
6. [Node-RED Example: Orion - Sentiment Analysis](/PART6.md)
7. [Node-RED Example: Orion - Watson Tone Analysis](/PART7.md)
8. [Node-RED Example: Orion - Watson Natural Language Understanding](/PART8.md)
9. [Node-RED Example: Orion - Watson Language Translation](/PART9.md)
10. [Node-RED Example: Orion - Twilio SMS](/PART10.md)
11. [Node-RED Example: Orion - Watson Assistant ChatBot](/PART11.md)
12. [Node-RED Example: Orion - IBM Cloudant Cloud Object Storage](/PART12.md)
13. [Node-RED Example: Orion - User Map](/PART13.md)
14. [Node-RED Example: Orion - IBM Blockchain](/PART14.md)

### Authors

- [John Walicki](https://github.com/johnwalicki/)
- [Greg Albrecht](https://github.com/orion-labs)
___

Enjoy!  Give us [feedback](https://github.com/johnwalicki/node-red-orion-onyx-workshop/issues) if you have suggestions on how to improve this tutorial.

## License

This tutorial is licensed under the Apache Software License, Version 2.  Separate third party code objects invoked within this code pattern are licensed by their respective providers pursuant to their own separate licenses. Contributions are subject to the [Developer Certificate of Origin, Version 1.1 (DCO)](https://developercertificate.org/) and the [Apache Software License, Version 2](http://www.apache.org/licenses/LICENSE-2.0.txt).

[Apache Software License (ASL) FAQ](http://www.apache.org/foundation/license-faq.html#WhatDoesItMEAN)
