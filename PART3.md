# Install the Orion mobile app and Pair the Onyx


# Requirements

- To use the **node-red-contrib-orion** nodes you must have an Orion account.
- Install the free Orion app on your [iOS](https://itunes.apple.com/us/app/orion-push-to-talk/id984202314) or [Android](https://play.google.com/store/apps/details?id=com.onbeep.obiwan) smart phone.
- You can sign up from within the Orion App on your [iOS](https://itunes.apple.com/us/app/orion-push-to-talk/id984202314) or [Android](https://play.google.com/store/apps/details?id=com.onbeep.obiwan) smart phone.
- Once you have an account, you will need to use the [Orion Management Console](https://login.orionlabs.io) to get the various keys you will need to configure nodes.

# Connect an Onyx

- Use the smart phone application to pair an Onyx.
- [Instructions - How to Setup an Onyx](https://support.orionlabs.io/article/94-how-do-i-setup-onyx)

![Orion Onyx](https://www.orionlabs.io/wp-content/uploads/2018/08/Black-Onyx_diagram.jpg)

# Join the Watson Workshop group

Share your account username / email with the workshop leader and they will add you to the Orion group.  The workshop leader will tell you the Group ID

# Configure Onyx Nodes

- Open your IBM Cloud Node-RED Starter application in a web browser
- Find the **Orion RX** in your left palette.
![Orion RX](https://raw.githubusercontent.com/orion-labs/node-red-contrib-orion/master/docs/orion_rx.png)
- For **Orion RX**, **Orion TX**, and **Orion Lookup** nodes, you'll need to
create at least one **Orion Config** configuration. When you first add one of
these Nodes to a Flow, you'll see that the config is blank:

![Unconfigured Node](https://github.com/orion-labs/node-red-contrib-orion/raw/master/docs/unconfigured_node.png)

Click the Edit/Pencil next to *Add new orion_config...* and enter your Orion
Login and Group information, then click *Save*:

![New Configuration](https://github.com/orion-labs/node-red-contrib-orion/raw/master/docs/new_config.png)


---

[Home](/README.md) | [Node-RED](/PART3.md) | [Setup](/PART2.md) | **Onyx** | [Connect](/PART4.md) | [Speech](/PART5.md) | [Sentiment](/PART6.md) | [Tone](/PART7.md) | [NLU](/PART8.md) | [Translate](/PART9.md) | [SMS](/PART10.md) | [ChatBot](/PART11.md) | [Cloudant](/PART12.md) | [Map](/PART13.md) | [Blockchain](/PART14.md) 

---
