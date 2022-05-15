# Sending and receiving data from the cloud using ESP32.

In this task we are going to measure temperature and hall voltage using ESP32, and observe its plot versus time on our thingspeak account.

**Hall effect sensor :**- It is a built-in sensor in ESP32. It  detects the presence and measures the magnitude of magnetic effect using Hall effect. Hall effect principle is, “output voltage is directly proportional to strength of the field.” Principle of working of this sensor: current is applied to a thin strip of metal. In the presence of magnetic field, perpendicular to the direction of current, charge carriers are deflected by Lorentz force, producing a difference in voltage between 2 sides of strips.”

**Connections : **- connect ESP32 to computer. Create an account on https://thingspeak.com/, create a new channel.
Go to API keys, copy the write API key, and store it.


## Procedure

* Create an account on Thinkspeak website.
* Then create a new channel.
* Enter field 1 as hall value, field 2 value as temperature value.
* Save the channel.
* Go to Api key menu then copy api key.
* Open arduino ide and write the code.
  code:
* Replace your api key in the code.
* Compile and upload the code.
* Now you can observe the data being displayed on the thinkspeak website.

## Working


## References

https://iotdesignpro.com/projects/how-to-send-data-to-thingspeak-cloud-using-esp32
