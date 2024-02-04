# Pin Brute Force

### WPS Pin Brute Force Attack

WPS (Wi-Fi Protected Setup) is a network security standard designed to simplify the process of connecting devices to a secure Wi-Fi network without the need to enter a complex password. It achieves this by using a PIN (Personal Identification Number), which is an eight-digit number that can be entered to connect a device to the network.

### **How Brute Force Attack Works**

A brute force attack on WPS PINs involves systematically trying every possible combination until the correct one is found. Considering the WPS PIN is an eight-digit number, the number of possible combinations is 10^8 (100,000,000). However, due to the way the WPS protocol is designed, the number of attempts needed may be significantly lower.

The eight-digit PIN is split into two parts: the first seven digits and the last digit, which serves as a checksum for the previous seven. Because of this structure, the effective number of combinations to brute force is reduced to 10^7 (10,000,000). Additionally, after the first four digits are confirmed, the protocol confirms this, effectively splitting the brute force process and further reducing the complexity.

### **Risks and Mitigations**

Performing a WPS PIN brute force attack is considered a security risk, and using such methods to gain unauthorized access to networks is illegal and unethical. Network administrators need to understand this risk so they can take appropriate security measures:

* Disable WPS on the router.
* Use a strong WPA2 or WPA3 security protocol for the Wi-Fi network.
* Regularly monitor network access for any unauthorized attempts.

Please ensure you are authorized and it is legal before attempting any kind of security testing on networks that you do not own.
