Soulgram

Soulgram is a simple reflection-based social web app where users can share short thoughts, feelings, or reflections.
It is designed to encourage authentic expression and meaningful connection.

🌱 Concept

Unlike traditional social platforms focused on metrics and attention, Soulgram centers around personal reflection and emotional expression.

Users can:

- Write short reflections
- Share thoughts in a simple feed
- Express themselves without pressure for likes or followers

The goal is to create a digital space for mindfulness and honest sharing.

---

🚀 Tech Stack

Soulgram is built with a lightweight modern stack:

- Frontend: HTML, CSS, JavaScript
- Database & API: Supabase
- Deployment: Vercel
- Repository: GitHub

Tools used:

- Supabase – backend database and API
- Vercel – hosting and deployment
- GitHub – version control

---

📦 Features (Current)

- Post reflections
- Store posts in a Supabase database
- Simple minimal interface
- Live web deployment

---

🔧 Setup

1. Clone the repository
2. Create a project in Supabase
3. Create a table called:

Soulgram

Columns:

id (int8, primary key)
content (text)
created_at (timestamp)

4. Add your Supabase credentials in "index.html":

const supabaseUrl = "YOUR_PROJECT_URL"
const supabaseKey = "YOUR_ANON_KEY"

5. Deploy with Vercel.

---

🌍 Live Deployment

The app is deployed using Vercel and automatically updates when new commits are pushed to GitHub.

---

🔮 Future Plans

Planned improvements for Soulgram:

- Reflection feed
- Emoji reactions
- User accounts
- Profile pages
- Daily reflection prompts
- Real-time updates

---

✨ Vision

Soulgram explores a different kind of social network — one that prioritizes reflection, emotional honesty, and meaningful interaction over engagement metrics.

---

📄 License

Open project for experimentation and learning.
