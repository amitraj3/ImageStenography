Image Steganography - EmbedMessage


This Java code provides a basic implementation of image steganography, allowing you to embed a secret message into an image. The embedded message is imperceptible to the human eye, and the resulting image can be saved as a new file.

----------------------//How to Use//----------------------------------

Open Image: Click the "Open" button to select an image file (supported formats: jpg, jpeg, png, gif, tiff, bmp, dib). The selected image will be displayed in the "Original Image" section.

Enter Message: Enter the secret message you want to embed into the image in the "Message to be embedded" text area.

Embed Message: Click the "Encrypt" button to embed the message into the image. The modified image will be displayed in the "Steganographed Image" section.

Save Image: Click the "Save into new file" button to save the steganographed image as a new file (supported formats: png, bmp). Choose a location and provide a file name for the saved image.

Reset: Click the "Reset" button to clear the message and start over with a new image.

Dependencies

This code uses the following dependencies:

Java AWT (Abstract Window Toolkit) for the graphical user interface.
Java Swing for the buttons, text area, and scroll panes.
Java ImageIO for reading and writing images.
Running the Code
To run this code, make sure you have Java Development Kit (JDK) installed on your system. Compile and run the EmbedMessage.java file using the Java compiler and runtime environment.

---------------------------------------Limitations:------------------------------------

The maximum message length that can be embedded depends on the size of the selected image. If the message is too long for the image, an error message will be displayed.
This code currently supports embedding messages into images in a graphical user interface (GUI) environment only. It does not provide a separate method for programmatically embedding messages.
License
This code is released under the MIT License.

Contact Information
For any questions or suggestions, please feel free to reach out to the author:

Name: [Amit Raj]
Email: [amitraj63k@gmail.com]
GitHub: [amitraj63]