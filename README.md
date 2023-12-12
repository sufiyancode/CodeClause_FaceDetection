# Face Recognition Project

Welcome to our Face Recognition project! This initiative enables you to identify faces in images using the Face-API.js library. This application, developed with HTML, CSS, and JavaScript, offers a user-friendly interface for detecting faces in uploaded images.

This project is a part of the Code Clause Internship Program.

**Important:** Please wait momentarily as all the models load. Once loaded, grant your browser access to your camera, and the website will promptly begin detecting your face along with your facial expressions.

## How to Utilize

To make the most of the Face Recognition project, adhere to these steps:

1. **Clone the Repository:** Begin by cloning this repository to your local machine. Execute the following command in your terminal:

   ```bash
   git clone https://github.com/your-username/face-recognition.git
   ```

2. **Acquire Face-API.js Library:** This project relies on the Face-API.js library for face detection. Refer to the [Face-API.js Documentation](https://github.com/justadudewhohacks/face-api.js) for library details and download it.

3. **Integrate Face-API.js Library:** After downloading the Face-API.js library, place the `face-api.min.js` file in the project's `js` folder. In the `index.html` file, ensure the library script is included before the `script.js` file:

   ```html
   <script src="js/face-api.min.js"></script>
   <script src="js/script.js"></script>
   ```

4. **Initiate a Live Server:** To interact with the application, run the project using a live server. If you don't have Node.js installed, use the following command to install the `live-server` package globally:

   ```bash
   npm install -g live-server
   ```

5. **Launch the Application:** Navigate to the project directory in your terminal and execute the following command:

   ```bash
   live-server
   ```

   Access the application at `http://127.0.0.1:8080/index.html` in your web browser.

6. **Face Detection:** Once the application is open, upload an image from your local machine using the "Choose File" button. After selecting the image, click on "Detect Faces." The Face-API.js library will analyze the image and outline detected faces with bounding boxes.

7. **Additional Features:** Customize the application based on your project's needs by incorporating more features from the Face-API.js library, such as facial landmark detection, age and gender prediction, emotion detection, etc. Explore the library documentation for insights.

## Contribution Guidelines

If you wish to contribute to this project, open an issue or submit a pull request on our GitHub repository. We value your feedback and contributions!

---

Thank you for using our Face Recognition project! For questions or assistance, feel free to reach out through our GitHub repository or email. Enjoy exploring the world of face recognition!
