# ALX Travel App — Milestone 2

This project implements database models, serializers, and a custom seeder command for populating the database with sample data.

## Features

- Django models for:
  - Listing
  - Booking
  - Review
- DRF serializers for:
  - Listing
  - Booking
- Custom management command:
  - `seed` — populates the database with sample listings.

## Running the Seeder

Run the command below:
python manage.py seed


This will create sample listings for development and testing.

## Directory Structure

alx_travel_app/
├── listings/
│   ├── models.py
│   ├── serializers.py
│   ├── management/commands/seed.py

