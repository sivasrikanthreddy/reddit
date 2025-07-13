# Reddit User Persona Generator

## 📦 Setup Instructions

1. Clone this repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Create a `.env` file in the root directory with the following variables:
   ```env
   REDDIT_CLIENT_ID=your_client_id
   REDDIT_CLIENT_SECRET=your_client_secret
   REDDIT_USER_AGENT=your_user_agent
   OPENAI_API_KEY=your_openai_api_key
   ```
4. Run the script with a Reddit profile URL:
   ```bash
   python reddit_persona.py --url https://www.reddit.com/user/kojied/
   ```
5. Check the generated persona in the `output/` directory.
