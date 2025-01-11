E-Voting System

A secure and efficient E-Voting system built with Django. This project allows registered users to vote electronically in elections while ensuring privacy, authentication, and result integrity.

Features

User Authentication: Secure login and registration for voters and admins.

Election Management: Admins can create and manage elections and candidates.

Secure Voting: Each user can cast a vote for a specific election, ensuring anonymity.

Real-Time Results: Display election results instantly after the voting period ends.

Responsive Design: Optimized for desktop and mobile devices.

Requirements

Python 3.8+

Django 4.0+

PostgreSQL (or any other database supported by Django)

Setup Instructions

Clone the Repository:

git clone https://github.com/nadeali0999/e-voting-system.git
cd e-voting-system

Create a Virtual Environment:

python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate

Install Dependencies:

pip install -r requirements.txt

Set Up Environment Variables:
Create a .env file in the project root and configure the following:

SECRET_KEY=your_secret_key
DEBUG=True
DATABASE_URL=your_database_url

Apply Migrations:

python manage.py migrate

Run the Development Server:

python manage.py runserver

Access the application at http://127.0.0.1:8000/.

Usage

Admin Panel:

Access the admin panel at http://127.0.0.1:8000/admin/.

Create elections, candidates, and manage users.

Voter Portal:

Users can register, log in, and vote in active elections.

Election Results:

View real-time results once voting is complete.

![4](https://github.com/user-attachments/assets/b800901f-3db3-4b9d-bf31-c5ce7a04fc81)
![1](https://github.com/user-attachments/assets/08b20d6a-b546-45b4-9a64-58be9ca7d4f4)
![6](https://github.com/user-attachments/assets/f4f74f25-2d15-423d-9c4d-8de0d9bb926e)
![10](https://github.com/user-attachments/assets/3e002e92-9b8b-4f0e-8838-92db28ba3347)


![1](https://github.com/user-attachments/assets/62f0c3f9-32e8-44d0-94d3-d789ba73b482)
