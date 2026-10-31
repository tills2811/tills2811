# GitHub Profile Setup Checklist

## 1. Publish the profile README
1. On GitHub, create a **new public repo named exactly `tills2811`**. Don't add a README; leave it empty.
2. Run these commands in PowerShell:
   ```powershell
   cd E:\github\tills2811
   git init
   git add README.md
   git commit -m "Add profile README"
   git branch -M main
   git remote add origin https://github.com/tills2811/tills2811.git
   git push -u origin main
   ```
   (SETUP.md stays local; only README.md is pushed.)

## 2. Edit profile (github.com → your avatar → Settings → Public profile)
| Field | Value |
|---|---|
| Name | `Shreyash Arali` (remove the trailing space) |
| Bio | `Full Stack AI Engineer · GenAI, RAG & Agentic AI · Next.js + FastAPI + LangGraph · @ THG Ingenuity` |
| Company | `THG Ingenuity` |
| Location | `Pune, India` |
| URL | `https://www.linkedin.com/in/shreyash-arali/` (or your portfolio once it's live) |
| Social | Add LinkedIn |
| Profile photo | Use a professional headshot (the same one as LinkedIn) |

## 3. Pin 6 repos (Profile → Customize your pins)
1. `blog_generator_ai_agent`
2. `google_adk_learnings`
3. `chatbot-site`
4. `genai_learnings`
5. `chatbot_omkar` (or the Portfolio News Agent once it's public)
6. `noteapp`

## 4. Polish the pinned repos (repo page → ⚙️ next to "About")
| Repo | Description | Topics |
|---|---|---|
| blog_generator_ai_agent | Multi-agent LangGraph pipeline that turns YouTube transcripts into structured blog posts | `langgraph` `langchain` `openai` `ai-agents` `pydantic` |
| google_adk_learnings | Agents built with Google's Agent Development Kit (ADK) | `google-adk` `ai-agents` `gemini` `python` |
| chatbot-site | Conversational AI chatbot web app | `chatbot` `llm` `generative-ai` |
| genai_learnings | GenAI notebooks: RAG, embeddings, prompting, agents | `rag` `langchain` `llm` `jupyter` |
| noteapp | Full-stack notes app in TypeScript | `typescript` `react` `nextjs` |

## 5. Hide beginner repos (Settings → Danger Zone → Archive, or make Private)
These 2023 HTML/CSS practice repos make the profile look like a student's:
`weather-app`, `e-patra`, `gapshup`, `Get_linked`, `Quote_generator`, `image-cursol`, `contact-animation`,
`Infinite_Scroll`, `Picture_in_picture`, `Portfolio-Website`, `Js_projects`, `GFG_full_stack`,
`Dbms-Mini`, `Event-management-website`, `frontend-websites`, `Blog_app`, `breeze.ai`, `BE_Project`

Making them **private** removes them from the profile (the contribution graph is kept if "private contributions" is enabled under Settings → Public profile).

## 6. Biggest upgrade: publish the Portfolio News Summarization Agent
It's your strongest full-stack AI project (Next.js + FastAPI + LangGraph + Zerodha) but it isn't on GitHub. Push it with a README (screenshot, architecture diagram, setup steps) and link it in the profile README.

## 7. Fix broken links
- `new-portfolio-website` → https://portfolio-umber-three-58.vercel.app returns **404**. Redeploy it or remove the homepage link.
