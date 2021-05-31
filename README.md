# eTour-documentation

Learn about architecture and component solutions from this documentation.

From each repository of eTour project, you will find a README file describing the technical documentation for the specific component and instructions for further development.

# eTour Project

eTour is a beacons software development project created by LUT University master students. This documentation is intended to assist in the further development of the product. This documentation is the technical documentation of eTour and walks through the design decisions and structure of the implementations. With this documentation, the admin or developer will gain knowledge about the environment. Please take a look at project repositories' README files to get instructions, how to set up and modify the environment.

## eTour - Create Tours with Beacons

**eTour provides iOS and Android mobile applications.** These apps can be used to create a tour controlled by a mobile app. User selects a tour and app introduces the target place by directing the user from the beacon to the next. On a tour stop, the beacon launches a dynamic and customized web page and app displays targeted information, images, and videos.

eTour has mobile applications for iOS and Android operating systems. Solution has also NodeJS backend solution, NoSQL database and Redis memory cache. User Interface is developed with Flutter and moth mobile operating systems are using Flutter.

# Architecture

eTour has two mobile applications with iOS and Android operating systems. Backend solution is running in Google Cloud Platform and Firebase NoSQL database stores the tour specific contents. Functional view is presented in figure 1. Sequence diagram of the beacon discovery in action is presented in figure 2.

![Functional view.](https://github.com/Beacon-eTour/eTour-documentation/blob/main/figures/eTour_functional-view.png "Functional view.")

`Figure 1: Functional view of eTour app`

![Sequence diagram.](https://github.com/Beacon-eTour/eTour-documentation/blob/main/figures/eTour_sequence-diagram.png "Sequence diagram")
`Figure 2: Sequence diagram of eTour app`
# UI

Coming up: user Interface examples (mockups) for mobile applications, tours and menus.

# Creators of eTour

* Juho Kontiainen		 
* Mahyar Mohammadi	 
* Loan Ngo 			 
* Piret Niva			 
* Topi Penttilä
* Riina Purovesi

eTour was created as a LUT University course project. LUT University (Lappeenranta-Lahti University of Technology LUT) was established in 1969 in Finland. Creators of eTour are master students at Lahti in LUT School of Engineering Science.

## Contact

We are very interested to hear that kind of projects eTour has been used for and how it has been further developed. Send news or questions to us at:
beacon.etour[at]gmail.com. Important: mention **eTour** in the topic, when you send us e-mail, thank you!
