# Investigate a Dataset - No-show appointments
## by Nndweleni Sundani


## Dataset

The dataset being analyzed contains information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. A number of characteristics about the patient are included in each row.

Below is a list of column names (and explanations) for our dataset:

PatientId - it a unique identification number for each patient.
AppointmentID - it a unique identification number for each appointment.
Gender - indicates the gender of the patient.
ScheduledDay - tells us on what day the patient set up their appointment.
Age - indicates the age of the patient.
Neighborhood - indicates the location of the hospital.
Scholarship - indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família.
Hipertension - indicates whether or not the patient has hypertension.
Diabetes - indicates whether or not the patient is diabetic.
Alcoholism - indicates whether or not the patient consumes alcohol.
Handcap - indicates whether or not the patient is a handicap.
SMS_received - indicates whether or not the sms was received by the patient.
No-show - indicates whether or not the patient showed up for the appointment.

## How to run the script
You can run the script using a Python integrated development environment (IDE). This script is written in Python 3, so you will need the Python 3.x version of the installer. To read the file, the following software requirements apply:

- You should have Python 3, NumPy, and pandas installed using Anaconda
- A text editor, like Sublime or Atom.
- A terminal application (Terminal on Mac and Linux or on Windows).


## Summary of Findings

Most of the patients are younger people and this we were able to see using a histogram distribution which showed that the highest number of patients were of ages 0-5, 25-40, and 45-65. It does make sense as the older population (more than 65 years) is also few. Our mean age was 37.

Female appointments comprised almost 2/3 of the total appoitments. Male patients only comprised 35% which is quite low. .Our analysis found no correllation between the gender of a patient and the missing of an appointment.Surprisingly, the proportion of patients who miss appointments is almost the same for both genders

Alcoholism does not have any effect to predict whether or not the patient will show-up for the appointment. The sample for patient described as alcoholism was only 3% which is very low, and because of that, we cannot really draw meaningful insight using such a small sample.

SMS reminders are counter-intuitive as patients who received them represent a higher number of people who missed appointments compared to those who did not receive SMS.
