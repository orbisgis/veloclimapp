# VeloClimApp
A flutter app used to collect data from sensors mounted on a bike.
=======

# Description

The VeloClimApp application allows users to communicate via Bluetooth with the VeloClimap sensor, which was developed at the Lab-STICC as part of the VeloClimat project.
This initiative is sponsored by the GEOMANUM Foundation.



  VeloClimApp      | VeloClimap sensor       | 
 |-----------------|------------------|
 | <img width="300"  alt="image" src="https://github.com/user-attachments/assets/1317dd4b-8b86-45b4-8d8e-374c21a712a1" /> | <img width="300"  alt="image" src="https://github.com/user-attachments/assets/c5c09fc4-eb34-40d8-870b-92307212e8b3" />
 |

# sensor_logging

Flutter source code for the android app used for low cost sensors (VeloClimApp)
Tested with Android 11
Permission problems with android 14

## Build

To build :  
```bash
flutter clean
flutter pub get
flutter build apk --release
```

## TODO
- remove prints
- fix double tap on stop button
- eventually permissions for more android versions to work
- push data on a server

