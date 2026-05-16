
# 🚀 Utopia Onboarding Agent

AI-powered FastAPI agent that automates onboarding workflows using Gemini and Slack integration.

---

# 📌 What it does

- Generates onboarding plans for new fellows
- Uses Google Gemini AI to create structured tasks
- Sends onboarding updates to Slack automatically
- Produces JSON output for other agents in Utopia OS

---

# ⚙️ How to Run

## 1. Install Python
Make sure Python 3.10+ is installed.

Check version:
```bash
python --version
https://www.python.org/downloads/   (to download it if needed this is the link)

##2. Create virtual environment
Windows:
use this prompt : python -m venv venv
use this to activate it : venv\Scripts\activate

##3. Install dependencies
put this on you cmd: pip install -r requirements.txt

##4.Add environment variables:
Create a file named inside my code:
.env

##5.Place your gemeini api key and slack url because its diffrent from on pc to another each has its own
NOTE:I used this Model of Gemini  model="gemini-2.0-flash"
GEMINI_API_KEY=your_gemini_api_key_here
SLACK_WEBHOOK_URL=your_slack_webhook_here

##6. Run the server in VS terminal or CMD:
this is the prompt : python -m uvicorn main:app --reload

You should see:
Uvicorn running on http://127.0.0.1:8000

##7.Open in browser:
http://127.0.0.1:8000/docs (This will let you to test my agent)

##8.Then go to POST/onboard and then press try it out

##9.then press excute button

##10.The output will be shown under responses and this is the output 
