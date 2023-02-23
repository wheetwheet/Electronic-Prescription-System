# Electronic-Prescription-System
Software Development Methodologies Proejct

This project aims to design and develop an electronic prescription system. 
The system serves as a platform for doctors, patients and pharmacies. Doctors will use the system to issue prescriptions for their patients. Once a prescription is issued, a “token” is generated in the form of a string code and a QR code, and sent to the patient (via email or optionally SMS). To get the prescription dispensed, the patient visits a pharmacy and shows the electronic prescription token (e.g. on their phone). The pharmacy then dispenses the appropriate medicines and dosage based on the doctor’s prescription associated with the token. The pharmacy can also update status of the prescription (e.g. date of dispensed, number of supplies left, etc.)

The system should support at least the following key aspects.
1. Support and manage different types of users and user profiles.
2. Support doctors in providing and managing electronic prescriptions for their patients.
3. Support patients in seeing their past and new prescriptions.
4. Support pharmacies in accessing prescriptions (through tokens using the associated string code and/or QR code – accessing using QR code is optional) and updating the prescriptions’ status.
5. Support the generation and transmission of tokens.
