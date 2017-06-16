The Raspberry Pi camera module can be used to take high-definition video, as well as still photographs. To use the camera module, you will first need to connect it to your Raspberry Pi.

- Disconnect your Raspberry Pi from its power source before starting.

- The flex cable of the camera inserts into the connector between the Ethernet and HDMI ports, with the silver connectors facing the HDMI port.

- The flex cable connector should be opened by pulling the tabs on the top of the connector upwards then towards the Ethernet port.

- The flex cable should be inserted firmly into the connector, with care taken not to bend the flex at too acute an angle.

- The top part of the connector should then be pushed towards the HDMI connector and down, while the flex cable is held in place.

![camera-connect](images/camera-connect.gif)

- Reboot your Raspberry Pi and then make sure that the Camera is enabled. To do this, click on the Menu, then **Preferences** and choose **Raspberry Pi Configuration**. Then ensure that the *radio button* for **Camera** in the **Interfaces** tab has been checked.

- Lastly, you'll want to test that your camera is working. The easiest way to do this is to open a Terminal window and type the following:

```bash
raspistill -k
```

- You should see a preview image displayed on the screen. You can exit the `raspistill` program by typing `x` and then pressing `Enter`
