# VeloClimApp

![Flutter](https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?logo=dart&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?logo=android&logoColor=white)
![Bluetooth](https://img.shields.io/badge/Bluetooth-0082FC?logo=bluetooth&logoColor=white)

A Flutter app used to collect data from sensors mounted on a bike.

## Description

VeloClimap is the companion Android app for the VéloCliMap sensor (nicknamed "le lancement papate"), a device developed at the Lab-STICC research lab and mounted on a bicycle to measure air temperature and humidity while riding. The app connects to the sensor via Bluetooth to collect these physical measurements along with the smartphone's GPS position, then stores the data in a CSV file that can be shared afterward. In its latest version, the app can also upload the data directly to a mapping server through a dedicated endpoint, in addition to local CSV export. Its development has been supported by the Geomanum Foundation.

It's part of the broader VéloClimat citizen-science project — a multi-day cycling route where participants take part in workshops (called "thermoParties") to record air temperature readings using the VeloCliMap sensor. The collected data follows open-science FAIR principles, feeding into a public mapping portal for researchers, local authorities, and citizens to explore.

| VeloClimApp | VeloClimap sensor |
|:---:|:---:|
| <img width="300" alt="VeloClimApp screenshot" src="https://github.com/user-attachments/assets/1317dd4b-8b86-45b4-8d8e-374c21a712a1" /> | <img width="300" alt="VeloClimap sensor" src="https://github.com/user-attachments/assets/c5c09fc4-eb34-40d8-870b-92307212e8b3" /> |

## Requirements

- Android 11+
- Bluetooth and Location permissions enabled
- VeloClimap sensor device (see [geomanum.org/fr/projets/veloclimat](https://geomanum.org/fr/projets/veloclimat))

## Build

To build:

```bash
flutter clean
flutter pub get
flutter build apk --release
```
