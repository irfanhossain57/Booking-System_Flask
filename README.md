# Booking-System_Flask
A all in one booking system

## Deploy on Vercel

This project is configured for Vercel with:

- `vercel.json` pointing to `api/index.py` as the Python serverless entrypoint
- `requirements.txt` for Python dependencies

### Required environment variables

Set these in your Vercel project settings:

- `MONGO_URI` (your MongoDB connection string)
- `FLASK_SECRET_KEY` (any long random value)
