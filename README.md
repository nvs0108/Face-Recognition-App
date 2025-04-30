# Face Recognition App

This is an Android application that leverages face recognition technology to detect and recognize faces in images. The app uses a custom SDK for face recognition and provides an intuitive user interface to demonstrate its capabilities.

## Features
- Real-time face detection
- Face recognition from images or videos
- Option to save recognized faces in a database
- User-friendly Android interface for interaction with the app

## Prerequisites
Before running the app, make sure you have the following installed:
- Android Studio (latest version)
- JDK 8 or later
- Gradle (for building the project)

## Installation
1. Clone the repository:  
   `git clone https://github.com/nvs0108/Face-Recognition-App.git`
2. Navigate to the project directory:  
   `cd Face-Recognition-App`
3. Open the project in Android Studio:  
   - Open Android Studio, select **File** > **Open** and choose the project directory.
4. Sync the project with Gradle:  
   - Android Studio should automatically prompt you to sync the project with Gradle. If not, go to **File** > **Sync Project with Gradle Files**.
5. Run the application:  
   - Connect your Android device or use an emulator.  
   - Click the **Run** button in Android Studio or select **Run** > **Run 'app'**.

## Usage
Once the app is running on your Android device, follow these steps:
1. Launch the app, and you will be directed to the main screen.
2. You can either take a photo or select an existing image from your gallery.
3. The app will process the image and detect faces, displaying the results.
4. Recognized faces will be shown, and you will have the option to save them for further recognition.

## Structure
- **`app/`**: Contains the main Android application code.
- **`libfacesdk/`**: The custom SDK for face recognition functionalities.
- **`gradle/`**: Contains Gradle wrapper files for building the project.

## Dependencies
- **OpenCV**: Used for image processing (if applicable).
- **TensorFlow** or other ML libraries for face recognition (if applicable).

## Contributing
Contributions are welcome! Please follow these steps if you would like to contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to your forked repository (`git push origin feature-branch`).
5. Submit a pull request for review.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Thanks to the creators of the face recognition libraries used in this project.
- Special thanks to [OpenCV](https://opencv.org/) for image processing and [TensorFlow](https://www.tensorflow.org/) for machine learning support (if used).
