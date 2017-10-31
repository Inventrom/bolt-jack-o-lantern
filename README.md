Bolt Halloween Lantern
======================
1. User Tweets to @BoltJackOLaalten containing one of 5 words (scary, harmless, loving, peaceful, sleepy) with #boltiot taken 
2. Parse Tweet and if matches criteria, send out Bolt GET request to toggle LED.
3. Tweet back to succesfull tweet saying LED set, with live stream link (persist state for 50 seconds)


Python API for bolt

Simple GET request, Digital GPIO control on bolt. (MultiWrite)



Node-RED
--------
-Twitter, connect account, debug console
Checking for #boltiot

eg.
Working with #FantasticBeasts at #boltiot :D https://t.co/J0eqeFbabM


BOLT API
--------
Bolt MJ 2 : BOLT1339293

DigitalWrite HIGH, Pin 0
http://cloud.boltiot.com/remote/cdece468-2906-471c-90d6-2cb860c8a01b/digitalWrite?pin=0&state=HIGH&deviceName=BOLT1339293

If all hotwords, ignore message
