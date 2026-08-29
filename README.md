## Hi there 👋

<THE LOT T.O — LAST OF TRUE TORONTO LTD.
Adaptive Intelligence • Institutional Design • Myth‑Tech Systems
Welcome to the official GitHub profile of THE LOT T.O — LAST OF TRUE TORONTO LTD., a Toronto‑based institutional design company building founder‑grade adaptive intelligence systems, cosmological brand architectures, and myth‑tech operational engines.

Our flagship system:

AICE™ — Adaptive Intelligence Canon Engine
AICE™ is a multi‑agent intelligence architecture that unifies mythology, institutional design, operational cognition, and adaptive forecasting into a single real‑time founder partner.

Built using:

Gemini 3.5 (intent routing, semantic expansion, multi‑agent reasoning)

Google GenAI SDK (agent framework)

Google Cloud Run (backend hosting)

Firestore (state + memory)

Pub/Sub (event bus for multi‑agent orchestration)

Cloud SQL (structured canon + archetype tables)

Cloud Build (CI/CD pipeline)

AICE™ routes every founder directive through a Gemini‑powered Intent Router, distributes it across Strategy, Creative Intelligence, Operational Intelligence, and Forecasting clusters, and synthesizes a canon‑aligned output through the Adaptive Response Engine.

This system was created specifically for the All Things Agentic Hackathon.

Architecture Overview
AICE™ operates across four layers:

1. Input & Intent Layer
User → Gemini 3.5 → Intent Router

2. Multi‑Agent Intelligence Layer
Strategy Agent Cluster

Creative Intelligence Cluster

Operational Intelligence Cluster

Forecasting & Analysis Cluster

3. Google Cloud Execution Layer
Cloud Run • Firestore • Pub/Sub • Cloud SQL • Cloud Build

4. Output & Delivery Layer
Adaptive Response Engine → Web UI / API

Spin‑Up Instructions
Clone the repo:

Code
git clone https://github.com/LAST-OF-TRUE-TORONTO-LTD/aice.git
cd aice
Install dependencies:

Code
pip install -r requirements.txt
Environment variables:

Code
GOOGLE_API_KEY=YOUR_KEY
PROJECT_ID=project-ffa5c7eb-9011-465a-a8c
Run locally:

Code
python agent/main.py
Deploy to Cloud Run:

Code
gcloud builds submit --tag gcr.io/$GOOGLE_CLOUD_PROJECT/aice-backend ./agent
gcloud run deploy aice-backend \
  --image gcr.io/$GOOGLE_CLOUD_PROJECT/aice-backend \
  --platform managed \
  --region us-central1 \
  --allow-unauthenticated
Test:

Code
curl -X POST https://YOUR_CLOUD_RUN_URL/run \
  -H "Content-Type: application/json" \
  -d '{"prompt": "Explain the AICE adaptive loop."}'
About THE LOT T.O
We build institutional systems that merge mythology, cosmology, operational intelligence, and adaptive design into unified founder‑grade architectures.

This profile represents our public research, systems, and agentic frameworks.!--
**lastoftruetorontoltd/LASTOFTRUETORONTOLTD** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
