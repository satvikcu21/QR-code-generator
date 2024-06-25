# QR-code-generator
**Project Report: QR Code Generation**

**Objective**

   The objective of this project is to create a simple web application that generates a QR code based on user input (text or URL). The generated QR code can be used for various purposes such as sharing links or 
   text information easily.

**Functionality Overview**

The application includes:
1.An input field where users can enter text or a URL.
2.A button to trigger the QR code generation.
3.An area to display the generated QR code.

**Implementation Details**

1.**HTML Structure:**
   A container holding a text input, a button, and an image element to display the QR code.
   The HTML is structured to be simple and clear, making it easy to use.
   
2.**CSS (style.css):**
  Basic styling for the container, input, button, and image.
  An optional .show-img class to control the display of the QR code image.
  An optional .error class to indicate when the input is invalid.
  
3.**JavaScript Functionality:**
   Elements: References to the input, button, and image elements are obtained using getElementById.
   Function: The generateQR function:
   Checks if the input field is not empty.
   Constructs a URL to generate the QR code using an external API (api.qrserver.com).
   Updates the src attribute of the image element to display the generated QR code.
   Adds a class to show the image or highlight the input field if empty.

**Previews**

![Screenshot 2024-06-25 190109](https://github.com/satvikcu21/Form-validation/assets/150938638/a1d86981-f6b0-4f7e-907f-a60b48475a3b)

![Screenshot 2024-06-25 190136](https://github.com/satvikcu21/Form-validation/assets/150938638/2baac570-bb89-42e3-a633-652e0fb7ff78)
