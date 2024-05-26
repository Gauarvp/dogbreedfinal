### Project Manual for Dog Breed Classification System

#### Table of Contents

1. Introduction
2. Project Setup
   - Prerequisites
   - Installation
3. Running the Project
   - Starting the Server
   - Accessing the Application
4. Features
   - Dog Breed Classification
   - Dog Marketplace
   - Dog Training Videos
   - Chatbot
   - Pet-Friendly Places
   - Dog Walkers and Sitters
   - QR Code for Lost Dogs
   - Authentication and Database Management
5. Troubleshooting
6. Team Information
7. Contact Information

### 1. Introduction

This manual provides detailed instructions on how to set up, run, and use the Dog Breed Classification system. The system includes features like dog breed classification using machine learning, a marketplace for dog-related products, training videos, a chatbot for assistance, information on pet-friendly places, services for dog walkers and sitters, a QR code system to find lost dogs, and authentication using a local database file. The project will be distributed on a CD-ROM.

### 2. Project Setup

#### Prerequisites

- Python 3.x
- Necessary Python libraries (listed in `requirements.txt`)

#### Installation

1. **Insert the CD-ROM**:
   - Insert the CD-ROM containing the project files into your computer's CD drive.

2. **Copy the Project Files**:
   - Copy the entire project directory from the CD-ROM to your local machine.

3. **Set up the Python environment**:
   - Open a terminal or command prompt and navigate to the project directory.
   - Run the following commands:
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows use `venv\Scripts\activate`
   pip install -r requirements.txt
   ```

4. **Set up the local database**:
   - Ensure that the local database file (e.g., `users.db`) is in the correct location as specified in your project configuration.

### 3. Running the Project

#### Starting the Server

1. **Start the backend server**:
   ```bash
   python app.py
   ```

#### Accessing the Application

- Open your web browser and navigate to `http://localhost:5000` to access the application.

### 4. Features

#### Dog Breed Classification

- Upload a dog image, and the system will classify the breed using a pre-trained machine learning model.
- Ensure that the model is loaded correctly from the `models` directory.

#### Dog Marketplace

- Browse and purchase dog-related products.
- Items are listed with details such as price, description, and availability.

#### Dog Training Videos

- Access a collection of training videos for dogs.
- Videos can be searched and filtered based on training topics.

#### Chatbot

- An interactive chatbot is available for user assistance.
- The chatbot can help with FAQs, guiding through different sections of the application.

#### Pet-Friendly Places

- Find nearby pet-friendly places.
- Information includes addresses, contact details, and user reviews.

#### Dog Walkers and Sitters

- List of available dog walkers and sitters.
- Users can book services and read reviews.

#### QR Code for Lost Dogs

- Generate a QR code linked to a dog’s profile.
- If the dog is lost, anyone who finds it can scan the QR code to get owner contact information.

#### Authentication and Database Management

- Users can register and log in to the system.
- User data is stored securely in a local database file (e.g., `users.db`).

### 5. Troubleshooting

- **Server not starting**: Check if all dependencies are installed and if the database file path is correct.
- **Database issues**: Ensure the local database file is accessible and correctly configured.
- **Feature not working**: Check the browser console and server logs for error messages.

### 6. Team Information

- **Team Member 1:**
  - **Name:** Sai Gowrav P
  - **Email:** 1jt20cs121@jyothyit.ac.in
  - **Phone:** 6362047166

- **Team Member 2:**
  - **Name:** Varun Kumar D
  - **Email:** 1jt20cs108@jyothyit.ac.in
  - **Phone:** 93808 16488

- **Team Member 3:**
  - **Name:** Varsha S
  - **Email:** 1jt20cs107@jyothyit.ac.in
  - **Phone:** 6383038583


- **Team Member 4:**
  - **Name:** Vishnu Prasad Pai
  - **Email:** 1jt20cs111@jyothyit.ac.in
  - **Phone:** 9916257177


### 7. Contact Information

For further assistance, please contact:

- **Name:** Sai Gowrav P
- **Email:** Gowravp47@gmail.com
- **Phone:** +91 6362047166
- **LinkedIn:** [www.linkedin.com/in/saigauravp](www.linkedin.com/in/saigauravp)
- **GitHub:** [https://github.com/Gauarvp](https://github.com/Gauarvp)

### `requirements.txt` File

Here is the content for `requirements.txt` file:

```
tensorflow==2.7.0
protobuf==3.20.*
numpy
pandas
scikit-learn
pillow
imutils
requests
time
opencv-python
pyzbar
os
generative-ai
secrets
flask
```

Ensure to save this content in a file named `requirements.txt` in your project directory. 
