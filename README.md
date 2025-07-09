# 🎯 Phishing Website Detection Tool

Phishing websites are a major cybersecurity threat that deceive users into revealing sensitive information like login credentials, banking details, and personal data. This project provides a lightweight, effective tool to detect such malicious URLs using rule-based or machine learning techniques.

---

## 🚀 Objective
---
To develop a tool that:
- Detects potentially harmful URLs  
- Flags suspicious links before users click them  
- Helps reduce the risk of identity theft and fraud
---

## 🛠️ Technologies Used
---
Depending on your implementation:

- **Python 3**
- **Pandas** – for data handling  
- **Regex** – for rule-based URL pattern detection  
- **Scikit-learn** – for building ML models  
- **Tkinter** *(optional)* – for GUI interface  
- **URL Dataset** – containing both phishing and legitimate URLs

---

## 📦 Requirements
---
Install the required dependencies using pip:

```bash
pip install pandas scikit-learn
```
---
For optional GUI support:
```
pip install tk
```
---
### 🔍 Features
---
- 🔒 Rule-Based Detection
Checks for suspicious URL patterns like:

- IP-based URLs

- Excessive use of special characters

- Known phishing domain structures

- 🤖 Machine Learning-Based Detection

- Trained on labeled dataset (phishing vs. legitimate)

- Uses features like URL length, presence of HTTPS, domain age, etc.

- 🖥️ Optional GUI using Tkinter

- 📊 Accurate Classification and easy-to-understand output
---
### 📁 Project Structure
---
```
phishing-url-detector/
│
├── phishing_detector.py         # Main detection script
├── rule_based_detector.py       # Rule-based version
├── ml_model.py                  # ML-based version
├── dataset/
│   └── phishing_legit_urls.csv  # Sample dataset
├── gui_app.py                   # (Optional) Tkinter-based GUI
├── requirements.txt
└── README.md
```

### 🧪 How to Run
---
1.Clone the repository
```
git clone https://github.com/AtharvaDalvi2003/phishing-url-detector.git
cd phishing-url-detector
```
2.Install dependencies
```
pip install -r requirements.txt
```
3.Run the desired version
- Rule-based:
```
python rule_based_detector.py
```
- Machine Learning-based:
```
python ml_model.py
```
- GUI version:
```
python gui_app.py
```
---
## ✅ Expected Outcome
---
- Flags URLs as Safe or Phishing

- Helps users identify suspicious links before interacting

- Can be integrated with web extensions or apps for added protection
---
## 📸 Screenshot

Legitimate (SAFE)

![Image](https://github.com/user-attachments/assets/f1fc173e-0d02-4822-ac9b-fddedac87d70)

Suspicious (NO HTTPS)

![Image](https://github.com/user-attachments/assets/57293d3f-889b-4090-b1e1-72dfc10b0d42)

---
## 🧾 License
This project is open-source and available under the MIT License.

