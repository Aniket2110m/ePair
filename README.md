# ePair - Service Booking Platform

A full-stack service booking application built with Laravel (Backend) and Flutter (Frontend).

## Project Structure

```
ePair/
├── Backend/          # Laravel API backend
└── Frontend/         # Flutter mobile & web application
    └── User app and web/
```

## Backend (Laravel)

### Requirements
- PHP 8.0+
- MySQL/MariaDB
- Composer

### Installation
```bash
cd Backend
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve
```

The backend will run on `http://localhost:8000`

## Frontend (Flutter)

### Requirements
- Flutter SDK 3.38.9+
- Dart 3.10.8+
- Android Studio (for Android builds)
- Chrome/Edge (for web builds)

### Installation
```bash
cd "Frontend/User app and web"
flutter pub get
flutter run -d chrome  # For web
flutter build apk      # For Android APK
```

### Configuration
Update the API base URL in:
- `lib/core/helper/api_checker.dart`

## Features
- User authentication (Email, Google, Facebook, Apple)
- Service browsing and booking
- Real-time chat
- Payment integration
- Multi-language support (English, Arabic, Bengali, Hindi)
- Push notifications
- Location-based services

## Tech Stack

### Backend
- Laravel 9.x
- MySQL
- Firebase (Push notifications)
- RESTful API

### Frontend
- Flutter 3.38.9
- GetX (State Management)
- Firebase Integration
- Google Maps
- Payment Gateways

## License
All rights reserved.

## Contact
For any queries or support, please contact the development team.
