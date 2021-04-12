# IC2

IC2 (ʌɪ siː kjuːb) aims to design and develop an autonomous and distributed infrastructure for information, communication, and computation.  This project will integrate information, communication, and computation functions into one autonomous and distributed infrastructure.  As the platforms of these functions, World Wide Web, the Internet protocol, and cloud computing have been acting important roles.

In IC2, security is a fundamental concept behind all components as shown in the following figure.

    +--------------------------------------------+
    | Security                                   |
    |                                            |
    |           +---------------+                |
    |           | Information   |                |
    |           +---------------+                |
    | +---------------+ +---------------+        |
    | | Communication | | Computation   |        |
    | +---------------+ +---------------+        |
    +--------------------------------------------+



## Essential Components

### Data delivery

* Data type
  * Metadata
  * File
  * Streaming (over datagram)
  * Message
  * Package (archive of files)

* Communication type
  * Unidirectional unicast
  * Bidirectional unicast
  * Multicast
  * Broadcast

### ID & Locator

* ID
  * Person
  * Device
  * Connection
  * Flow
  * Data
  * Packet
* Locator
  * Device or person to deliver data

### AAA: Authentication, Authorization, and Accounting

* Granularity
  * Per-device
  * Per-person
  * Per-connection
  * Per-flow (ADU)
  * Per-packet (PDU)

