The Raspberry Pi Camera Module can be used to take high-definition video as well as photographs. To use the Camera Module, you will first need to connect it to your Raspberry Pi:

- Disconnect your Raspberry Pi from its power source before starting

- The flex cable of the camera inserts into the connector between the Ethernet and HDMI ports, with the silver connectors facing the HDMI port

- Open the flex cable connector by pulling the tabs on the top of the connector upwards and then towards the Ethernet port

- Firmly insert the flex cable into the connector while taking care not to bend the flex at too sharp an angle

- Push the top part of the connector towards the HDMI connector and down while holding the flex cable in place

![camera-connect](images/camera-connect.gif)

Reboot your Raspberry Pi and then make sure that the camera is enabled:

- Click on the Menu, then on **Preferences** and choose **Raspberry Pi Configuration**. Then ensure that the *radio button* for **Camera** in the **Interfaces** tab has been checked.

Finally, you'll want to test that your camera is working. The easiest way to do this is to open a Terminal window and type the following:

```bash
raspistill -k
```

You should see a preview image displayed on the screen. You can exit the `raspistill` program by typing `x` and then pressing `Enter`.
