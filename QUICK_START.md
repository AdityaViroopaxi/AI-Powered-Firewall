# Quick Start Guide - AI-Powered Firewall

**Author:** Aditya Viroopaxi   
**Repository:** [AI-Powered-Firewall](https://github.com/AdityaViroopaxi/AI-Powered-Firewall)

## 🚀 Quick Setup (Windows)

### Option 1: Automated Setup (Recommended)
```bash
# Clone the repository
git clone https://github.com/AdityaViroopaxi/AI-Powered-Firewall.git
cd AI-Powered-Firewall

# Run the automated setup
setup.bat
```

### Option 2: Manual Setup
```bash
# 1. Create virtual environment
python -m venv venv
venv\Scripts\activate

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run the application
cd app
python main.py
```

## 📋 Prerequisites

- **Python 3.8+** - [Download from python.org](https://python.org)
- **Git** - [Download from git-scm.com](https://git-scm.com)
- **Windows OS** (for .bat files)

## 🎯 Running the Applications

### AI Web Firewall (Main Application)
```bash
cd app
python main.py
```
- Open browser: `http://localhost:5000`
- Test the firewall protection system

### Hacker Portal (Testing Tool)
```bash
cd hacker_portal
python app.py
```
- Open browser: `http://localhost:5001`
- Simulate attacks to test the firewall

## 📊 Training the Model (Optional)

If you need to retrain the machine learning model:
```bash
python train_model.py
```

## 🔧 Troubleshooting

### Common Issues:

1. **Python not found**
   - Install Python 3.8+ from python.org
   - Make sure "Add Python to PATH" is checked during installation

2. **Virtual environment issues**
   - Delete the `venv` folder and run setup.bat again

3. **Package installation errors**
   - Try running: `pip install --upgrade pip`
   - Then run setup.bat again

4. **Model file missing**
   - Run `python train_model.py` to generate the model

5. **Dataset missing**
   - Download NSL-KDD dataset and place in `dataset/` folder

## 📁 Project Structure

```
AI-Powered-Firewall/
├── app/                 # Main firewall application
├── hacker_portal/       # Attack simulation tool
├── image/              # Project screenshots
├── dataset/            # Training data
├── model/              # ML model files
├── setup.bat           # Automated setup script
├── README.md           # Complete documentation
└── requirements.txt    # Python dependencies
```

## 🌐 Access URLs

- **AI Firewall**: http://localhost:5000
- **Hacker Portal**: http://localhost:5001

## 📞 Support

For issues or questions:
- Repository: [GitHub Issues](https://github.com/AdityaViroopaxi/AI-Powered-Firewall/issues)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
*Made with ❤️ by Aditya Viroopaxi*
