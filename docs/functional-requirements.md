## Functional requirements

* two sensors can be bundled together and connected to one device
* sensor data is manipulated simultaneously for both sensors
* iOS and Android applications must be available
* internet traffic to and from cloud services should be kept under 30 kBps
* polling rate/discretization frequency should be high enough to capture sufficient data
  * punches should be easily identifiable and isolated
* on-device computing should be kept to the bare minimum
* punch velocity, generated force and punch count should be computed
* databases of raw and processed/punch data should be permanently available
  * database constraints include the ability to handle hundreds of I/O operations per second with minimal delay (ms)
* memory usage, battery consumption and other device resources should be kept in mind


### Likely use cases or basic functions
* **FEEDBACK FROM STAKEHOLDERS** - appointments, payments, etc.
