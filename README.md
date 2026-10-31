# Smart Attendance System

A web app that counts faces in a class picture, lets the teacher confirm the
number, and saves attendance records to a CSV file.

It counts faces only. It does not identify anyone.

## Features
- Take a picture with the computer's camera
- Upload a picture
- Face detection with OpenCV Haar cascades
- Adjustable scale factor, min neighbors and min face size
- Poor-light boost and side-profile detection
- Attendance records table and CSV download

## Run it
    pip install -r requirements.txt
    python app.py

Then open http://localhost:5000 (use localhost so the camera works).

## Limitations
Haar cascades struggle with masks, tilted heads and dark rooms.
