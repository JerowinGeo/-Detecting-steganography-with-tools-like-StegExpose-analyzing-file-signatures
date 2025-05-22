# Detecting-steganography-with-tools-like-StegExpose-analyzing-file-signatures
## AIM:
To detect hidden data using steganography detection tools like StegExpose and analyze file signatures for authenticity and manipulation.

## DESIGN STEPS:

### Step 1:
Install StegExpose or use the JAR version to detect steganography in image files.

### Step 2:
Run StegExpose on a directory of suspected image files using the command:

### Step 3:
Analyze file signatures using tools like file, binwalk, or xxd to check for inconsistencies or embedded content.

## PROGRAM:
StegExpose and File Signature Analysis Commands
Step 1: Download Image and Create Secret Message File
• Download a .jpeg image from a trusted website or use own image

![image](https://github.com/user-attachments/assets/f8695d8e-559e-4a78-afe5-0a98d004f59d)

• Create a text file named secret with a confidential message:

![image](https://github.com/user-attachments/assets/6ae62f9c-ee46-4402-88b1-736e40d2c077)

Step 2: Install and Verify Steghide Tool
• To install Steghide on Kali linux,run:

• Confirm the installation by checking its version:

![image](https://github.com/user-attachments/assets/6c50ab2a-f0a3-4983-9216-67da855238ac)

Step 3: Embed the Secret Message into the Image
• Use the following command to embed secret into jaimurughan.jpeg:

![image](https://github.com/user-attachments/assets/01b1e52f-949f-4de2-ac44-5fd293de1e3f)

Step 4: Delete the Original Secret File
• After embedding, delete the plaintext file:

![image](https://github.com/user-attachments/assets/9923dbde-e820-41f4-8820-ca48c1fb4fee)

OUTPUT:
List of Images with Steganography Detection Scores and File Signature Details

Step 1: Extract the Embedded Secret from the Image

![image](https://github.com/user-attachments/assets/3fa0dcc9-9a27-43a3-a17c-8ee54ca4df38)

• To retrieve the hidden file: • Enter the same passphrase used during embedding.


Step 2: Verify the Extracted Message
• Display the extracted file content to verify:

• Ensure the message matches the original secret content.

• Another command to see the same secret message is

Step 3: Retrieve Information About the Embedded Data

![image](https://github.com/user-attachments/assets/c9ffbf93-218e-4226-b928-78f4f5f2d48f)

• This will display file type, size, and whether data is embedded.









## OUTPUT:
List of Images with Steganography Detection Scores and File Signature Details

## RESULT:
Hidden data was successfully detected and file signatures were analyzed for irregularities.
