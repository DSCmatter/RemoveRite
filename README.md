# RemoveBG

**RemoveBG** is a simple web application that removes the background from any image file. It uses Flask as the web framework, rembg for background removal, and Pillow for image processing. The app is containerized using Docker for easy deployment.

## Features

- **Upload Image**: Upload an image file from your device.
- **Background Removal**: Automatically removes the background from the uploaded image.
- **Download Image**: Download the processed image with the background removed.

## Requirements

- Python 3.8+ or current version
- Flask
- rembg [Source](https://github.com/danielgatis/rembg)
- Pillow
- Docker (for containerization)

## Installation

### Clone the Repository

```
git clone https://github.com/yourusername/removebg.git
cd removebg
```

## Install required packages

```
pip install -r requirements.txt
```

## Run the Application
``` python app.py ``` 

The application will be accessible at http://127.0.0.1:5000/.

Using Docker
Build the Docker Image
To containerize the application using Docker, use the following command:

Copy code
```docker build -t removebg ```
Run the Docker Container

Copy code
```docker run -d -p 5000:5000 removebg ```

The application will be accessible at http://localhost:5000/.

### Usage
- Navigate to the homepage.
- Upload an image by clicking the "Choose File" button.
- Click "Remove Background" to process the image.
- Download the image with the background removed.

### Note: Using Docker is not required to use the app.
