 MK-Travels 🚌

MK-Travels is a full-stack bus ticket booking web application that allows users to search buses, view seat availability, and make/cancel bookings. The project is built with Django (REST API) on the backend and React with Tailwind CSS on the frontend.



 🚀 Features

- User Registration & Login (JWT Token Based)
- Browse and Filter Available Buses
- View Seats and Book Specific Seat Numbers
- View User Booking History
- Cancel Booked Tickets
- Role-based Navigation and Authentication
- Responsive UI built with Tailwind CSS



 🛠 Tech Stack

 Frontend:
- React.js
- React Router
- Axios
- Tailwind CSS
- FontAwesome Icons

 Backend:
- Django
- Django REST Framework (DRF)
- SQLite (for development)
- CORS Headers



 📁 Project Structure

MK-Travels/
├── Backend/
│   ├── bookings/            # Django App (models, views, serializers)
│   ├── travels/             # Django Project (settings, urls)
│   ├── db.sqlite3           # SQLite Database
│   └── manage.py
├── Frontend \ mktravels/
│   ├── src/components/      # React Components
│   ├── App.jsx, index.css   # Main App Files
│   └── tailwind.config.cjs  # Tailwind Setup



⚙️ Setup Instructions

 Backend (Django)

cd Backend
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver


 Frontend (React)

cd Frontend\mktravels
npm install
npm run dev


📌 Usage

1. Register and Login.
2. Search buses by origin, destination, and date.
3. View seat layout and book available seats.
4. View your bookings under "My Bookings" and cancel if needed.
5. Logout when done.



 💡 Future Enhancements

- Admin dashboard for bus management.
- Online payment integration.
- Email confirmation for bookings.
- Add unit and integration tests.



 🙌 Acknowledgements

Created by MK using Django & React.
