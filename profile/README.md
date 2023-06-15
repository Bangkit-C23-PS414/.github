<div align="center">
	<img src="https://raw.githubusercontent.com/Bangkit-C23-PS414/.github/main/profile/ic_launcher-playstore.webp" width="192" />
	<h3 align="center">Recoffeery</h3>
	<p align="center">
		Recoffeery is an Android application that utilizes artificial intelligence and the device's camera to detect and identify coffee leaf disease. It provides a convenient way for coffee farmers and enthusiasts to quickly analyze and diagnose the health of coffee plants by capturing leaf images.
		<br />
		<a href="#how-to-use-the-app-"><strong>How to Use The App »</strong></a>
	</p>
</div>

## Screenshots
<div>
	<img src="https://raw.githubusercontent.com/Bangkit-C23-PS414/.github/main/profile/screenshots/screen-1.webp" width="200" />
	<img src="https://raw.githubusercontent.com/Bangkit-C23-PS414/.github/main/profile/screenshots/screen-2.webp" width="200" />
	<img src="https://raw.githubusercontent.com/Bangkit-C23-PS414/.github/main/profile/screenshots/screen-3.webp" width="200" />
	<img src="https://raw.githubusercontent.com/Bangkit-C23-PS414/.github/main/profile/screenshots/screen-4.webp" width="200" />
</div>

## Introduction 👋
**Team ID: C23-PS414**

Hi everyone! We are from C23-PS414. We consist of 6 people and these are my team members:

|Name|Bangkit ID|Learning Path|LinkedIn
|--|--|--|--
|Saddam Sinatrya Jalu Mukti|A282DSX1070|Mobile Development|[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/saddam-azy/)|
|Alfatih Aditya Susanto|A181DSX2732|Mobile Development|[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alfatihaditya/)|
|Dimas Ichsanul Arifin|M181DSX1804|Machine Learning|[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dimasichsanul/)|
|Ramdhan Firdaus Amelia|M181DSX0308|Machine Learning|[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ramdhan-firdaus-amelia/)|
|Arizki Putra Rahman|C168DKX3967|Cloud Computing|[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/arizkinewbie/)|
|Muhammad Syukur Abadi|C282DSX0729|Cloud Computing|[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/muhammadsyukura/)|

**Our Team Advisors**
|Name|Advisor ID|Learning Path|LinkedIn
|--|--|--|--
|Sayed Khaidir Ali|B23-A113|Tech - Cloud and Back End|[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sayed-khaidir-ali/)|
|Hidayaturrahman|B23-A088|Tech - Machine Learning|[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hidayaturrahman/)|

## Theme 🌾
Food Accessibility, Agribusiness, and Food Security

## How To Use The App 📱
### A. Getting Started
#### Prerequisites
Android phone and internet connection
#### Installation
Download and Install the [APK](https://drive.google.com/drive/folders/1V2XKaV4dnu7JnO4IOUGGxhCyfIQq9lMY?usp=sharing)
#### Register
Open the app and click register then fill the form

### B. Usage
#### How to detect plant disease
1. Open the app
2. Sign In to your account or Sign Up if you don't have an account
3. Click **Detect Now** button at home screen
4. Point the camera into the leaf part of the plant for a better result
5. Click capture and upload
6. Wait for the result

## Features
- **Leaf Health Assessment**: The app uses AI algorithms to detect and analyze coffee leaves from images captured by the device's camera. Based on the captured image, the app provides an assessment of the health condition of the coffee leaf.
- **Image Capture and Gallery**: Users can capture leaf images using the app's built-in camera functionality. Additionally, the app allows users to browse and select images from their device's gallery for analysis.
- **Results and Recommendations**: The app presents the analysis results and provides recommendations to the user regarding potential remedies or actions to take for maintaining or improving the health of the coffee plants.
- **Detection History**: Users can view their detection history, including the date and results of previous leaf detections. The history can be filtered based on different criteria.

## Architecture
The Coffee Leaf Detection App follows a client-server architecture. The client-side, implemented on Android, handles the user interface, image capturing, and displays the results. The server-side consists of the AI algorithms responsible for leaf detection and analysis.
The communication between the client and server occurs via RESTful APIs. The client sends leaf images to the server for processing, and the server returns the analysis results. The app utilizes machine learning models trained on a dataset of coffee leaf images to achieve accurate leaf detection and health assessment.

## Libraries Used
### Android
- **Jetpack Compose**: Jetpack Compose is a modern UI toolkit for building native Android user interfaces. It provides a declarative approach to UI development, making it easier to build dynamic and interactive user interfaces.
- **CameraX**: CameraX is an Android Jetpack library that provides a simple and consistent API for accessing camera functionality across different Android devices.
- **Coil**: Coil is an image loading library for Android that provides easy-to-use APIs for loading and displaying images efficiently.
- **DataStore**: DataStore is a data storage solution from the Jetpack libraries that offers a modern, reactive, and easy-to-use approach for persisting data in Android applications.
- **Room**: Room is an Android Jetpack library that provides an abstraction layer over SQLite, making it easier to work with a SQLite database in an Android app.
- **Retrofit**: Retrofit is a widely-used HTTP client library for Android that simplifies the process of making RESTful API requests to the server.
- **Paging 3**: Paging 3 is a Jetpack library that helps in loading and displaying large datasets from a data source incrementally, improving app performance and user experience.
- **Dagger Hilt**: Dagger Hilt is a dependency injection library for Android that simplifies the management of dependencies in an application.

### Machine Learning
- **TensorFlow**: TensorFlow is an open-source machine learning framework used for training and deploying deep learning models. It provides a rich ecosystem of tools and libraries for building and deploying machine learning applications.
- **Keras**: Keras is a high-level neural networks API written in Python. It provides a user-friendly interface for building and training deep learning models on top of TensorFlow.
- **NumPy**: NumPy is a Python library for scientific computing. It provides powerful array and matrix operations, making it essential for numerical computations in machine learning.
- **PIL (Python Imaging Library)**: PIL is a library for opening, manipulating, and saving many different image file formats in Python. It is commonly used for image preprocessing and augmentation in machine learning pipelines.

### Cloud Computing/Backend
- **Cloud Run**: Cloud Run is a serverless compute platform provided by Google Cloud. It allows you to run stateless containers in a fully managed environment, providing scalability and ease of deployment.
- **Firestore**: Firestore is a flexible, scalable, and fully managed NoSQL document database provided by Google Cloud. It enables real-time synchronization and offline support for data storage.
- **Cloud Storage**: Cloud Storage is a scalable and secure object storage service provided by Google Cloud. It allows you to store and retrieve large amounts of data, including images and other files.
- **App Engine**: App Engine is a fully managed serverless platform provided by Google Cloud. It enables you to build and deploy applications without managing infrastructure, providing auto-scaling and high availability.
- **Cloud Functions**: Cloud Functions is a serverless compute platform provided by Google Cloud. It allows you to write and deploy lightweight, event-driven functions that respond to cloud events and execute custom logic.
- **GoLang**: GoLang is a programming language developed by Google. It is known for its simplicity, efficiency, and strong support for concurrent programming.
- **Node.js**: Node.js is a JavaScript runtime built on Chrome's V8 JavaScript engine. It allows you to build scalable and fast network applications, making it a popular choice for backend development.

Note: This list includes some of the major libraries used in the Recofferry App. It may not include all the libraries and dependencies used in the project.
