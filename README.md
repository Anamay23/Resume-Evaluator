<h1>LLM-Powered Resume Evaluator</h1>

<h2>Overview</h2>
The LLM-Powered Resume Evaluator is a tool that allows users to evaluate their resume against a given job description using different Large Language Models (LLMs). The tool provides feedback on how well the resume matches the job description and enables users to view the feedback from multiple models, helping them optimize their resume for better job prospects as well as guage how different LLMs provide output for the same task.


<h2>Features</h2>
📝 Resume Evaluation – Get feedback on how well your resume aligns with a job description
🔄 Multi-LLM Support – View evaluation results from OpenAI (GPT), Gemini, Claude, LLaMA, DeepSeek and Mistral
🎛 Configurable Parameters – Adjust model settings like temperature, max tokens, top-p, and top-k for fine-tuned responses (in the code)
🖥 User-Friendly Interface – A Streamlit-based UI that allows easy input of resumes and job descriptions

<h2>Setup & Installation</h2>

<h3>Prerequisites</h3>
Ensure you have Python installed (preferably Python 3.8+)

<h3>1. Clone the Repository</h3>
    git clone https://github.com/Anamay23/Resume-Evaluator.git
    cd llm-resume-evaluator

<h3>2. Create a Virtual Environment (Optional but Recommended)</h3>
    python -m venv venv
    source venv/bin/activate  # On macOS/Linux
    venv\Scripts\activate     # On Windows

<h3>3. Install Dependencies</h3>
    pip install -r requirements.txt

<h3>4. Create your own API Keys for all models and enter them as environment variables in .env file</h3>

<h3>5. Run the Application</h3>
    streamlit run app.py

<h2>Usage</h2>
Enter the job description for which you want feedback
Upload your resume 
Select the LLMs you want to use for evaluation
View feedback from different LLMs by selecting desired LLM 
Optimize your resume according to feedback generated

<h2>Configuration</h2>
You can modify config.py to update default LLM settings like:

temperature: Controls randomness in responses
max_tokens: Sets the maximum response length
top_p / top_k: Sampling methods for response diversity

<h2>Roadmap & Future Enhancements</h2>
🔹Add feature to compare results of different LLMs in a table on the UI
🔹Add feature to change model parameters like temp and max_tokens on the UI 

<h2>Contributing</h2>
Feel free to fork the repo and submit a pull request! Any contributions to improve the tool are welcome
