# HomeWise 

# 1. Introduction 
Project Report: Boston House Price Predictor - The Boston House Price Prediction Application is a web-based tool designed to predict housing prices in Boston 
using machine learning techniques.  -  It utilizes Flask, HTML, CSS, Python, and Docker to create a robust and scalable application. 
# 2. Technologies Used 
- Flask: A lightweight web framework in Python used for building the backend API and serving web pages. - HTML: Markup language for creating the structure and content of the web pages. - CSS: Styling language for designing the appearance and layout of the web pages. - Python: Programming language used for the machine learning model development and integration with Flask. - Linear Regression: Machine learning model employed for predicting house prices based on various features. - Docker: Containerization platform used to package the application and its dependencies into a standardized unit 
for deployment. 
# 3. Project Structure 
- app.py: Flask application file containing routes and logic for handling HTTP requests and rendering templates. - templates/: Directory containing HTML templates for rendering web pages. - requirements.txt: File listing Python dependencies required for the application. - Dockerfile: Configuration file for building the Docker image of the application. - regmodel.pkl: The Regression model trained on Boston Housing Dataset -scaling.pkl: It is used for scaling or standardizing input data before making predictions.  
# 4. Application Workflow 
- User Interface: The front-end interface is designed using HTML and CSS, providing a form where users can input 
various features related to a Boston house. - Backend: Flask handles the form submission, processes the input data, and makes predictions using a pre-trained 
linear regression model. - Prediction: Upon form submission, Flask retrieves the input data, passes it to the machine learning model, 
computes the predicted house price, and displays it back to the user. - Dockerization: The entire application is containerized using Docker, ensuring portability and ease of deployment 
across different environments. 
# 5. Deployment and Usage 
- Building the Docker Image: The Docker image is built using the provided Dockerfile. This encapsulates the 
application and its dependencies into a self-contained unit. - Running the Docker Container: The Docker container is run locally or deployed to a server, exposing the Flask 
application on port 5000. - Accessing the Application: Users can access the application through a web browser by navigating to 
`http://localhost:5000`. The interface allows them to input house features and receive predicted prices. 
# 6. Conclusion 
- The Boston House Price Prediction Application demonstrates the integration of Flask, HTML, CSS, Python, and 
Docker to create a functional machine learning-driven web application. 
# 7. Future scope 
- Future enhancements could include improving the user interface, incorporating additional machine learning 
models for comparison, and scaling the application for larger datasets or multiple users concurrently. 
# 8. Contact Information 
- For inquiries or further information, please contact dd2242003@gmail.com. --- 
