# MediCo - Rural Healthcare Platform

## Overview

MediCo is a web-based healthcare platform designed to bridge rural communities with essential medical services. It enables seamless interaction between patients, doctors, and pharmacies, allowing users to book appointments, order medications, manage their healthcare efficiently, and access health information through education resources and symptom checking tools.

## Features

- **Patient Portal**: Browse and book appointments with available doctors
- **Doctor Management**: Manage patient schedules and appointments
- **Pharmacy Integration**: Order medications online with delivery options
- **Appointment Booking**: Convenient scheduling system for healthcare services
- **User Authentication**: Secure login and registration for all users
- **Health Education**: Access comprehensive health information and educational resources
- **Symptom Checker**: Identify potential health conditions based on symptoms
- **Responsive Design**: Mobile-friendly interface for accessibility

## Tech Stack

- **Frontend**: HTML (62.8%), CSS (3.1%)
- **Backend**: Python (34.1%)
- **Framework**: Flask (web framework)
- **Database**: SQL-based storage
- **Architecture**: MVC (Model-View-Controller)

## Architecture

MediCo follows the **MVC (Model-View-Controller)** architecture pattern:

### Model Layer
- User, Doctor, Patient, and Appointment models
- Medication and Pharmacy data models
- Health education and symptom checker data models
- Database interactions and business logic

### View Layer
- HTML templates for patient portal
- Doctor management interface
- Pharmacy interface
- Health education portal
- Symptom checker interface
- User authentication pages

### Controller Layer
- User authentication controller
- Appointment booking controller
- Pharmacy order controller
- Doctor schedule management controller
- Health education controller
- Symptom checker controller

## Project Structure

```
Final-Project-Medico/
├── app.py                 # Main Flask application
├── models/               # MVC Model layer
├── controllers/          # MVC Controller layer
├── views/               # MVC View layer (templates)
├── static/
│   └── CSS/              # Stylesheet files
├── templates/            # HTML templates
├── database/             # Database configurations
└── README.md
```

## Usage

### For Patients
1. Register or log in to your account
2. Browse available doctors and their schedules
3. Book an appointment at your preferred time
4. Order medications through the pharmacy section
5. Access health education resources
6. Use the symptom checker tool for health concerns
7. Track your appointments and orders

### For Doctors
1. Log in to your doctor account
2. View and manage patient appointments
3. Update your availability schedule
4. Track patient information

### For Pharmacies
1. Manage medication inventory
2. Process patient orders
3. Arrange deliveries
4. Track order history

## Features in Detail

### Appointment Booking System
- Easy-to-use scheduling interface
- Real-time availability updates
- Appointment reminders and notifications

### Medication Ordering
- Browse available medications
- Secure ordering process
- Delivery tracking

### Health Education
- Comprehensive medical information
- Health tips and guidelines
- Disease prevention resources
- Wellness articles and guides

### Symptom Checker
- User-friendly symptom identification tool
- Potential condition suggestions
- Medical information for identified symptoms
- Recommendation to consult doctors

### User Profiles
- Manage personal health information
- View appointment history
- Track medication orders
- Access symptom checker history

## Database

The application uses a SQL-based database to store:
- User accounts and profiles
- Appointment schedules
- Medication inventory
- Order history
- Health education content
- Symptom checker data and history

## Security Features

- User authentication and authorization
- Secure password handling
- Protected user data

## Future Enhancements

- Online consultation features
- Video appointment capability
- Prescription management
- Health records digitization
- Payment gateway integration
- SMS/Email notifications

## Contributing

Contributions are welcome! Please feel free to submit issues and pull requests.

## License

This project is open source and available for educational purposes.

## Author

**Ashraful Alam**  
GitHub: [@AshrafulAlam07](https://github.com/AshrafulAlam07)
