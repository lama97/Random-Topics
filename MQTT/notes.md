# MQTT 
- based on publish/subscribe system
- publish the **topic** , subscribe to the **topic**
- one topic can work for many devices 

## Setting MQTT on Linux (ubuntu)
### Some Remarks
- used public broker : 'test.mosquito.org'
- script used to subscribe to topics (mqtt_client_demo.py)
- another script to publish the topics to the broker (mqtt_publish_demo.py)

### Implementation Set-up
1. sudo apt install python3-pip (to install python package)
2. run mqtt_client_demo.py
3. run mqtt_publish_demo.py

### Conclusion 
- publishing a message to a certain topic is like activating
the command to turn on/execute something 
- gets taken care of by the public broker (mosquito.org in this case)
- when subscribed to a certain topic : I receive messages published
to the same topic

### Useful Links
https://core-electronics.com.au/tutorials/getting-started-with-home-automation-using-mqtt.html
