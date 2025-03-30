# Image Guard AI

## About the Project
Image Guard AI is a Jupyter Notebook-based project that leverages machine learning and computer vision techniques to analyze and filter images. The primary goal of this project is to detect and flag inappropriate or unwanted content in images, as well as to distinguish between real images and AI-generated images, ensuring a safer and more controlled environment for image sharing and usage.

## Features
- **Image Analysis:** Utilizes advanced machine learning models to analyze the content of images.
- **Content Filtering:** Detects and flags inappropriate or unwanted content in images.
- **AI vs Real Image Detection:** Uses Vision Transformer (ViT) and PyTorch pipelines to differentiate between real images and AI-generated images.
- **Data Visualization:** Provides visualizations to help understand the analysis results.
- **Jupyter Notebooks:** Uses Jupyter Notebooks for interactive development and analysis.

## How It Works
1. **Data Capture:** The system captures image data from various sources.
2. **Image Analysis:** 
   - **Content Filtering:** Processes the images using machine learning models to detect inappropriate content.
   - **AI vs Real Detection:** Implements Vision Transformer (ViT) and PyTorch pipelines to analyze and classify images as real or AI-generated.
3. **Alert Generation:** Flags images that contain inappropriate content or are identified as AI-generated.
4. **Visualization:** Provides visual insights into the analysis and detection results.

## Installation
To set up the project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/DhanushSM/image_guard_ai.git
    ```
2. Navigate to the project directory:
    ```bash
    cd image_guard_ai
    ```
3. Create and activate a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
    ```
4. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
5. Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

## Usage
- Open the Jupyter Notebooks in the project directory to explore the image analysis and filtering workflows.
- Follow the steps in the notebooks to perform data cleaning, analysis, visualization, and model development.
- Modify the notebooks as needed to experiment with different data sets and models.

## Contributing
Contributions are welcome! To contribute to this project, follow these steps:

1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature-name
    ```
3. Make your changes and commit them:
    ```bash
    git commit -m 'Add some feature'
    ```
4. Push to the branch:
    ```bash
    git push origin feature-name
    ```
5. Open a pull request to the `main` branch.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Contact Information
- **Repository Owner:** [DhanushSM](https://github.com/DhanushSM)
- **Email:** [your-email@example.com]
