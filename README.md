# Fruit Pantry Assistant

Welcome to the Fruit Pantry Assistant GitHub repository! This project is designed to help you organize your pantry or fruit bowl while providing you with delicious and healthy meal ideas based on the fruits you have available. The project includes a web application frontend and a backend powered by Flask, YOLOv8 for object detection, and various API calls for recipe suggestions.

Project Overview
The Fruit Pantry Assistant is a web application that combines computer vision technology, machine learning, and recipe APIs to create a user-friendly experience for users who want to make the most of their pantry or fruit bowl.

Features
Object Detection: The application utilizes the YOLOv8 model to detect fruits in the photos uploaded by users.
Fruit Review: Users can review and adjust the detected fruits' quantities before proceeding to recipe suggestions.
Recipe Suggestions: Based on the detected fruits, the application provides users with healthy meal ideas.
Web Interface: The web interface offers an intuitive way for users to interact with the application.
How to Use
Upload Photo: Start by uploading a photo of your pantry or fruit bowl using the provided form.
Review Detected Fruits: After uploading the photo, you can review the detected fruits and adjust their quantities if needed.
Get Recipe Ideas: Proceed to get delicious and healthy meal ideas based on the detected fruits.
Annotated Image: The application provides an annotated image highlighting the detected fruits for your reference.
Getting Started
To run the Fruit Pantry Assistant application locally, follow these steps:

Clone the repository to your local machine:

bash
Copy code
git clone https://github.com/your-username/fruit-pantry-assistant.git
cd fruit-pantry-assistant
Install the required dependencies using pip:

bash
Copy code
pip install flask ultralytics pillow
Run the Flask application:

bash
Copy code
python app.py
Open your web browser and go to http://localhost:5000 to access the application.

Technologies Used
Flask: The backend of the application is built using Flask, a Python web framework.
YOLOv8: YOLOv8 is used for object detection to identify fruits in the uploaded photos.
API Calls: The application communicates with recipe APIs to provide meal suggestions based on the detected fruits.
Contributors
Your Name (your.email@example.com)
Acknowledgments
The YOLOv8 model and related code are based on Ultralytics.
Recipe suggestions are obtained from [API Name/Provider].
License
This project is licensed under the MIT License.

We hope you enjoy using the Fruit Pantry Assistant to keep your pantry organized and discover exciting new meal ideas! If you have any questions, suggestions, or contributions, feel free to reach out to us. Happy organizing and happy eating!
