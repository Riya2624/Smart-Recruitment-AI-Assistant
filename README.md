# **AI-Powered Recruitment Assistant**

## **Project Overview**  
The **Ai-Powered Recruitment Assistant** is an AI-driven tool designed to optimize the recruitment process. Leveraging the **LLaMA model**, LangChain, and ChatGroq, this system extracts key details such as job roles, required skills, and experience levels from job descriptions. It integrates **ChromaDB** for semantic portfolio matching and real-time feedback, while an interactive **Streamlit** interface provides seamless functionality for job input, portfolio matching, and automated email generation.  

## **Features**  
1. **Job Description Analysis**:  
   Extracts structured data, such as job roles, skills, and experience levels, from unstructured job descriptions using the LLaMA model and LangChain.  

2. **Semantic Portfolio Matching**:  
   Utilizes **ChromaDB** for efficient vector-based semantic search, matching candidate portfolios based on job requirements.  

3. **Interactive Web Interface**:  
   Built using **Streamlit**, the interface allows recruiters to input job descriptions, view matching portfolios, and manage candidate communication.  

4. **Automated Email Generation**:  
   Employs **ChatGroq** for generating contextually personalized emails to communicate with shortlisted candidates or stakeholders.  

5. **Real-Time Feedback**:  
   Provides dynamic portfolio matching and instant feedback, enabling faster recruitment decisions.  

## **Technologies Used**  
- **LLaMA Model**: For natural language understanding and key detail extraction.  
- **LangChain**: To process unstructured job descriptions into structured data.  
- **ChatGroq**: For natural language processing and email generation.  
- **ChromaDB**: A vector database for semantic search and efficient portfolio matching.  
- **Streamlit**: To build an interactive and user-friendly web interface.  
- **Python**: The core programming language for system development.  

## **Installation and Setup**  

### **Prerequisites**  
Ensure you have the following installed:  
- Python 3.8 or above  
- pip (Python package installer)  

### **Installation Steps**  
1. Clone the repository:  
   ```bash
   git clone https://github.com/Riya2624/AI-Powered-Recruitment-Assistant.git
   cd recruitment-assistant
2.Install dependencies:
    pip install -r requirements.txt
3.Download and set up the LLaMA model:
Follow instructions from Hugging Face's LLaMA model to download the weights and tokenizer.
4.Run the application:
streamlit run app.py

### **Usage**
1.Upload a job description through the Streamlit interface.
2.The tool extracts roles, skills, and experience details.
3.View matched candidate portfolios using semantic search powered by ChromaDB.
4.Automatically generate customized emails for shortlisted candidates.
