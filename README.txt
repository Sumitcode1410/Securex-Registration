# SECUREX Event Registration Portal

This is a mobile-first, screenshot-inspired event registration portal built for SECUREX.

## Stack
- Google Apps Script Web App
- Google Sheets as database
- HTML/CSS/JavaScript
- QR code E-Pass

## Setup

1. Create a Google Sheet.
2. Open Extensions -> Apps Script.
3. Create `Code.gs` and paste the Code.gs content from this folder.
4. Create an HTML file named `index` and paste the index.html content.
5. In Code.gs, edit the `CONFIG` object:
   - COLLEGE
   - EVENT_NAME
   - EVENT_TAG
   - EVENT_DESCRIPTION
   - DATE
   - DAY
   - TIME
   - VENUE
   - MENTOR
   - WHAT_YOU_LEARN
   - REGISTRATION_FEE
6. In Apps Script, select `setupSheet` and Run once. Give Google permission.
7. Deploy -> New deployment -> Web app.
8. Execute as: Me.
9. Who has access: Anyone.
10. Copy the Web App URL and share it with students.

## What students can do
- Open the link on phone
- Fill registration form
- Submit
- Receive unique Registration ID
- Get QR E-Pass
- Search their pass later using Roll Number, Email or Registration ID
- Print / Save PDF

## Data
All submitted registrations are stored in the Google Sheet tab named `Registrations`.

## Important
Do not put passwords, API keys or private credentials into the frontend.
For a public production event, restrict access to the Sheet itself and only share the Web App URL.


Poster configuration applied:
College: Moradabad Institute of Technology (MIT)
Society: SecureX Cyber Club
Event: CYBER QUEST 2026
Date: 2 September 2026 (Wednesday)
Time: 2 PM Onwards
Venue: B-120 Seminar Hall
Faculty Convener: Mr. Vikas Bhatnagar
Academic Year: 2nd Year, 3rd Year
Branch: Text input
Class Section: Text input


FINAL EVENT INFORMATION SHOWN TO STUDENTS:
Moradabad Institute of Technology (MIT)
SecureX Cyber Club
CYBER QUEST 2026
2 September 2026 — Wednesday
2 PM Onwards
B-120 Seminar Hall
Faculty Convener: Mr. Vikas Bhatnagar
THINK. EXPLORE. LEARN. AWARE.
Cyber Challenges
Real-world scenario awareness
Exciting Prizes
Learn. Compete. Grow Together.
