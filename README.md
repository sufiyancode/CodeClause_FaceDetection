
# Face Detector Project

Welcome to the Face Detector project! This project allows you to detect faces in images using the Face-API.js library. The application is built using HTML, CSS, and JavaScript, and it provides an easy-to-use interface to detect faces in the uploaded images.

This project is a part of Code Clause Internship

**Note:** Please wait a while after all the models get loaded, then allow the browser to access your camera just in a while the website will start to detect your face as well as your facial expressions...

## How to Use

To use the Face Detector project, follow these steps:

1. **Clone the Repository:** First, clone this repository to your local machine using the following command:

   ```bash
   git clone https://github.com/your-username/face-detector.git
   ```

2. **Obtain Face-API.js Library:** The Face Detector project uses the Face-API.js library to detect faces in images. You can find the documentation and download the library from the following link: [Face-API.js Documentation](https://github.com/justadudewhohacks/face-api.js)

3. **Include Face-API.js Library:** After downloading the Face-API.js library, place the `face-api.min.js` file in the project's `js` folder. In the `index.html` file, make sure to include the library script before the `script.js` file as shown below:

   ```html
   <script src="js/face-api.min.js"></script>
   <script src="js/script.js"></script>
   ```

4. **Start a Live Server:** To interact with the application, you need to run the project using a live server. If you have Node.js installed, you can use the popular `live-server` package. If you don't have it, you can install it globally using:

   ```bash
   npm install -g live-server
   ```

5. **Launch the Application:** After installing `live-server`, navigate to the project directory in your terminal and run the following command:

   ```bash
   live-server
   ```

   The application should now be accessible at `http://127.0.0.1:8080/index.html`. Open this link in your web browser.

6. **Detecting Faces:** Once the application is open in your web browser, you can upload an image from your local machine using the "Choose File" button. After selecting the image, click on the "Detect Faces" button. The application will use the Face-API.js library to analyze the image and draw bounding boxes around detected faces.

7. **Additional Features:** Depending on your project's requirements, you can further enhance the application by adding more features using the capabilities of the Face-API.js library, such as facial landmark detection, age and gender prediction, emotion detection, and more. Refer to the library documentation for details.

## Contributing

If you'd like to contribute to this project, feel free to open an issue or submit a pull request on the GitHub repository. Your feedback and contributions are highly appreciated!

---

Thank you for using the Face Detector project! If you have any questions or need assistance, feel free to reach out to us through our GitHub repository or email. Happy face detecting!

Created by Swikrit Shukla - All rights reserved.
