"# AgroVision 🌾

An intelligent plant disease detection web application powered by machine learning, built to help farmers and agricultural professionals identify and manage plant diseases effectively.

## Features ✨

- **Disease Detection**: Predict plant diseases from crop images using deep learning models
- **Real-time Chat**: Interactive chat interface for agricultural guidance
- **Comprehensive Gallery**: Browse detected plant diseases and their classifications
- **News & Updates**: Stay informed about the latest agricultural insights
- **User Authentication**: Secure login system for personalized experiences
- **Dataset Integration**: Utilizes real-world plant disease datasets

## Dataset 📊

This project uses the **New Plant Diseases Dataset** from Kaggle:

📥 **Dataset Link**: [New Plant Diseases Dataset](https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset)

### Dataset Details
- **Size**: Comprehensive collection of plant disease images
- **Classes**: Multiple plant species and disease categories
- **Format**: High-quality images for training and validation
- **Usage**: Plant disease classification and detection

## Tech Stack 🛠️

### Backend
- **Flask** - Python web framework
- **Python** - Core backend language

### Frontend
- **HTML5** - Structure
- **CSS3** - Styling
- **JavaScript** - Interactivity
- **Node.js** - Runtime environment

## Project Structure 📁

```
AgroVision/
├── flask_app.py          # Flask backend application
├── server.js             # Node.js server configuration
├── start_servers.py      # Server startup script
├── main.js               # Frontend JavaScript logic
├── style.css             # Global styles
├── dataset-catalog.json  # Dataset metadata
├── package.json          # Node.js dependencies
│
├── HTML Pages:
├── index.html            # Homepage
├── login.html            # Authentication page
├── predict.html          # Disease prediction interface
├── gallery.html          # Disease gallery
├── news.html             # Agricultural news
├── about.html            # About the application
├── contact.html          # Contact information
│
└── README.md             # This file
```

## Installation & Setup 🚀

### Prerequisites
- Python 3.7+
- Node.js 12+
- pip (Python package manager)
- npm (Node package manager)

### Backend Setup
```bash
# Install Python dependencies
pip install flask

# Run Flask application
python flask_app.py
```

### Frontend Setup
```bash
# Install Node.js dependencies
npm install

# Start the servers
python start_servers.py
```

## Usage 💡

1. **Navigate to Homepage**: Open `index.html` in your browser
2. **Login/Register**: Access the authentication page
3. **Upload Image**: Use the predict page to upload crop images
4. **Get Predictions**: Receive disease detection results
5. **Browse Gallery**: Explore detected diseases in the gallery
6. **Chat Support**: Use the chat feature for agricultural advice

## How to Use the Dataset

1. Download the dataset from: [Kaggle New Plant Diseases Dataset](https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset)
2. Extract the dataset to your local directory
3. Update `dataset-catalog.json` with your dataset paths
4. Train your model using the provided images
5. Integrate predictions into the application

## Key Pages

| Page | Purpose |
|------|---------|
| `index.html` | Landing page and main dashboard |
| `login.html` | User authentication |
| `predict.html` | Disease prediction from image upload |
| `gallery.html` | Browse all detected plant diseases |
| `news.html` | Agricultural news and updates |
| `about.html` | Project information |
| `contact.html` | Contact and feedback form |

## API Endpoints

The Flask backend provides RESTful endpoints for:
- Plant disease prediction
- Image processing
- User authentication
- Data retrieval

## Future Enhancements 🎯

- Mobile app development
- Real-time disease monitoring
- Integration with IoT sensors
- Weather-based predictions
- Crop recommendation system

## Contributing 🤝

Contributions are welcome! Please feel free to submit a Pull Request.

## License 📄

This project is open source and available under the MIT License.

## Support & Contact 📧

For questions, issues, or feedback, please visit our contact page or open an issue on the repository.

---

**Last Updated**: May 2026  
**Version**: 1.0.0" 
