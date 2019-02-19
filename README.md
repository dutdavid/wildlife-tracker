# Project Name: Wildlife Tracker

An an application that allows Rangers to track wildlife sightings in the area by adding either endangered animals or normal animals and a sighting that they were seen in.

## Created by: David Dut

## Prerequisites

You will need the following things properly installed on your computer.

* JRE
* JDK

##The applications allows users to do the following:

    * Add an animal
    * Add an engangered animal
    * Add a sighting
    * Delete and edit animals and their sightings

## Setup/Installation Requirements

1.On GitHub, navigate to the main page of the repository.

2.Under the repository name, click Clone or download.

3.In the Clone with HTTPs section, click to copy the clone URL for the repository.

4.Open Terminal.

5.Change the current working directory to the location where you want the cloned directory to be made.

6.Type git clone, and then paste the URL you copied in Step 2.

7.Press Enter. Your local clone will be created.

## Setup/Installation Requirements

* _Make sure you have Java, Gradle installed._
* _Clone this repository from my Github named dutdavid._

## Behavior Driven Development
| input                    |    output                             |   
|--------------------------|---------------------------------------| 
| add an animal            |  displays all animals                 |
| add endangered animals   | displays all animals                  | 
| click add Cient          | succefulyy added client               |
| Delete animal            |  succefully deleted stylist           | 
| Delete sighting          |  succefully deleted sighting          | 

## Running / Development

* `gradle run`

### Running Tests

* `gradle test`

### Building

* `gradle build`

### SQL

* Launch postgres
* Type in psql
* Run the following commands:

* `CREATE DATABASE wildlife_tracker;`
* `\c wildlife_tracker;`
* `CREATE TABLE animals (id serial PRIMARY KEY, name varchar, health varchar, age varchar, type varchar);`
* `CREATE TABLE
wildlife_tracker=# CREATE TABLE sightings (id serial PRIMARY KEY, animal_id int, location varchar, ranger_name varchar, timestamp timestamp);`
* `CREATE DATABASE wildlife_tracker_test WITH TEMPLATE wildlife_tracker;`

### License

*This software is Licensed under the MIT License.*

Copyright (c) 2019 **_David Dut_**
