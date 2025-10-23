# Course Setup

## Introduction
This lesson explains how to prepare your environment and run code samples from the AI Agents for Beginners course.

---

## Community & Support
- Join the AI Agents For Beginners Discord channel to get help with setup, ask course questions, and connect with other learners.

---

## Cloning the Repository

**Fork or Clone:**
- Fork the repo on GitHub to create your own copy.
- Clone your fork to your machine:
  ```bash
  git clone --depth 1 https://github.com/<your-username>/ai-agents-for-beginners.git
  ```
  Replace `<your-username>` with your GitHub username.

**Shallow/Sparse Clone:**
- To save space, do a shallow clone (`--depth 1`) or sparse checkout for selected folders:
  ```bash
  git clone --depth 1 --filter=blob:none --sparse https://github.com/<your-username>/ai-agents-for-beginners.git
  cd ai-agents-for-beginners
  git sparse-checkout set 00-course-setup 01-intro-to-ai-agents
  ```

**Remove Git History (optional, irreversible):**
- Linux/macOS: `rm -rf .git`
- Windows: `Remove-Item -Recurse -Force .git`

---

## Using GitHub Codespaces
- Create a Codespace for your fork via GitHub.
- Use shallow/sparse clone commands in the Codespace terminal for selected folders.

---

## Tips
- Always use your fork URL if you want to edit or commit.
- You can fetch more history or files later by updating sparse-checkout settings.

---

## Running the Code

### Jupyter Notebooks
- The course provides Jupyter Notebooks for hands-on learning.
- Frameworks used:
  1. **Semantic Kernel Agent Framework** (semantic-kernel.ipynb)
  2. **AutoGen Framework** (autogen.ipynb)
  3. **Azure AI Foundry + Azure AI Agent Service** (azureaiagent.ipynb)

- Choose the framework that matches your available resources:
  - GitHub Account required for Semantic Kernel & AutoGen.
  - Azure Subscription required for Azure AI Foundry.

---

## Requirements

- **Python 3.12+**
  - Install Python 3.12 if missing.
  - Create and activate a virtual environment:
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # macOS/Linux
    venv\Scripts\activate     # Windows
    ```
- **GitHub Account** (for GitHub Models Marketplace)
- **Azure Subscription** (for Azure AI Foundry)
- **Azure AI Foundry Account** (for Azure AI Agent Service)

- **Install Dependencies:**
  ```bash
  pip install -r requirements.txt
  ```

---

## VSCode Setup
- Ensure VSCode is using the correct Python version (3.12+).

---

## GitHub Models Setup

### Step 1: Get a GitHub Personal Access Token (PAT)
- Go to your GitHub Account > Developer Settings > Personal Access Tokens.
- Select fine-grained tokens, minimal necessary permissions (Models).
- Recommended token duration: 7–30 days.
- Store your token securely.

### Step 2: Create Your `.env` File
- Copy example file:
  ```bash
  cp .env.example .env
  ```
- Paste your token into the `GITHUB_TOKEN` field in `.env`.

---

## Azure AI Foundry Setup

### Step 1: Retrieve Your Azure Project Endpoint
- Create a hub and project in Azure AI Foundry.
- Get your connection string from the project overview page.

### Step 2: Create Your `.env` File
- Copy example file:
  ```bash
  cp .env.example .env
  ```
- Paste your project endpoint into the `PROJECT_ENDPOINT` field.

### Step 3: Sign in to Azure
- Use keyless authentication with Microsoft Entra ID:
  ```bash
  az login --use-device-code
  ```

---

## Additional Environment Variables (For Agentic RAG Lesson)
- Add variables like `AZURE_SUBSCRIPTION_ID`, `AZURE_AI_PROJECT_NAME`, `AZURE_OPENAI_SERVICE`, and more to your `.env` as needed for Azure Search and OpenAI integration.

---

## Security & Best Practices
- Never share your personal tokens or credentials.
- Store all secrets securely (e.g., password manager).
- Use principle of least privilege for all access.

---

## Reference
- For full instructions and troubleshooting, consult the official [AI Agents for Beginners GitHub repo](https://github.com/microsoft/ai-agents-for-beginners).

---

# Advice for Beginners

## Getting Started

- Most of the course uses **Jupyter Notebooks**. These are widely used in industry for data science, AI, and ML projects.
- Being able to read and understand Jupyter Notebooks is a valuable skill. Many companies look for this in interviews—don’t forget to mention it!

## If You Get Stuck

- Don’t hesitate to watch the assisted video tutorials provided with the course.
- Learning from others and seeing step-by-step guides can be very helpful.

## Why Learn AI & ML?

- AI and ML are in high demand across many industries.
- The more you learn now, the more useful and employable you’ll be in the future.

## Growth Mindset

- **Don’t get discouraged or frustrated.**
  - Technology can be slow, errors will happen, and things may not work as expected.
  - It’s normal to fail—embrace mistakes as learning opportunities.
  - Take time to think or research what went wrong, fix it, and try again.
  - Remember: You learn more from failure than success.

## Good Practices for GitHub & Resumes

- Keep your GitHub repositories clean and organized.
- Add clear READMEs and documentation.
- Showcase your projects and learning journey—employers love seeing real work and progress.
- If you use Jupyter Notebooks, highlight this on your resume and in interviews.
- Be honest about what you know and what you’re learning.

---

**Remember:** Everyone starts somewhere. The most important thing is to keep learning, experimenting, and building your skills!
