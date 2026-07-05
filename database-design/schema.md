# Database Overview

The PatientView database is designed around clinic workflows.

Main entities:

- Doctors
- Assistants
- Patients
- Treatments/Consultations
- Patient Queue
- Drug Catalog

Relationships:

- Each doctor can manage multiple patients.
- Each patient can have multiple consultations.
- Each consultation is linked to a doctor.
- Assistants manage patient registration and queue operations.
- Prescriptions are generated using entries from the drug catalog.
