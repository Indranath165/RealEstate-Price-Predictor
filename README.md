<h1>Real Estate-Price-Predictor</h1>
This repository contains a real estate price predictor built using Python. The predictor utilizes machine learning algorithms to predict real estate prices based on various features. The project includes data cleaning, visualization, model building, and a web-based user interface. <br>
<img width="910" alt="realestate" src="https://github.com/Indranath165/RealEstate-Price-Predictor/assets/121590717/e6a693df-7c42-47c7-84ca-78153813956f">
<br>
<h2>Dataset</h2>
The dataset used for this project is sourced from Kaggle and can be found <a href="https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data" target="_blank">here</a>. It contains information about various properties in Bengaluru, including features such as location, size, total square feet, number of bedrooms, bathrooms, and more.
<h2>Technologies Used</h2>
The real estate price predictor is built using the following technologies:
<ul>
    <li>Python</li>
    <li>Numpy</li>
    <li>Pandas</li>
    <li>Matplotlib</li>
    <li>Scikit-learn</li>
    <li>Flask</li>
    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>
</ul>
<h2>Installation</h2>
To install and run the real estate price predictor, follow these steps:
<ol>
    <li>Clone or download this repository to your local machine.</li>
    <li>Navigate to the project directory: <code>cd RealEstate-Price-Predictor</code></li>
    <li>Install the required Python dependencies: <br> <code>pip install -r requirements.txt</code></li>
    <li>Install the Live Server extension for Visual Studio Code. This extension allows you to launch a local development server for the frontend:
    <ul>
        <li>Open Visual Studio Code</li>
        <li>Navigate to the Extensions view on the left sidebar</li>
        <li>Search for "Live Server"</li>
        <li>Click "Install" to install the extension</li>
    </ul></li>
    <li>Open the app.html file located in the client folder of the project using Visual Studio Code.</li>
    <li>Right-click anywhere in the app.html file and select "Open with Live Server" from the context menu. This will launch a local development server for the frontend.</li>
    <li>Start the Flask server by running the following command in the project directory: <br> <code>python app.py</code></li>
    <li>Open your web browser and access the application at <a href="http://127.0.0.1:5500/client/app.html" target="_blank">http://127.0.0.1:5500/client/app.html</a></li>
</ol>
Now you can interact with the real estate price predictor through the web interface.
<br><br>
Note: The backend server is served by running app.py, while the frontend is served using the Live Server extension in Visual Studio Code.
<h2>Usage</h2>
Upon accessing the web application, you will be presented with a user interface where you can enter property details, such as location, size, number of bedrooms, and bathrooms. Click the "Predict" button to get the estimated price for the property based on the trained model.
<h2>Contributions</h2>
Contributions to this project are welcome! If you find any bugs or want to enhance the functionality, please feel free to submit a pull request. Additionally, you can open an issue for any questions or suggestions you may have.
