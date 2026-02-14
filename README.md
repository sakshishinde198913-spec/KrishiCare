# 🌾 KrishiCare -- Smart Crop Disease Detection

### AI-Powered Crop Health Monitoring \| Built for Smart India Hackathon

🔗 Live Demo: https://cropcareai-u7co.onrender.com/

------------------------------------------------------------------------

## About the Project

KrishiCare is an AI-powered crop health monitoring web application built
using Flutter Web. It allows farmers to upload crop images and instantly
detect plant diseases using trained deep-learning models.

The goal is to provide early disease detection, improve crop yield, and
support farmers with accessible technology.

------------------------------------------------------------------------

## Features

AI-Based Crop Disease Detection - Upload crop / leaf images - Detect
possible plant diseases - Display disease name + confidence score

Deep Learning Integration - Backend ML API for predictions - Supports
multiple crops (wheat, rice, maize, etc.) - Uses trained CNN models

Built With Flutter Web - Clean and modern UI - Fully responsive across
devices - Runs directly in browser

Hosted on Render - Stable hosting - Fast and lightweight deployment -
Optimized for Flutter Web

------------------------------------------------------------------------

## Project Structure

lib/ │── main.dart ├── screens/home_screen.dart ├──
widgets/upload_card.dart └── services/api_service.dart

assets/ web/

------------------------------------------------------------------------

## How It Works

User uploads crop image → Flutter Web sends image to ML API → API
processes image using trained model → Prediction + confidence score
returned → Results displayed to the user

------------------------------------------------------------------------

## Tech Stack

Frontend: Flutter Web Backend API: Python / FastAPI / Flask ML Models:
TensorFlow / PyTorch Hosting: Render Storage: Firebase / Cloudinary /
Local Server

------------------------------------------------------------------------

## Run Locally

git clone https://github.com/your-username/krishicare.git cd krishicare
flutter pub get flutter config --enable-web flutter run -d chrome

------------------------------------------------------------------------

## Deployment

flutter build web Upload /build/web to Render Static Site.

------------------------------------------------------------------------

## Future Improvements

-   More crop disease models
-   Offline prediction support
-   Farmer language support
-   Android & iOS mobile apps
-   Crop treatment recommendations

------------------------------------------------------------------------

If you like this project, please star the repo.
