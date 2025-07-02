🚗 OCR for Car License Plates using EasyOCR & Traditional CV

This project aims to detect and extract text from car license plates using a hybrid approach combining traditional computer vision techniques and EasyOCR.


✅ Project Overview:

📷 Input: Image of a car showing the license plate

🧠 Goal: Detect the license plate area, preprocess it, and extract the text using OCR

🧪 Techniques Used:

Grayscale conversion

Thresholding

Contour detection

Cropping the license plate region

EasyOCR for text recognition




🔧 Tools & Technologies:

Python

OpenCV (for image processing)

EasyOCR (for text recognition)

Matplotlib (for visualization)



📌 Project Steps:

1. Load and preprocess the image

Resize if needed

Convert to grayscale



2. Apply thresholding

To enhance the contrast between text and background



3. Detect contours

To localize the license plate region



4. Crop the license plate area

Based on bounding boxes



5. Apply EasyOCR

To extract text from the cropped image



🧾 Sample Output:

Input Image → Processed → Plate Cropped → Extracted Text:
"XYZ 1234" ✅



🌍 Use Cases:

Automated vehicle identification

Parking systems

Traffic enforcement cameras

Toll gates

