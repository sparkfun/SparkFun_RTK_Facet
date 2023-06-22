SparkFun RTK Facet
========================================

<table class="table table-hover table-striped table-bordered">
  <tr align="center">
   <td><a href="https://www.sparkfun.com/products/20000"><img src="https://cdn.sparkfun.com//assets/parts/1/9/7/4/6/20000-SparkFun_RTK_Facet_L-Band-01.jpg"></a></td>
   <td><a href="https://www.sparkfun.com/products/18590"><img src="https://cdn.sparkfun.com//assets/parts/1/8/6/3/0/RTK_Facet_Photos-01.jpg"></a></td>
  <tr align="center">
    <td><a href="https://www.sparkfun.com/products/20000">SparkFun RTK Facet L-Band (GPS-20000)</a></td>
    <td><a href="https://www.sparkfun.com/products/19029">SparkFun RTK Facet (GPS-19029)</a></td>
  </tr>
</table>

The SparkFun RTK Facet and RTK Facet L-Band are your one stop shop for high precision geolocation and surveying needs. For basic users, it’s incredibly easy to get up and running and for advanced users, the RTK Facet is a flexible and powerful tool. With just a few minutes of setup, the RTK Facet is one of the fastest ways to take centimeter grade measurements. By connecting your phone to the RTK Facet over Bluetooth, your phone can act as the radio link to provide correction data as well as receive the NMEA output from the device. This is exactly how $10,000 surveying devices have been operating for the past decade - we just made it easier, smaller, and a lot cheaper. 

The RTK Facet L-Band utilizes corrections from u-blox's PointPerfect service broadcast from a geosynchronous Inmarsat satellite. The only setup required is a WiFi SSID and password. Once entered, the device will provision itself and periodically (once a month) update the decryption keys necessary to use the PointPerfect service. The price of the RTK Facet L-Band includes a 12-month subscription. Additional years of service can be purchased.

Under the hood of the SparkFun RTK Facet is an ESP32 WROOM connected to a ZED-F9P as well as some peripheral hardware (OLED, LiPo fuel gauge, microSD, etc). Additionally, housed under the dome of the RTK Facet is a surveyor grade L1/L2 antenna. It is the same element found within our GNSS Multi-Band L1/L2 Surveying Antenna.

Under the hood of the SparkFun RTK Facet L-Band is an ESP32 WROOM connected to a ZED-F9P GNSS receiver, a NEO-D9S L-Band receiver (for corrections), and a variety of peripheral hardware (LiPo fuel gauge, microSD, etc). Additionally, housed under the dome of the RTK Facet L-Band is a surveyor grade L1/L2/L-Band antenna. This antenna is a unique combination of elements designed to receive the GNSS signals (L1/L2) alongside the 1.55GHz PointPerfect corrections. The built-in antenna has an ARP of 69mm from the base to the measuring point of the L1 antenna and an ARP of 68mm to the measuring point of the L2 antenna. The RTK Facet L-Band is programmed in Arduino and can be tailored by you to fit whatever your needs may be.

Repository Contents
-------------------

* **/Documents** - Datasheets and additional product information
* **/Hardware** - Eagle PCB files
* **/Labels** - Display overlay and info stickers
* **/Mechanical** - Drawings use to created injection molding tooling

Documentation
--------------

* **[RTK Product Manual](https://docs.sparkfun.com/SparkFun_RTK_Firmware/)** - A detailed guide describing all the various software features of the RTK product line. Essentially it is a manual for the firmware used by the RTK Facet.
* **[RTK Facet L-Band Hookup Guide](https://learn.sparkfun.com/tutorials/sparkfun-rtk-facet-l-band-hookup-guide)** - Hookup guide for the SparkFun RTK Facet L-Band.
* **[RTK Facet Hookup Guide](https://learn.sparkfun.com/tutorials/sparkfun-rtk-facet-hookup-guide)** - Hookup guide for the SparkFun RTK Facet.

License Information
-------------------

This product is _**open source**_! 

Please review the LICENSE.md file for license information. 

If you have any questions or concerns on licensing, please contact technical support on our [SparkFun forums](https://forum.sparkfun.com/viewforum.php?f=152).

Distributed as-is; no warranty is given.

- Your friends at SparkFun.
