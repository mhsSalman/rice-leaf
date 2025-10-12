rice-disease-detection/
│
├── dataset/                        # Dataset gambar
│   ├── Bacterial_Leaf_Blight/     # Folder gambar penyakit 1
│   ├── Brown_Spot/                # Folder gambar penyakit 2
│   ├── Leaf_Smut/                 # Folder gambar penyakit 3
│   └── Healthy/                   # Folder gambar sehat
│
├── model/                         # Model yang sudah ditraining
│   └── rice_disease_model.h5     # Model utama
│
├── templates/                     # HTML templates
│   └── padi.html                  # Frontend interface
│
├── static/                        # Static files
│   ├── js/
│   │   └── penyakit_integrated.js # JavaScript frontend
│   └── css/
│
├── logs/                          # Training logs (TensorBoard)
│
├── app.py                         # Flask backend (API)
├── train_model.py                 # Script training model
├── requirements.txt               # Python dependencies
└── README.md                      # Dokumentasi ini
