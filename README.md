# Movie Ticket Booking System

## Project Overview
A web-based application that allows users to browse available movies, select showtimes, choose seats, and book tickets online. Built with Django for the backend and standard web technologies for the frontend.

## Features
- **User Authentication**: Register and log in to manage bookings.
- **Movie Listings**: View current and upcoming movies with details (title, duration, genre, poster).
- **Showtimes**: Display available showtimes for each movie.
- **Seat Selection**: Interactive seating chart to select and reserve seats.
- **Booking Confirmation**: Email confirmation with ticket details.
- **Admin Dashboard**: Add, update, or remove movies, showtimes, and manage bookings.
- **Search & Filters**: Search by movie title and filter by genre, language, or rating.
- **(Optional) Payment Integration**: Pay online via Stripe or PayPal.

## Technology Stack
- **Backend**: Django (Python)
- **Frontend**: HTML5, CSS3, JavaScript
- **Database**: SQLite (development), PostgreSQL or MySQL (production)
- **Templates**: Django Templates
- **Version Control**: Git & GitHub

## Installation & Setup
1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/movie-ticket-booking.git
   cd movie-ticket-booking
   ```

2. **Create Virtual Environment**
   ```bash
   python3 -m venv venv
   source venv/bin/activate   # On Windows: venv\\Scripts\\activate
   ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Database Migrations**
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

5. **Create Superuser (Admin)**
   ```bash
   python manage.py createsuperuser
   ```

6. **Run the Development Server**
   ```bash
   python manage.py runserver
   ```
   Access the app at `http://localhost:8000`.

## Usage
- **User**: Browse movies, select showtime, pick seats, confirm booking.
- **Admin**: Log in to `/admin`, manage movies, showtimes, and view bookings.

## Project Structure
```
movie-ticket-booking/
├── booking/            # Django app for bookings
├── movies/             # Django app for movie listings
├── users/              # Django app for authentication
├── templates/          # HTML templates
├── static/             # CSS, JS, images
├── manage.py
└── requirements.txt
```

## Contributing
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/name`)
3. Commit your changes (`git commit -m "Add feature"`)
4. Push to branch (`git push origin feature/name`)
5. Open a Pull Request

*Happy coding!*
