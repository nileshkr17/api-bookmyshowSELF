# Movie Booking API

The Movie Booking API is a RESTful API that allows users to browse and book movie tickets for various movies and locations. It provides endpoints to retrieve movie details, locations, and book tickets.

## Installation

To run the Movie Booking API locally, follow these steps:

1. Clone the repository: `git clone https://github.com/your-repo/movie-booking-api.git`
2. Navigate to the project directory: `cd movie-booking-api`
3. Install dependencies: `npm install`
4. Start the server: `npm start`
5. The API will be available at `http://localhost:8000`

## API Endpoints

The API provides the following endpoints:

### Movies

- `GET /movies`: Retrieve a list of all movies.
- `GET /movies/{id}`: Retrieve details of a specific movie by ID.

### Locations

- `GET /locations`: Retrieve a list of all locations.

### Bookings

- `POST /bookings`: Create a new booking.
- `GET /bookings/{id}`: Retrieve details of a specific booking by ID.

## API Usage

To use the Movie Booking API, send HTTP requests to the appropriate endpoints using a tool like cURL or an API testing tool such as Postman.

### Example Requests

#### Retrieve a list of all movies

```
GET /movies
GET /movies/1
GET /locations

```