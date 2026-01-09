<!--
# Origin Intel - Technical Overview

Authority-based intelligence platform for cryptocurrency ecosystem monitoring.

## Architecture
- **Backend**: Python/FastAPI, Celery workers, PostgreSQL + Redis
- **Frontend**: Next.js 14, Tailwind CSS, shadcn/ui
- **Mobile**: React Native with push notifications
- **AI Pipeline**: Gemini Flash (L2) + Claude Sonnet (L3) for classification
- **Data Sources**: X API, GitHub API, governance platforms (Snapshot, Tally)

## Core Systems
1. **Authority Graph Builder**: Multi-strategy GitHub→X handle mapping
2. **Monitoring Engine**: Adaptive polling with rate limit optimization
3. **Triage Pipeline**: 3-level classification (regex → small LLM → heavy LLM)
4. **Anomaly Detector**: Baseline tracking with deviation flagging
5. **Context Engine**: Event linking and jargon translation
6. **Learning System**: Behavioral adaptation from user feedback

## Key Algorithms
- Authority scoring
- Shared authority pools for API efficiency
- Event-triggered tier escalation
- Cross-project systemic signal detection

## Getting Started
See [CONTRIBUTING.md](CONTRIBUTING.md) for
**/docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
