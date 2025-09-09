# Medicinal_Plants_Detection_By_Using_Deep_Learning_Model

Description of the project - 

Designed and implemented an AI-driven web application capable of identifying medicinal plants from leaf images using YOLOv8 model. The system, developed in Python and integrated with an HTML/CSS frontend, enables users to upload plant images and instantly receive accurate classifications along with their medicinal properties. This project combines deep learning with a user-friendly interface to make traditional plant knowledge more accessible and reliable.


File Structure - 

Medicinal_Plants_Detection_By-Using_Deep_Learning_Model/
│
├── dataset/                       # Dataset of medicinal plants
│   ├── train/                     # Training images
│   │   ├── Neem/
│   │   ├── Tulsi/
│   │   ├── Haritoki/
│   │   └── ... (other plants)
│   ├── test/                      # Testing images
│   └── validation/                # Validation images
│
├── models/                        # Saved trained models
│   └── medicinal_plant_model.h5
│
├── static/                        # CSS, JS, images for web UI
│   └── style.css
│
├── templates/                     # HTML templates for Flask
│   └── index.html
│
├── app.py                         # Flask application entry point
├── requirements.txt               # Dependencies
├── README.md                      # Project description
└── LICENSE                        # License file

