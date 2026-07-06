# Responsive BMI Calculator Web Application

A user-friendly, responsive Body Mass Index (BMI) Calculator built using HTML5, CSS3, and JavaScript. This application calculates BMI based on age, gender, height, and weight, providing instant classification feedback.

# Features
*  Clean layout with interactive form elements.
*  Computes BMI dynamically using the standard formula.
*  Visual indicators for Underweight, Normal, Overweight, and Obese ranges.
*  Optimized for desktops, tablets, and smartphones.

---
##  Docker Documentation

### 1. Build the Docker Image
docker build -t bmi-calculator:v1 .
### 2. Run the Image as a Container
docker run -d -p 8080:80 --name bmi-app-container bmi-calculator:v1
### 3. Pull the Image
docker pull hello world 
### 5. Stop the Running Container
docker stop bmi-app-container

