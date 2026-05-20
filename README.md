# Compliance in AI

Reveal.js presentation for AI Pioneers Club Denver, 2026-05-20.

**Thesis:** The size of an AI system defines the rules you apply to it. Classical physics versus quantum physics. Personal AI lives in classical mechanics. Enterprise AI lives in quantum mechanics. Different scales call for fundamentally different governance.

Live: https://compliance.chasealdridge.com

## Local preview

```bash
python3 -m http.server 8765
# open http://localhost:8765
```

Press `S` in the deck for speaker view.

## Deploy

Docker + nginx static host on Coolify. Port 3000.

```bash
docker build -t compliance-in-ai .
docker run -p 3000:3000 compliance-in-ai
```

Production deploys via Coolify auto-build on push to `main`.
