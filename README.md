

#                                                         WILDLIFE TRACKER! :paw_prints:

## AUTHOR

NELSON KIMANI

## DESCRIPTION :page_with_curl: :paw_prints:

This application allows Rangers to track wildlife sightings in the area, record them and ensure the animals are isolated to a safer zone.

[Check-Out App!](https://tracker-wild-life4.herokuapp.com)

## User Story

- Ranger can add a Animal.

- Ranger add a Sighting of a Single Animal

- Ranger can delete both Animal and Sightings Recorded.

- Application can Keep track of Engdangered animals, health, date of sighting, location age, identity number and number of animals. 

## PRE-REQUISITES.

A couple of things to get you started:

1. Ensure you have [Java](https://java.com/en/download/) installed

A simple way to install Java is using [sdkman](https://sdkman.io/).

Simply follow the instructions to have _sdkman_ installed and install java:

```bash
sdk install java
```

2. [Gradle](https://gradle.org/)

Gradle is used as the build tool and can be installed with sdkman:

```bash
sdk install gradle
```

3. Postgresql

Ensure you have installed postgresql on your localmachine

- Open your bash terminal

NOTE!

The ``` $ ``` and ``` =# ``` are only used to indicate the current location!... DO NOT TYPE THEM!

- Initialize postgresql Database using the below commands.

```
$ psql
```

- Create DataBase

```
=# CREATE DATABASE wildlife_tracker;
```

- Connect to DataBase

```
=# \c wildlife_tracker
```

- Create Animal Table

```
=# CREATE TABLE sightings (id serial PRIMARY KEY, animalname varchar, sightlocation varchar, ranger varchar,spotted TIMESTAMP);

```

- Create Sightings Table

```
=# CREATE TABLE sightings (id serial PRIMARY KEY, animalname varchar, sightlocation varchar, ranger varchar,sighted_date TIMESTAMP);

```

- CREATE Test DataBase

```
=# CREATE DATABASE wildlife_tracker WITH TEMPLATE wildlife_tracker_test;
```

## **SETUP/INSTALLATION!**

**{follow the below instructions for set up.}**

1. You will need Internet connection.

2. You need to get into the Project Repository.

Link:-> ```https://github.com/AceNel/Wildlife-Tracker```

3. From there you can access the Wildlife Tracker.

4. **Clone** the project.

5. **get into project folder** (cd into project).

6. If you have all the **Pre-requisites** you can run the application.

```
gradle run
```

### TECHNOLOGIES USED:

- **[Java](https://java.com/en/download/) - source language.**

- **[Gradle](https://gradle.org/) for dependency management and running tasks.**

- Bootstrap.

- Cascading Style Sheets.

- Handlebars engine.

## License
MIT 2019 NELSON KIMANI
