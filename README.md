# 🤖 **JobQuest AI**
### 🌟 **Your AI Companion for Job Applications**

![Python](https://img.shields.io/badge/Python-%2314354C.svg?style=for-the-badge&logo=python&logoColor=white)
![Rasa](https://img.shields.io/badge/Rasa-%2300A3E0.svg?style=for-the-badge&logo=rasa&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-Cloud-red?style=for-the-badge&logo=streamlit) 
![Status](https://img.shields.io/badge/Status-In%20Development-orange?style=for-the-badge)


---

## 📄 **Overview**

**JobQuest AI** is a conversational AI chatbot designed to enhance the job application process by effectively answering common candidate queries and guiding users through the various stages of applying for a job. Leveraging **Natural Language Processing (NLP)**, the chatbot understands and responds to user inputs with accuracy and relevance, streamlining the job application process for candidates.

The chatbot collects and stores applicant details, including the full name, mobile number, email address, and a link to their resumes, in a structured format (CSV), making it easy to manage and review applicant data.

---

## ✨ **Key Features**

- **🔹 Candidate Query Handling**  
  The chatbot can respond to frequently asked questions from candidates, such as inquiries about job openings, application status, and company information.

- **🔹 Guided Application Process**  
  Assists candidates through the job application process, providing step-by-step guidance and collecting necessary information like full name, mobile number, email, and resume.

- **🔹 Natural Language Processing**  
  Utilizes NLP to interpret user inputs and provide appropriate responses, ensuring a seamless and intuitive interaction experience.

- **🔹 Custom Actions**  
  Includes tailored responses and actions such as greeting users, providing job descriptions, and offering company information.

- **🔹 Applicant Details Storage**  
  Collects applicant details and stores them in a CSV file for easy access and management.

---

## 🛠️ **Tech Stack**

- **Programming Language:**  
  ![Python](https://img.shields.io/badge/Python-3.8-blue.svg?style=for-the-badge&logo=python&logoColor=white)  
  Used for implementing the model and backend functionalities.

- **Frameworks:**  
  ![Rasa](https://img.shields.io/badge/Rasa-2.8.0-orange.svg?style=for-the-badge&logo=rasa&logoColor=white)  
  The primary library for building and deploying the conversational AI.  

  ![Streamlit](https://img.shields.io/badge/Streamlit-Cloud-red?style=for-the-badge&logo=streamlit)  
  Used for creating a user-friendly frontend interface.

- **Libraries Used:**  
  - `Requests`  
  - `Pandas`  
  - `NumPy`

---

## 🚀 **Getting Started**

### Prerequisites
Before you begin, ensure you have the following installed on your local machine:
- Python 3.8 or above
- Rasa and Streamlit libraries

### Installation
Follow the steps below to set up the project on your local environment:

1. **Navigate to the Project Directory:**
   ```bash
   cd JobQuest-AI

2. **Install Dependencies:**
Install the necessary dependencies using the requirements.txt file:
   ```bash
   pip install -r requirements.txt

3. **Run the Rasa Server:**
Launch the Rasa actions server:
   ```bash
   rasa run actions --port 5056

4. **Test the Chatbot:**
Open another terminal and run:

   ```bash
   rasa shell --port 5006 --endpoints endpoints.yml

---


## 📊 **Model Performance**
The model efficiently handles candidate queries with a high degree of accuracy, ensuring a smooth user experience. Performance metrics will be updated as the model is trained and refined.

---

## 📋 **Future Enhancements**
🌟 Integrate with Job Portals:
Expand the chatbot's capabilities to connect with popular job portals for real-time job openings.

🌟 Multilingual Support:
Enhance the chatbot to support multiple languages, catering to a diverse user base.

🌟 Advanced Analytics:
Implement analytics features to track user interactions and improve response accuracy based on feedback.

---

## 🤝 **Contributing**
Contributions are welcome! If you have suggestions for improvements or new features, feel free to open an issue or create a pull request. Let's collaborate to make this project even better!

---

## 📬 **Contact**
For any inquiries or suggestions, please feel free to reach out:

- Name: Heet Mehta
- Email: mehtaheet5@gmail.com
- GitHub: Heet852003




