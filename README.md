# Background Remover

## Overview

Background Remover is a simple web application that allows users to remove the background from images. It uses Flask for the backend and HTML/CSS/JavaScript for the frontend. The application processes images uploaded by the user and returns the processed image with the background removed.

## Features

- Drag and drop file upload functionality.
- Automatic form submission upon file selection or drop.
- Processes images to remove the background.
- Returns the processed image as a download.

## Setup

### Prerequisites

- Python 3.6 or higher
- Flask
- Pillow (PIL)
- rembg

### Installation

1. Clone the repository:

   ```
   git clone https://github.com/0xcharanmadhu/background-remover-python.git
   cd background-remover-python
   ```

2. Install the required Python packages:

   ```
   pip install Flask Pillow rembg
   ```

3. Run the Flask application:

   ```
   python app.py
   ```

4. Open your web browser and navigate to `http://localhost:5100` to use the application.

## Usage

1. Click on the drop zone or use the file input to select an image.
2. The application will automatically process the image and remove the background.
3. The processed image will be downloaded automatically.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue if you find any bugs or have suggestions for improvements.

## License

This project is licensed under the MIT License. See the [MIT](https://mit-license.org/) file for details.

## Contact

If you have any questions or need further assistance, please open an issue on GitHub.
