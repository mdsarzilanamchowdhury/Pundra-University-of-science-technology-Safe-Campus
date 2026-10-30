# PUB SafeCampus

### Emergency Response and Campus Safety Application

**Track C: Smart Campus Services | PUB CSE Fest-26 Hackathon**

## 1. Project Description

When a student faces harassment, an accident, a medical problem or a fire on campus, the quickest help is usually nearby security staff or the proctor's office, but students often do not know whom to contact and nothing is recorded.

PUB SafeCampus is an emergency response and campus safety application that enables students and staff to raise emergency alerts or report incidents within seconds, routes them to the appropriate responders with location information, and tracks each incident until it is resolved.

## 2. Required Features

### 1. SOS Emergency Alert

An SOS button with hold-to-confirm functionality and a short cancellation countdown that sends the user's identity, live location, and time to the security desk and personal emergency contacts.

### 2. Incident Reporting

Report incidents by category:

* Medical
* Harassment
* Ragging
* Fire
* Accident
* Theft
* Hazard

Users can submit descriptions, photos or videos, and location information through a map pin or by specifying the building and room.

### 3. Anonymous Reporting

Anonymous reporting for sensitive categories such as harassment and ragging to protect the identity of the reporter.

### 4. Responder Dashboard

A dashboard displaying active alerts on a map, ordered by severity, with responder assignment and acknowledgement functionality.

### 5. Incident Status Tracking

Track incident progress through the following statuses:

* Reported
* Acknowledged
* Responder on the Way
* Resolved

Timestamps remain visible to the reporter, with chat functionality between the reporter and responder.

### 6. Campus Emergency Directory

One-tap access to emergency contacts:

* Security
* Medical Centre
* Proctor
* Fire Service
* Ambulance

### 7. Broadcast Alerts

Security office can broadcast emergency alerts to all users, such as fire drills and flood warnings, with read confirmation.

### 8. Offline Fallback

Queue incident reports when internet connectivity is unavailable and send them when the connection returns, or prepare an SMS.

### 9. Incident History and Reports

Maintain incident history and generate reports covering:

* Response time
* Incidents by category
* Incidents by location
* Incident heat map

## 3. User Roles

| User Role              | Responsibilities                                                               |
| ---------------------- | ------------------------------------------------------------------------------ |
| Student / Staff        | Raises SOS alerts, reports incidents, and follows incident status.             |
| Responder              | Security staff, medical officer or proctor who accepts and resolves incidents. |
| Security Administrator | Manages responders, broadcasts alerts, and views reports.                      |

## 4. Restrictions and Safety

* The application must be clearly labelled as a prototype and provide a test mode.
* Never contact real emergency services (such as 999) during testing.
* Location is shared only with permission and only while an alert is active.
* Anonymous reports must not reveal the reporter's identity.

## 5. Optional Features

* Nearest-responder selection
* Fake-call feature
* SMS simulation
* Walk-with-me live location sharing
* Shake-to-alert

## 6. Live Website

**Live Demo:** https://pub-safecampus.onrender.com/

## 7. Important Notice

PUB SafeCampus is developed as a prototype for academic and hackathon purposes. It is intended for testing and demonstration and should not be used as a replacement for real emergency services.
