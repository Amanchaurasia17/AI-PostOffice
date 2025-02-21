# **AI-Powered Delivery Post Office Identification System** 🚀  

## 🏆 **Smart India Hackathon 2024 Finalist** 🏆  
**Team: Neural-Nodes**  
👤 **Aman Chaurasia** | 👤 **Ravikant Prajapti** | 👤 **Srishti Tripathi** | 👤 **Anjali Verma** | 👤 **Vikhyat Singh** | 👤 **Rounak Patel**  

### 📌 **Overview**  
This project automates **postal address identification and correction** using **AI, OCR, and NLP**, optimizing postal deliveries by reducing errors in mismatched PIN codes and delivery locations.  

## ✨ **Key Features**  
✅ **AI-Powered OCR** – Extracts text from postal envelopes using **Tesseract & OpenCV**.  
✅ **Intelligent Address Correction** – NLP-based **BERT model** corrects and validates extracted addresses.  
✅ **Self-Learning Feedback Loop** – Improves accuracy with real-world corrections.  
✅ **Real-Time Address Validation** – Integrates with **Google Maps API** for accurate location detection.  
✅ **Scalable and Lightweight** – Uses **Django (backend), React+Vite (frontend), SQLite (database)**.  

---

## 📂 **Project Structure**  

📦 AI-PostOffice
┣ 📂 neural_nodes_backend (Django Backend)
┃ ┣ 📜 manage.py (Django management file)
┃ ┣ 📂 api (API endpoints - Django REST Framework)
┃ ┣ 📂 models (BERT, OCR, database models)
┃ ┣ 📜 settings.py (Django configurations)
┃ ┗ 📜 requirements.txt (Python dependencies)
┣ 📂 neural_nodes_frontend (React + Vite Frontend)
┃ ┣ 📜 App.jsx (Main UI)
┃ ┣ 📂 components (UI components)
┃ ┣ 📜 tailwind.config.js (Tailwind CSS configuration)
┃ ┗ 📜 package.json (Frontend dependencies)
┣ 📂 data (Sample datasets for training/testing)
┣ 📂 models (Pre-trained AI models - OCR, NLP)
┣ 📜 README.md (Project documentation)
┣ 📜 docker-compose.yml (Deployment configuration)
┗ 📜 config.yaml (API keys and settings)


---

---

## ⚙️ **Tech Stack**  

| Component      | Technology |
|---------------|-----------|
| **Backend**   | Django, Django REST Framework |
| **Frontend**  | React + Vite, Tailwind CSS |
| **Database**  | SQLite, Firestore (NoSQL) |
| **OCR**       | OpenCV, Tesseract |
| **ML Model**  | BERT, Hugging Face Transformers, PyTorch |
| **Deployment**| Docker, AWS/GCP |

---

## 🚀 **Installation & Setup**  

### **1️⃣ Clone the repository**  
```bash
git clone --recurse-submodules https://github.com/your-repo/AI-Powered-Postal-System.git
cd AI-Powered-Postal-System


### 2️⃣ Install dependencies  

#### **Backend (Django)**
```bash
cd neural_nodes_backend
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver


#### **Frontend (React + Vite)**
```bash
cd ../neural_nodes_frontend
npm install
npm run dev


🔍 How It Works?
1️⃣ Upload a postal envelope image via the UI.
2️⃣ OCR extracts text (recipient name, address, PIN code).
3️⃣ ML Model (BERT) corrects and validates address.
4️⃣ Google Maps API verifies correct postal details.
5️⃣ Real-time dashboard displays corrected data.


📊 Model Training & Dataset
Dataset: Trained on Indian postal data, including real-world envelope images.
Training Pipeline:
Fine-tuned BERT for text correction.
Augmented dataset using synthetic postal data.
Active Learning: Retraining with real-world user feedback.


🔒 Security & Privacy
🔹 Data Encryption – Protects sensitive postal data.
🔹 GDPR Compliant – Ensures privacy for address storage.
🔹 Role-Based Access – Restricts unauthorized access to corrections.

📈 Future Improvements
🔹 Multilingual Support – Recognizing regional languages.
🔹 Mobile App – Postal workers can scan on-the-go.
🔹 AI-Driven Delivery Route Optimization – Smarter postal logistics.

## 🙌 **Contributors - Team Neural-Nodes (SIH 2024 Finalists)**  
👤 [Aman](https://github.com/Amanchaurasia17) [🔗](https://www.linkedin.com/in/amanchaurasiya14/)  
👤 [Ravikant](https://github.com/ravee360) [🔗](https://www.linkedin.com/in/ravikant-prajapati/)  
👤 [Srishti](https://github.com/Sritripathi) [🔗](https://www.linkedin.com/in/srishti-tripathi-b17b2325a/)  
👤 [Anjali](https://github.com/anjali0721) [🔗](https://www.linkedin.com/in/anjali-verma-8937b7258/)  
👤 [Vikhyat](https://github.com/prochecker101) [🔗](https://www.linkedin.com/in/vikhyat-s-24816025a/)  
👤 [Rounak](https://github.com/Ramakrishnan-1) [🔗](https://www.linkedin.com/in/rounak-patel/)  


📜 License
This project is open-source under the MIT License.

⭐ Support the Project!
If you find this useful, star the repo ⭐ and contribute!
