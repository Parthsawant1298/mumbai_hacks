# Veritas: Multi-Agent Truth Operating System

<div align="center">
  <img src="https://img.shields.io/badge/Agentic%20AI-Powered-blue?style=for-the-badge&logo=robot" alt="Agentic AI"/>
  <img src="https://img.shields.io/badge/Misinformation-Detection-red?style=for-the-badge&logo=shield" alt="Misinformation Detection"/>
  <img src="https://img.shields.io/badge/Google%20Gemini-2.5%20Flash-green?style=for-the-badge&logo=google" alt="Google Gemini"/>
  <img src="https://img.shields.io/badge/Real--time-Scanning-orange?style=for-the-badge&logo=zap" alt="Real-time"/>
</div>

## 🌟 The World's Most Advanced Agentic AI for Truth Verification

**Veritas** is not just another fact-checker—it's a revolutionary Multi-Agent Truth Operating System that deploys autonomous AI agents to combat misinformation at scale. Built for the MumbaiHacks 2025 Misinformation track, Veritas transforms how professionals verify information in real-time crises.

> **"In a world drowning in information, Veritas is the lighthouse that cuts through the fog of misinformation."**

## 📋 Table of Contents

- [🎯 Problem Statement](#-problem-statement)
- [🚀 Key Features](#-key-features)
- [💡 Pain Points & Solutions](#-pain-points--solutions)
- [🔄 How It Works: Agent Flows](#-how-it-works-agent-flows)
- [🏢 Company Intelligence Dashboard](#-company-intelligence-dashboard)
- [🛠️ Tech Stack](#️-tech-stack)
- [⚡ Why Veritas is Superior](#-why-veritas-is-superior)
- [💼 Business Model](#-business-model)
- [🌐 Chrome Extension](#-chrome-extension)
- [📦 Installation](#-installation)
- [🎮 Usage](#-usage)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)

## 🎯 Problem Statement

**MumbaiHacks 2025 - Misinformation Track**

Global crises like pandemics, geopolitical conflicts, or climate events generate a surge of online information, much of it confusing, conflicting, or deliberately false. This overload makes it difficult for citizens to know what to trust and how to act—leading to misinformation-driven harm.

**Agentic AI Challenge:** Build an AI agent capable of scanning multiple content streams and detecting emerging misinformation trends related to global or local crises. The agent should verify claims using cross-references and produce accessible, contextual explanations or corrections for diverse audiences.

## 🚀 Key Features

- **🤖 Multi-Agent Architecture**: 4 specialized AI agents working in harmony
- **🔍 Real-Time Crisis Scanning**: Proactive detection of misinformation trends
- **📊 Corporate Intelligence Engine**: Dedicated analysis for companies and investors
- **🖼️ Visual Claim Verification**: Extract and verify claims from images and screenshots
- **🎤 Voice-Enabled Interactions**: Real-time fact-checking via voice conversations
- **📈 Temporal Graph Analytics**: Track misinformation patterns over time
- **🌐 Chrome Integration**: Seamless browser-based verification
- **💬 Conversational AI**: Chat with verified news data using natural language
- **📱 Cross-Platform**: Web app, API, and browser extension support

## 💡 Pain Points & Solutions

### For Traders & Investors
**Pain Point:** Traders risk massive financial losses by acting on viral market rumors, fake earnings reports, or manipulated stock news that can crash portfolios in minutes.

**Veritas Solution:** Our Corporate Intelligence Engine provides real-time news verification with a Reliability Score, sentiment analysis, and temporal tracking. Traders get a "market truth dashboard" showing verified vs. fake news ratios, preventing costly decisions based on misinformation.

### For Journalists & Newsrooms
**Pain Point:** Journalists face intense deadline pressure to publish accurate stories, but verifying claims across multiple sources takes hours, risking the spread of unverified information.

**Veritas Solution:** The Main Agent routes queries instantly to specialized verifiers. Journalists can upload audio interviews for transcription and fact-checking, or scan crisis trends proactively. Our synthesis agent creates professional, sourced responses in seconds.

### For YouTubers & Content Creators
**Pain Point:** Content creators risk platform strikes, demonetization, or legal issues from sharing unverified claims, manipulated images, or trending but false narratives in their videos.

**Veritas Solution:** Visual claim extraction from screenshots prevents sharing fake tweet graphics. The Chrome extension allows right-click verification of scripts or articles. Voice mode enables real-time brainstorming with built-in fact-checking.

### For Researchers & Academics
**Pain Point:** Researchers need deep, structured analysis with citations, not just "True/False" labels. Generic tools lack the depth and source grounding required for academic work.

**Veritas Solution:** Confidence scoring (0.0-1.0), bias assessment, and comprehensive source grounding provide academic-grade verification. The synthesis agent structures findings into professional reports with evidence paragraphs.

## 🔄 How It Works: Agent Flows

Veritas employs a sophisticated agent orchestration system, inspired by real A2A (Agent-to-Agent) communication protocols. Here's how the agents collaborate:

### 1. Main Agent → Check Agent Flow (Fact-Checking Pipeline)
```
User Query → Main Agent (Routes) → Check Agent (Google Search + Verification) → Synthesis Agent (Professional Response)
```

**Example:** User asks "Is the claim 'COVID-19 vaccines cause infertility' true?"
- **Main Agent:** Recognizes factual query, delegates to Check Agent
- **Check Agent:** Searches Google, analyzes sources, returns VERDICT: FAKE, CONFIDENCE: 0.92, EXPLANATION: "Multiple studies show no link...", SOURCES: [WHO, CDC, Lancet]
- **Synthesis Agent:** Creates: "❌ This claim is FALSE. Vaccines do not cause infertility. Studies from WHO and CDC confirm safety..."

### 2. Main Agent → Scan Crisis Flow (Proactive Monitoring)
```
User Request → Main Agent → Scan Crisis Action → Check Agent (Batch Verification) → Structured Trend Report
```

**Example:** User says "Scan for misinformation about the Ukraine conflict"
- **Main Agent:** Triggers SCAN_CRISIS with topic="Ukraine conflict"
- **System:** Finds top 3 trending claims: ["Russia won Battle of Kyiv", "NATO invaded first", "Peace deal signed"]
- **Check Agent:** Verifies each claim with sources
- **Output:** Real-time dashboard with severity levels, volume metrics, and verified corrections

### 3. Main Agent → Process Image Flow (Visual Verification)
```
Image Upload → Main Agent → Image Agent (OCR + Extraction) → Check Agent → Verified Claims
```

**Example:** User uploads screenshot of a viral tweet claiming "Stock market crashed 50%"
- **Image Agent:** Extracts text: "BREAKING: Dow Jones down 50% after Fed announcement"
- **Check Agent:** Verifies against real market data
- **Result:** "FAKE: Dow Jones actually up 0.3% today. Source: Bloomberg, NYSE"

### 4. Voice Interaction Flow (Real-Time Conversation)
```
User Speech → Transcriber → Live Gemini Session → Tool Calls → Check Agent → Voice Response
```

**Example:** Podcaster says "Is it true that electric cars cause more pollution than gas?"
- **Transcriber:** Converts speech to text
- **Gemini Live:** Recognizes fact-check need, calls verify_fact tool
- **Check Agent:** Returns verdict with sources
- **Voice Response:** "Actually, electric cars produce zero tailpipe emissions..."

## 🏢 Company Intelligence Dashboard

### Registration & Profile Creation
Companies register via secure API endpoints, creating profiles with basic info (name, industry, website).

### Agent 1: Web Presence Discovery
```
Company Name from DB → Agent 1 → Google Search → Official Websites + Social Media + Investor Relations
```

**Example:** For "Tesla Inc."
- Finds official website: tesla.com
- Social: twitter.com/tesla, linkedin.com/company/tesla
- Investor: ir.tesla.com

### Agent 2: Multi-Source News Aggregation
```
Company Name → Agent 2 → 5 Targeted Google Searches → 30 News Items (Financial, Product, Legal, etc.)
```

**Categories:** Breaking News (12), Financial (10), Product/Innovation (8), Partnerships (6), Legal/Regulatory (4)

### Agent 3: Cross-Reference Verification
```
News Items + Official Sources → Agent 3 → Verification Engine → VERDICT + Confidence + Bias + Impact
```

**Enhanced Analysis:** Each news item gets bias assessment, impact rating, and detailed reasoning.

### Temporal Graph Storage
All verified data stored in MongoDB with timestamps, enabling trend analysis over time.

### Dashboard Features
- **Reliability Score:** (Real News / Total News) × Average Confidence × 100
- **Sentiment Analysis:** Positive/Negative/Neutral breakdown
- **Timeline Graphs:** 7-day trend visualization
- **Category Distribution:** Pie charts for news types
- **Source Tracking:** Top 10 news sources with credibility metrics

### Conversational Intelligence
Companies can chat with their news data: "Show me all negative news from last week" or "Summarize product launch announcements."

**Prompt-Based Queries:** Instead of raw data dumps, users get natural language summaries and insights.

## 🛠️ Tech Stack

- **AI Framework:** Google GenAI SDK with Gemini 2.5 Flash
- **Agent Architecture:** Real A2A (Agent-to-Agent) communication protocols
- **Search Tools:** Google Search API for real-time web verification
- **Backend:** FastAPI (Python) for high-performance async operations
- **Database:** MongoDB for temporal graph storage and news tracking
- **Frontend:** Next.js 14 with React components
- **Real-Time:** WebSocket integration for voice and live updates
- **Audio:** Native audio processing with WebRTC
- **Deployment:** Docker containers with auto-scaling
- **Security:** JWT authentication, API rate limiting, data encryption

## ⚡ Why Veritas is Superior: Feature Comparison

| Feature | Veritas | Perplexity AI | ChatGPT |
|---------|---------|---------------|---------|
| **Agentic AI** | ✅ Multi-agent orchestration with A2A protocols | ❌ Single model responses | ❌ No autonomous agents |
| **Real-Time Scanning** | ✅ Proactive crisis trend detection | ❌ Static search results | ❌ No real-time capabilities |
| **Multi-Source Verification** | ✅ Cross-references 5+ sources per claim | ✅ Basic source linking | ❌ No verification tools |
| **Visual Claim Detection** | ✅ OCR + fact-check from images | ❌ No image processing | ❌ Limited image analysis |
| **Voice Integration** | ✅ Real-time voice fact-checking | ❌ Text-only | ❌ No voice tools |
| **Corporate Intelligence** | ✅ Dedicated company analysis engine | ❌ No specialized tracking | ❌ Generic responses |
| **Temporal Analytics** | ✅ Trend graphs over time | ❌ No historical tracking | ❌ No temporal features |
| **Bias Assessment** | ✅ Low/Medium/High bias scoring | ❌ No bias detection | ❌ No bias analysis |
| **Confidence Scoring** | ✅ Precise 0.0-1.0 float values | ❌ Binary true/false | ❌ No confidence metrics |
| **Chrome Extension** | ✅ Browser-integrated verification | ❌ No extension | ❌ No extension |
| **Business Model** | ✅ Enterprise SaaS + API | ✅ Subscription model | ❌ No monetization tools |

**Verdict:** Veritas combines the best of search engines, AI chatbots, and specialized verification tools into one autonomous system. While Perplexity excels at search and ChatGPT at conversation, only Veritas deploys multiple agents working together for comprehensive truth verification.

## 💼 Business Model

### Core Monetization Strategies

1. **Enterprise SaaS Subscription**
   - **Tier 1 (Starter):** $49/month - Basic fact-checking, 100 queries/day
   - **Tier 2 (Professional):** $149/month - Voice integration, image verification, unlimited queries
   - **Tier 3 (Enterprise):** $499/month - Corporate intelligence, API access, white-label options

2. **API Licensing**
   - **Developer Tier:** $0.01 per API call for fact-checking
   - **Enterprise Tier:** Custom SLAs, dedicated infrastructure
   - **Government Contracts:** Specialized misinformation monitoring for public sector

3. **Premium Features**
   - **Real-Time Alerts:** $99/month - Instant notifications for crisis misinformation
   - **Custom Agent Training:** $999/setup - Domain-specific verification models
   - **Historical Analytics:** $299/month - Temporal trend analysis and reporting

4. **Partnership Revenue**
   - **News Organizations:** White-label verification tools
   - **Social Media Platforms:** Integrated moderation APIs
   - **Financial Institutions:** Market rumor monitoring services

### Revenue Projections
- **Year 1:** $2.5M (100 enterprise customers @ $25K avg)
- **Year 2:** $15M (500 customers, API revenue)
- **Year 3:** $50M+ (Market leader in AI verification)

### Go-to-Market Strategy
- **Phase 1:** Free beta for journalists and researchers
- **Phase 2:** Enterprise pilots with major news outlets
- **Phase 3:** Mass market adoption via Chrome extension

## 🌐 Chrome Extension

**Seamless Browser Integration for Content Creators**

### Features
- **Right-Click Verification:** Highlight text, right-click "Verify with Veritas"
- **Auto-Scan Articles:** Automatically check news pages for misinformation
- **Image Verification:** Upload screenshots directly from browser
- **Real-Time Alerts:** Notifications for trending false claims
- **Workflow Integration:** Embed verification results in content creation tools

### Technical Implementation
- **Manifest V3:** Modern Chrome extension architecture
- **Content Scripts:** Inject verification UI into web pages
- **Background Service:** Handle API calls and data processing
- **Popup Interface:** Quick access to verification history

## 📦 Installation

### Prerequisites
- Node.js 18+
- Python 3.9+
- MongoDB
- Google Cloud API key

### Backend Setup
```bash
cd app/backend
pip install -r requirements.txt
cp .env.example .env
# Add your GOOGLE_API_KEY and MONGODB_URI

# Quick start all services
python run_all.py

# Or run individually:
python main.py      # Core agents on port 8000
python data.py      # Data query API on port 8001
python company.py   # Company intelligence on port 8002
```

### Environment Variables
Create a `.env` file in `app/backend/` with:
```env
GOOGLE_API_KEY=your_google_gemini_api_key
MONGODB_URI=your_mongodb_connection_string
```

### Frontend Setup
```bash
npm install
npm run dev
```

### Chrome Extension
```bash
cd chrome-extension
# Load unpacked extension in Chrome developer mode
```

## 🎮 Usage

### Basic Fact-Checking
```javascript
// API call
const response = await fetch('/api/main-agent', {
  method: 'POST',
  body: JSON.stringify({ userText: "Is climate change real?" })
});
```

### Company Analysis
```javascript
const analysis = await fetch('/api/company/fetch-news', {
  method: 'POST',
  body: JSON.stringify({ companyId: "507f1f77bcf86cd799439011" })
});
```

### Voice Interaction
```javascript
// WebSocket connection
const ws = new WebSocket('ws://localhost:8000/ws/live-session');
// Send audio chunks for real-time verification
```

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md).

### Development Setup
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Add tests
5. Submit a pull request

### Agent Development
- Follow A2A communication protocols
- Add comprehensive logging
- Include error handling and fallbacks
- Test with diverse claim types

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<div align="center">
  <p><strong>Built with ❤️ for MumbaiHacks 2025</strong></p>
  <p>Transforming misinformation combat through autonomous AI agents</p>
  <p>
    <a href="#veritas-multi-agent-truth-operating-system">Back to Top</a>
  </p>
</div>
