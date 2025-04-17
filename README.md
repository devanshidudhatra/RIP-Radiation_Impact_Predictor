# ☢️ RIP: Radiation Impact Predictor

RIP (Radiation Impact Predictor) is a web-based tool that predicts whether given solar radiation values (wavelength and irradiance) are harmful to **astronauts** and **satellites**. It uses pre-trained machine learning models to assess radiation danger and also provides AI-generated precautions to mitigate harm.

---

## 🚀 Features

- Predict radiation damage to:
  - 🧑‍🚀 Astronauts
  - 🛰️ Satellites
- Visual and textual AI-generated suggestions
- Built using Flask for a clean web interface
- Model inference based on wavelength & irradiance
- Built-in CSV dataset (`solarcurrent.csv` & `required_data.csv`)
- Displays safety level and AI-generated protection tips

---

## 📂 How to Use

### 1. Clone the Repository

```bash
git clone https://github.com/devanshidudhatra/RIP-Radiation_Impact_Predictor.git
cd RIP-Radiation_Impact_Predictor
```

---

### 2. Install Requirements

Ensure you have Python installed. Then install required libraries:

```bash
pip install -r requirements.txt
```

_(If no `requirements.txt`, install Flask and any other dependencies manually.)_

---

### 3. Run the Web App

```bash
python app.py
```

- Visit `http://localhost:5000` in your browser
- Enter radiation details to check impact and precautions

---

## 💡 Technologies Used

This project was built using:

- 🐍 Python
- 🌐 Flask
- 📦 Pickle (for loading ML models)
- 📁 CSV (for reading solar radiation data)
- 🧠 Pre-trained ML models for astronaut and satellite prediction
- 🎨 HTML + CSS for UI

---

## 🔍 File Structure

```bash
├── app.py                  # Main Flask app
├── RadiationPredictor.ipynb # Model training notebook
├── train_model.py         # Model training script
├── model_satellite.pkl    # Pickled model for satellite impact
├── model_astronaut.pkl    # Pickled model for astronaut impact
├── templates/
│   └── index.html         # Web interface template
├── static/
│   └── style.css          # Styling for the web page
├── solarcurrent.csv       # Radiation data
├── required_data.csv      # Training dataset
```

---

## 📸 Screenshots (Optional)

You can add screenshots by uploading images to a folder (e.g., `images/`) and embedding like this:

```markdown
![Web Interface](images/web-ui.png)
```

---

## 🙋‍♀️ Author

Developed by **Devanshi Dudhatra**  
🔗 [GitHub Profile](https://github.com/devanshidudhatra)
