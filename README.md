# Java DAO Project

## Project Description

This Java project is designed to implement Data Access Objects (DAOs) for managing places and trips. The application includes two main DAOs: PlaceDao and TripDao.

### PlaceDao

1. **createPlace(Place p):** Adds a new place to the database.
2. **findPlaceById(Long id):** Retrieves a place based on the provided ID.
3. **updatePlace(Place p):** Updates the information of an existing place.
4. **removePlace(Place p):** Deletes a place from the database.

### TripDao

1. **createTrip(Trip t):** Creates a new trip and adds it to the database.
2. **findTripById(Long id):** Retrieves a trip based on the provided ID.
3. **removeTrip(Trip t):** Removes a trip from the database.

### Classes

1. **Place (Long id, String name):** Represents a place with an ID and a name.
2. **Trip (Long id, Place departure, Place destination, double price):** Represents a trip with an ID, departure place, destination place, and price.
3. **MainTest:** Contains the main method for testing the functionality of the DAOs.

## Internationalization

The application supports multiple languages, and the menu language is configurable through a .properties file. The language is loaded at the start based on the user's preferences.

## Getting Started

To get started with the project, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/your-repo.git`
2. Open the project in your preferred Java IDE.
3. Configure the language settings in the .properties file.
4. Run the MainTest class to test the functionality of the DAOs.

## Dependencies

This project has the following dependencies:

- [my-sql-connector](https://mvnrepository.com/artifact/mysql/mysql-connector-java): MySQL Driver.


