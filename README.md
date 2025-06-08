# Image Alternate text Web Application with PyTorch and ViT-GPT2

This project demonstrates a web application for generating alternate text for images using the Vision Transformer (ViT) model combined with GPT-2. Users can upload an image, and the model will generate a descriptive alternate text for the image.

## Features

- Upload an image to generate a alternate text.
- Uses Vision Transformer (ViT) and GPT-2 for image alternate text.
- Supports both CPU and GPU (CUDA) for model inference.

## Prerequisites

- Python 3.x
- Flask
- PyTorch
- Transformers
- Pillow

## Installation

Clone the repository:

\`\`\`bash
git clone https://github.com/your-username/image-alternate text-web-app.git
cd image-alternate text-web-app
\`\`\`

Install the required Python packages:

\`\`\`bash
pip install -r requirements.txt
\`\`\`

## Usage

1. Run the Flask web application:

\`\`\`bash
python app.py
\`\`\`

2. Open your web browser and go to `http://127.0.0.1:5000/`.
3. Upload an image and click on "Predict".
4. The generated alternate text will be displayed on the result page.

## Deployment

For deployment, you can use platforms like Heroku, AWS, or Azure. Make sure to update the host and port settings in `app.run()` for production deployment.

## Directory Structure

\`\`\`
image-alternate text-web-app/
├── app.py
├── templates/
│   ├── index.html
│   └── result.html
├── requirements.txt
└── README.md
\`\`\`

- `app.py`: Main Flask application file containing the web server and model inference logic.
- `templates/`: Folder containing HTML templates for the web application.
- `requirements.txt`: File containing the required Python packages.

## License

This project is licensed under the MIT License. See `LICENSE` for more details.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Acknowledgments

- Thanks to Hugging Face for providing pre-trained ViT-GPT2 model.
- Inspired by [Transformers by Hugging Face](https://github.com/huggingface/transformers).
- ![image](https://github.com/r-krishnapriya/imagecaptioning/assets/141714730/6407be44-6d4e-46bf-a458-fe9bd5321592)
- ![image](https://github.com/r-krishnapriya/imagecaptioning/assets/141714730/5349bf5c-e797-4010-b28b-2e25ecc0f777)


