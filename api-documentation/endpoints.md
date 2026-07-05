# API Documentation

## Authentication

POST /auth/login  
Authenticates doctors and assistants.

## Patients

GET /patients  
Returns patient records.

POST /patients  
Creates a new patient record.

## Queue

GET /queue  
Returns current queue.

POST /queue  
Adds patient to queue.

PATCH /queue/:id/status  
Updates queue status.

## Prescriptions

POST /prescriptions  
Creates a prescription.

GET /prescriptions/:patientId  
Returns prescription history for a patient.
