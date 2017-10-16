# <a name="JPaint"></a>ParkingTicketer [![Analytics](images/readme-icon.png)](https://github.com/DemonFangs/ParkingTicketer)

[![stable](http://badges.github.io/stability-badges/dist/stable.svg)](http://github.com/badges/stability-badges)
[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.png?v=103)](https://github.com/ellerbrock/open-source-badge/)

* [How to Run the Program](#toRun)
* [Requirements](#requirement)
* [Design and Concept](#design)
* [Contributors](#contributors)

## <a name="toRun"></a> How to Run the Program

- Compile
```sh
	javac ParkingTicket.java
```

- Run
```sh
	java ParkingTicket
```

## <a name="requirement"></a> Requirements/Pre-conditions

We assume that the Student Number that the client inputs will hold all the car infomration and insurance infmation on a seperate database. Parking enforcment will be able to do a Student Number search and find all the clients car information and insurance infomration.

The student database, `student.txt`, should have the following information:
* [9-digit Student Number]
* [5-digit PIN for authentication]
* [12-character student email address]
The information should be in the following format in the file:
```txt
	<Student Number> <PIN> <Email>
```

The insurance company database, `companies.txt`, should have the following information:
* [70-character company title]
* [8-digit company policy number]
The information should be in the following format in the file:
```txt
	<Company Title> <Policy Number>
```

## <a name="design"></a> Design and Concept

A university parking permit generator is meant to be used in a kiosk environment. The client will be infront of a touch screen interacting with each field of the GUI. There are three specific fields that the user has to provide information for, so that the permit can be proccessed. The user must provide their `student number`, `PIN` and an optional `email address`.

## <a name="contributors"></a> Contributors

* [Khadem Avinoor Alam](https://github.com/DemonFangs/)
* [Jhan Perera](https://github.com/jhanperera)
* [Bilal Khan]