# Doctor Consultation Fee Prediction

## Introduction
This project aims to predict the consultation fee of doctors based on various factors such as specialty, degree type, years of experience, location, city, doctor-patient score, and number of people votes. Data is collected from the online medical consultancy booking site Practo for cities like Delhi, Mumbai, and Bangalore.

## Data Collection
The Practo website was scraped using Python's BeautifulSoup library to gather doctor's details including their name, specialty, degree type, years of experience, location, city, doctor-patient score, number of people votes, and consultation fee.

## Dataset Description
The dataset comprises the following fields:
name: Name of the doctor
speciality_of_doctor: Specialty of the doctor (e.g., dentist, gynecologist, pediatrician)
degree_type: Degree type (e.g., MBBS, MS, MD, BDS)
year_of_experience: Total years of experience
Location: Location of the clinic
city: City of the clinic
dp_score: Doctor-patient experience score
npv: Number of people votes
consult_fee: Consultation fee at the clinic

## Machine Learning Model
A machine learning model has been developed utilizing the collected data to predict the consultation fee for doctors. The model incorporates various features such as specialty, degree type, years of experience, location, city, doctor-patient score, and number of people votes for accurate predictions.

## Web Application
A web application has been created where users can input the following values:
speciality_of_doctor: Specialty of the doctor
degree_type: Degree type
year_of_experience: Years of experience
Location: Location of the clinic
city: City of the clinic
dp_score: Doctor-patient experience score
npv: Number of people votes

Based on these inputs, the web application predicts the consultation fee for the doctor.

