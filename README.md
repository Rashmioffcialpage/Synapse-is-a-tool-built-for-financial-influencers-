# Synapse --------Columbia Iterate x Hackathon won this pre finalist first team🚀💡

**Synapse** is an AI-powered tool that automatically analyzes corporate earnings calls to surface key red flags, helping financial content creators cut through the noise and highlight what really matters. 📊🎙️

---

## Table of Contents

- [Overview](#overview)  
- [Features](#features)  
- [How It Works](#how-it-works)  
- [Tech Stack](#tech-stack)  
- [Getting Started](#getting-started)  
- [Acknowledgements](#acknowledgements)  
- [License](#license)  

---

## Overview 🧐

Earnings calls are notoriously difficult to parse. Companies often bury bad news in jargon, gloss over declining metrics, or avoid topics entirely. For analysts and content creators, manually combing through transcripts is time-consuming—and subtle signals can easily be missed. ⏳

**Synapse** solves this by automatically comparing earnings calls across consecutive quarters to identify:  

- ⚠️ Sudden changes in tone  
- ❌ Metrics that quietly disappeared from the narrative  
- 🕵️‍♂️ Soft language hinting at potential issues  

Users can then select these red flags to generate **polished podcast audio summaries** 🎧, ready to share with their audience.

---

## Features ✨

- 🤖 Automated comparison of earnings call transcripts across quarters  
- 📈 Detection of sentiment shifts, pipeline omissions, milestone delays, and disclosure changes  
- 🎙️ Generation of ready-to-share audio breakdowns (podcasts)  
- ✅ Selectable red flags for customized content creation  

---

## How It Works ⚙️

1. **Transcript Input** 📄: Provide two consecutive earnings call transcripts.  
2. **Analysis** 🔍: Synapse uses AI to detect red flags, such as:  
   - Changes in sentiment 😕➡️😃  
   - Missing metrics ❌📊  
   - Soft or ambiguous language 🗨️  
3. **Review** 👀: Users select which red flags to highlight.  
4. **Podcast Generation** 🎧: Synapse generates a polished audio summary for sharing.  

---

## Tech Stack 🛠️

- **AI & Backend**: [Claude Opus 4.5](https://www.anthropic.com/) 🤖  
- **Frontend Interface**: [Lovable](https://lovable.ai/) 🎨  
- **Voice AI / Podcast Generation**: [Hathora](https://hathora.dev/) 🗣️  

---

## Getting Started 🚀

To run Synapse locally:

```bash
# Clone the repository
git clone https://github.com/yourusername/synapse.git
cd synapse

# Install dependencies
pip install -r requirements.txt

# Run the application
python app.py
