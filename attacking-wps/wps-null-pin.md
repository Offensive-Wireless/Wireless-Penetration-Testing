# WPS Null Pin

### WPS Null Pin Attack

WPS, or Wi-Fi Protected Setup, is a network security standard designed to simplify the process of connecting devices to a wireless network. However, it's vulnerable to several types of attacks, one of which is the WPS Null Pin attack.

### **How WPS Null Pin Attack Works**

The WPS Null Pin attack takes advantage of a flaw in the implementation of the WPS protocol where an empty or null PIN—essentially a PIN consisting of all zeroes—can be accepted by a router or access point as a valid means of authentication.

Example of a command used in a WPS Null Pin attack with a tool like Reaver:

```
reaver -i wlan0mon -b 00:90:4C:C1:AC:21 -p "\x00\x00\x00\x00\x00\x00\x00\x00"
```

### **Preventing WPS Null Pin Attacks**

To secure a network against WPS Null Pin attacks, it's advisable to:

* Disable WPS on your router.
* Regularly update router firmware to ensure any security patches for WPS are applied.
* Monitor network authentication attempts to detect unusual patterns that may indicate an attack in progress.
