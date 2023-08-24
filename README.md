

virtualenv .venv
source .venv/scripts/activate
pip install -r requirements.txt
streamlit run Chatbot.py
pip install httpx-oauth
pip install python-dotenv