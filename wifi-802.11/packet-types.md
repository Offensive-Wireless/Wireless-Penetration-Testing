# Packet Types

### 802.11 Packet Types

In the 802.11 Wi-Fi networking standard, packets are categorized into three main types, each serving a unique purpose in the communication process between wireless devices:

#### **Management Frames**

Management frames are responsible for the establishment and maintenance of communication. They help in associating and disassociating devices with the network.

Examples of management frames include:

* **Beacon frames**: These are broadcast by the access point to signal its presence and relay information such as SSID and supported rates.
* **Authentication frames**: These are used for authentication services between devices and the access point.
* **Association request/response frames**: These frames manage device association with an access point.

#### **Control Frames**

Control frames facilitate the delivery of data frames by helping to control the access to the medium and providing frame acknowledgment.

Common control frames include:

* **Acknowledgment (ACK) frames**: Sent to confirm the successful reception of a frame.
* **Request to Send (RTS) and Clear to Send (CTS) frames**: Used in an optional handshaking process to minimize collisions.

#### **Data Frames**

Data frames carry the actual payload, which is the user data from higher layers. These frames are protected by acknowledgment mechanisms to ensure reliable delivery.

The structure of data frames includes:

* **Frame Control field**: Contains information defining the type of frame.
* **Duration**: Specifies the time period required for the frame.
* **Address fields**: Define the transmitter, receiver, and the BSSID.
* **Sequence Control field**: Helps in ordering frame sequences.
* **Data Payload**: The encapsulated user information.
* **Frame Check Sequence (FCS)**: Used for error detection.

Understanding the functions and structures of these packet types is crucial for diagnosing network issues and enhancing Wi-Fi performance.
