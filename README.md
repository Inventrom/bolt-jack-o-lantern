Bolt Halloween Jack-O'-Lantern
==============================
Node-RED flow for Bolt IoT Halloween project as explained on:
https://blog.boltiot.com/building-an-interactive-jack-o-lantern-with-bolt-iot-da4f03080bec

The flow covers:

1. User Tweets to @BoltJackOLaalten containing one of 5 words (scary, harmless, loving, peaceful, sleepy) with #boltiot taken 
2. Parse Tweet and if matches criteria, send out Bolt GET request to toggle LED.
3. Tweet back to succesfull tweet saying LED set, with live stream link (persist state for 50 seconds)


The API reference for Bolt:
https://cloud.boltiot.com/apiDoc

Happy Halloween!
