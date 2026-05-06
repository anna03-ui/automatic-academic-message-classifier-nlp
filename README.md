# 📚 Academic Message Classifier using NLP

An intelligent NLP-based system that automatically classifies academic-related messages into meaningful categories such as **Events**, **Tech Talks**, **Auditions**, and **Other Academic Notices**.

The project also extracts important information like:
- 📅 Event Dates
- ⏰ Event Times
- 📝 Registration / Submission Deadlines

and simulates reminders for important academic activities.

---

# 🚀 Features

✅ Academic message classification using NLP  
✅ TF-IDF based feature extraction  
✅ Multinomial Naive Bayes classifier  
✅ OCR support for scanned image announcements  
✅ Regex-based extraction of dates and deadlines  
✅ Reminder simulation for events and tech talks  
✅ Interactive menu-driven system  

---

# 🧠 Technologies Used

- Python
- Scikit-learn
- Pandas
- Regex (re)
- Pytesseract OCR
- Pillow (PIL)
- Google Colab / Jupyter Notebook

---

# 📌 Project Workflow

1. Input academic text message or image  
2. Preprocess text data  
3. Extract features using TF-IDF  
4. Predict category using Naive Bayes  
5. Extract date/time using regex  
6. Simulate reminder generation  

---

# 📂 Categories Supported

| Category | Examples |
|---|---|
| Event | College Fest, Sports Day, Celebrations |
| Tech Talk | AI Workshop, Webinar, Seminar |
| Audition | Music Fest, Drama Auditions, Competitions |
| Other Academic | Assignments, Exam Notices, Library Updates |

---

# 📸 Sample Output

### Example Input
```text
Cyber Security Workshop on 15th Sep 2025 at 11:30 AM
```

### Predicted Output
```text
Predicted Category: Tech Talk
Event Date: 15th Sep 2025
Event Time: 11:30 AM
Reminder Set Successfully
```

---

# 🔍 OCR Support

The system can also process text from image-based announcements using **Pytesseract OCR**.

Example:
- WhatsApp posters
- Event banners
- Screenshot announcements

---

# 📊 Model Information

| Component | Technique Used |
|---|---|
| Feature Extraction | TF-IDF Vectorizer |
| Classification Model | Multinomial Naive Bayes |
| Information Extraction | Regular Expressions |
| OCR Engine | Pytesseract |

---

# 🎯 Future Improvements

- Integration with Google Calendar
- WhatsApp / Gmail integration
- Real-time notification system
- BERT / Transformer-based NLP models
- Larger real-world dataset support

---

# 📁 Repository Structure

```text
automatic-academic-message-classifier-nlp/
│
├── NLP_MINI_PROJECT.ipynb
├── NLP MINIPROJECT REPORT.pdf
├── presentation.pptx
├── screenshots/
├── dataset/
├── README.md
```

---

# 👩‍💻 Author

**Anna Rose Thomas**  
B.Tech AIML & Data Science  
CHRIST (Deemed to be University)

---

# ⭐ Project Highlights

- Real-world student-focused NLP application
- Combines Machine Learning + OCR + Regex
- Lightweight and beginner-friendly
- Practical academic automation use case

---
