# IDenSure

A proof-of-concept system that verifies a user's identity and age using a simulated Aadhar card and a live selfie.

## 🔍 FEATURES
- OCR-based extraction of Date of Birth (DOB) from a fake Aadhar image.
- Face matching between the ID card photo and a live selfie.
- Age validation to check if the user is 18+.
- Confidence score shown for face match.
- Flask-based backend with a simple HTML frontend.

## PROCEDURE TO WORK 

Step 1: **Upload Your Aadhaar Card**
-Navigate to the web app in your browser.
-Click on the Upload Aadhaar Card button.
-Select a mock Aadhaar card image (e.g., sample_aadhaar.png) from your system.

![image](https://github.com/user-attachments/assets/b07a45c5-2843-4a9d-9463-b9a063bd4730)

Step 2: **Upload Your Selfie**
-After the Aadhaar card upload is successful it will automatically move to upload your selfie.
-Intially a prompt will be shown, sharing guidlines to make your results better.
-Take a live selfie or upload an image that resembles the ID photo.

 ![image](https://github.com/user-attachments/assets/fbfae9cb-a577-4eea-8287-99c9f680df48)


Step 3: Verify Identity
-Click the 'Verify Identity' button to process your inputs.
-The system will:
   -Extract the Date of Birth from the Aadhaar card using OCR.
   -Compare the selfie with the Aadhaar card photo using face recognition.
   
![image](https://github.com/user-attachments/assets/4a8e71c0-d061-48cb-ae99-3d77d314d2c9)

Step 4: **View Results**
-The results will display:
   -Age Verification: Confirms if the user meets the required age limit (e.g., 18+).
   -Identity Match: Indicates whether the selfie matches the Aadhaar card photo.
   
![image](https://github.com/user-attachments/assets/885317b4-ecbb-4e68-9321-12d0aff4a677)

## DEMO VIDEO
https://drive.google.com/file/d/1QnqkJRJaPTZNumamZi9QOPaqfx74KkuH/view?usp=sharing

## SCOPE OF IMPROVEMENT
->**Results Visualization**
Display results with more clarity, such as using graphical indicators (e.g., graphs for accuracy, confidence and overall efficiency).

->**Multilingual Support**
Consider providing options for multiple languages in the UI.

->**Integration into a Larger Ecosystem**
The Identity Guard Check can help Zynga by enabling secure age verification, identity validation, and fraud prevention, fostering safer gaming environments and regulatory compliance.

## PPT(To give you more insights)
https://drive.google.com/file/d/179iRbqa_AbL2RvdR5AEsFTvbK-zv8mpM/view?usp=sharing

NOTE: Presently it is not hosted. 
