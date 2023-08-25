# DigitGlyph: Bridging Art and Technology for Handwritten Digit Recognition

DigitGlyph is an innovative web application that brings together the world of artistic expression and cutting-edge technology. By leveraging the power of Convolutional Neural Networks (CNNs), DigitGlyph enables the recognition and classification of handwritten digits, creating a dynamic fusion between human creativity and machine intelligence.


Access the Web App here : [DigitGlyph](https://gokul-raja84.github.io/DigitGlyph/)

### Project Overview:


At the core of DigitGlyph lies a 17-layer CNN model, meticulously designed for recognizing and classifying handwritten digits. Trained on the venerable MNIST dataset, consisting of 70,000 grayscale images, the model transforms pixelated strokes into meaningful digital interpretations. With a carefully crafted combination of Conv2D, MaxPooling2D, BatchNormalization, Dense, Flatten, and Dropout layers, the model achieves an impressive accuracy of 99.15% after 30 epochs of training. The input layer, housing 32 neurons, feeds into an output layer with 10 neurons, corresponding to the 10 distinct digit classes.
- The model achieves an accuracy of 99.15%, showcasing its strong ability to accurately recognize and classify handwritten digits.It highlights the successful implementation of DigitGlyph, operating as a robust and potent tool for precise digit recognition.

### The Artistic Fusion:

DigitGlyph isn't just about numbers; it's about the expression, intricacy, and uniqueness behind each handwritten stroke. The project recognizes that digit recognition is not merely a technical challenge but a creative endeavor. By deploying TensorFlow.js, the model's efficacy is seamlessly integrated into a web application, allowing users to witness their handwritten digits being accurately classified. It transforms the abstract notion of machine learning into an artistic experience, as users see their handcrafted symbols come to life through the lens of technology.

### User InterFace:

- DigitGlyph's User InterFace 

![glyph 1](https://github.com/Gokul-Raja84/DigitGlyph/assets/106546785/9c09bc9e-3725-47ef-a7b6-5ee10b5433a6)



- DigitGlyph's digit recognition

![glyph 2](https://github.com/Gokul-Raja84/DigitGlyph/assets/106546785/106711e4-1968-405e-993c-671361f20f0c)




### Deployment and Interaction:

The final model is encapsulated into JSON and weight (.h5) files using TensorFlow.js converters. In the dynamic area of web development, HTML, CSS, and JavaScript collectively constructs an interactive user interface, providing a canvas where users can craft their handwritten digits. TensorFlow.js seamlessly loads the model, allowing users to witness the application's real-time predictions. The deployment culminates with the hosting of the web application on GitHub Pages, making DigitGlyph accessible to a global audience.

**For Deployment:**
- Save your trained model using TensorFlow.js converters: Create a JSON file to capture the model architecture and a .h5 file to store the model weights.
- Utilize TensorFlow.js in your JavaScript code: Integrate TensorFlow.js into your web application to leverage the power of your trained model directly in the browser.
- Load the model: Use TensorFlow.js to load the saved model, making it accessible for predictions in your JavaScript environment.
- Make predictions: With the model loaded, you can perform predictions on new data, enabling real-time insights and interactions.
- Deploy and share: By deploying your TensorFlow.js-powered application, you can provide users with an engaging experience and showcase the capabilities of your machine learning model in a user-friendly way.

### Conclusion

DigitGlyph isn't just a tool for recognizing digits; it's fusion between creative expression and technological innovation. By transforming handwritten strokes into meaningful classifications, DigitGlyph transcends traditional boundaries and showcases the potential of harmonizing art and technology. Join us on this captivating journey at [DigitGlyph Web App](https://gokul-raja84.github.io/DigitGlyph/) and experience the magic firsthand.


### Connect with Us

For feedback, suggestions, or collaborations, feel free to connect with us on [GitHub](https://github.com/Gokul-Raja84) or [Contact Me](mailto:gokulraja840@gmail.com). Let's explore the realms of art and technology together!


### Acknowledgements

Feel Free to Explore and Experiment: I encourage you to delve into the codebase, tinker with various architectures and hyperparameters, and contribute to enhancing the model's accuracy and performance. Your insights and innovations can play a crucial role in advancing this project !

