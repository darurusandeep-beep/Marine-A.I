# 🌊 Marine Intelligence Platform

AI-powered marine safety, weather, PFZ, alerts & navigation assistant for Indian fishermen.

## Features
- Real-time sea safety & weather
- Alert Agent (CRITICAL / WARNING / ADVISORY)
- Potential Fishing Zones (PFZ)
- Multi-route satellite navigation
- Voice input + Text-to-Speech (English / Hindi)
- Live coastal monitoring dashboard

## Deploy to Streamlit Community Cloud (Free Public Link)

### 1. Create a GitHub repository
1. Go to https://github.com/new
2. Name it e.g. `marine-intelligence-platform`
3. Make it **Public**
4. Click **Create repository**

### 2. Upload these files
Upload these 3 files to the repository:
- `marine_intelligence_platform.py` (main app)
- `requirements.txt`
- `README.md` (optional)

### 3. Deploy on Streamlit Cloud
1. Go to https://share.streamlit.io
2. Sign in with your GitHub account
3. Click **New app**
4. Select your repository
5. Main file path: `marine_intelligence_platform.py`
6. Click **Deploy**

### 4. Add Secret (Important)
After first deploy:
1. Go to your app → **Settings** → **Secrets**
2. Add this:

```toml
GROQ_API_KEY = "your_actual_groq_api_key_here"
```

3. Save → App will restart automatically.

### 5. Your Public Link
You will get a free permanent link like:

```
https://marine-intelligence-platform-xxxx.streamlit.app
```

Share this link with anyone — it works like a website.

---

## Local Testing
```bash
pip install -r requirements.txt
streamlit run marine_intelligence_platform.py
```

## Notes
- Keep your Groq API key private (use Secrets, never commit it).
- The app works best on Chrome / Edge for voice features.
