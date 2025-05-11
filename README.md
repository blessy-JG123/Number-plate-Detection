Number Plate Detection using EasyOCR and OpenCV

This project detects Indian vehicle number plates from images using OpenCV and EasyOCR in Google Colab. 
It uses a pre-trained Haar Cascade classifier to locate license plates and then extracts text using EasyOCR.
Technologies Used
- Python
- OpenCV
- EasyOCR
- Google Colab
Dataset
The dataset contains sample images of Indian vehicle number plates. 
Store the images in your Google Drive under the following path:
/MyDrive/Indian_Number_Plates/Sample_Images
How to Run the Project
1. Mount your Google Drive in Google Colab:
   from google.colab import drive  
   drive.mount('/content/drive')
2. Load and analyze number plate images:
   detected_texts = analyze_dataset(dataset_path)
3. The program will display:
   - Each processed image with detected plate highlighted
   - Recognized number plate text below each image
Example Output
- Displays the input image with a green rectangle around the number plate.
- Prints the OCR-detected text beside each image.

Dependencies

Install EasyOCR in Colab using:

   !pip install easyocr

Author

- GitHub: [blessy-JG123](https://github.com/blessy-JG123)
