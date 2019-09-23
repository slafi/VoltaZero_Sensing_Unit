# VoltaZero Shield

VoltaZero is an Arduino Uno shield which encompasses a total of five onboard and external sensors. It was designed as part of the VoltaZero Sensing Unit which combines a microcontroller (Arduino Uno), a connectivity means (Helium Atom) and a sensing board (VoltaZero Shield). The primary usage of the shield is for environment control. However, it was designed with extensibility in mind. It supports external sensors through onboard built-in relays. 

# VoltaZero Sensors

| Sensor        | Pin           | Type  | Location  |
|:------------- |:------------- |:----- |:----- |
| Temperature sensor (t0) | A0 | IN | onboard |
| Temperature sensor (t1) | A1 | IN | external |
| Light sensor | A2 | IN | onboard |
| Extension relay (r1) | A3 | IN/OUT | external |
| Extension relay (r2) | A4 | IN/OUT | external |
| Active buzzer | D2 | OUT | onboard |

![alt text](resources/voltazero_shield.png "VoltaZero Shield Sensors")
*VoltaZero Sensing Unit: A collection of sensors with MCU and connectivity*

# Data Flow

One Paragraph of project description goes here

![alt text](resources/vzero_data_flow.png "VoltaZero Data Stream")

# Project Description

One Paragraph of project description goes here

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

```
Give examples
```

### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE.md) file for details.

## Acknowledgments

* **A. Elzayat** - Design of the VoltaZero Shield.
