# Blood Cancer Cell Detection System

## Overview
This project aims to develop an automated blood cancer cell detection system using deep learning techniques. Leveraging the power of convolutional neural networks (CNNs) and EfficientNetB0, this model is trained to classify blood cancer cells with high accuracy. The system has achieved an impressive accuracy of **99.76%**, significantly surpassing the previous state-of-the-art of **94.76%**.

## Social Objective
Early detection of blood cancer, such as leukemia, can significantly improve the prognosis of patients. This model contributes to the medical field by providing a tool for doctors and healthcare professionals to more accurately and quickly detect cancerous cells in blood samples. By automating the detection process, the model aims to reduce human error, speed up diagnosis, and ultimately save lives.

## Importance of the Model
The model is essential because:
- **High Accuracy**: With a 99.76% accuracy rate, this model outperforms previous methods, offering more reliable results.
- **Early Detection**: Accurate and early detection of blood cancer can help doctors devise more effective treatment plans, potentially leading to better patient outcomes.
- **Scalability**: The system can be integrated into healthcare systems to aid clinicians worldwide, especially in regions with limited access to specialized diagnostic tools.

## Achievements & Future Goals
### Achievements:
- **Accuracy**: Achieved a test accuracy of 99.76%, a notable improvement over prior models (94.76%).
- **Model Deployment**: The model is deployed and accessible via a live web interface, making it easy for healthcare professionals to access and use the tool in real-time.
- ![Screenshot 2024-11-06 212747](https://github.com/user-attachments/assets/102d5526-2472-45b9-a81a-217c7b611961)

![Screenshot 2024-11-06 212755](https://github.com/user-attachments/assets/d7c262dc-2326-4f59-bd28-1e3dc35b575b)

### Future Objectives:
- **Integration with Healthcare Systems**: The goal is to integrate this model into hospital management systems to assist doctors in diagnosing patients in real-time.
- **Improving Robustness**: Enhance the model by training on a more diverse dataset to account for different types of blood cancers, further improving its generalization.
- **Expansion to Other Diseases**: The architecture of this model can be adapted for detecting other types of cancer or rare diseases in blood samples, potentially creating a broader diagnostic tool.
- **Real-time Analysis**: Develop a real-time version of the model that can process and analyze blood samples during patient visits for immediate results.

## How to Use
1. Visit the live web application: [Blood Cancer Cell Detection](https://hema-detect-website.vercel.app/)
2. Upload blood cell images to be analyzed.
3. The model will classify the cells and return the prediction (cancerous or non-cancerous) along with the confidence score.
4. ![Screenshot 2024-11-06 213203](https://github.com/user-attachments/assets/f414c3c7-4223-40ef-aa43-b34279595998)
5. ![Screenshot 2024-11-06 213234](https://github.com/user-attachments/assets/c4c11010-0c7e-4e22-b1a9-6a289814f2c0)
6. ![Screenshot 2024-11-06 213250](https://github.com/user-attachments/assets/0bc17330-9397-4065-8a94-a82d335cc255)



## Installation & Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/SUMIT2001GO/Blood-Cancer-Cell-Detection-System-Using-CNN-VGG16.git

### How to Add This to GitHub:
1. Open your repository on GitHub.
2. Click on the `Add file` dropdown and select `Create new file`.
3. Name the file `README.md`.
4. Paste the markdown content above into the file.
5. Commit the changes.

Once you commit, GitHub will automatically render this as a formatted page when you view it in the repository. Let me know if you need any changes!

## Acknowledgements

- **EfficientNetB0**: For providing an efficient and powerful architecture for image classification tasks.
- **Keras & TensorFlow**: For the deep learning framework used to train the model.
- **OpenCV & NumPy**: For image preprocessing and data manipulation.
- **Scikit-learn**: For providing the tools to evaluate model performance and generate classification reports and confusion matrices.
- **Matplotlib & Seaborn**: For visualizing the results, including confusion matrices and performance metrics.
- **Vercel**: For providing a platform to deploy and host the live web application.


