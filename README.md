# YourKey AI: OpenAI, Claude & Gemini Side Panel

A privacy-first, direct-to-API side panel assistant for Google Chrome. Bring your own API keys and chat with the world's most powerful AI models inside a dark-themed client completely local-to-device.

---

## 🚀 Key Features
* **Multi-Provider Hub:** Seamlessly switch between OpenAI, Anthropic Claude, and Google Gemini with dynamic UI visual indicator badges.
* **Zero-Host Privacy:** Local background protocols guarantee sensitive text ingestions never touch an external middleman server.
* **Smart Right-Click Context Menus:** Highlight text on any page, right-click and inject it instantly to your panel setup without heavy host permissions.
* **Google Search Grounding:** Toggle live web searches for Gemini models, backed by an inline automated safety status bar warning layout.
* **Markdown Conversational Export:** Save and download your full logs locally to your machine as clean `.md` files via the **📥 Export Chat** button.
* **Volatile State Protection:** Never lose your work. Active session memory automatically backs up locally during accidental side panel closures or sudden browser restarts.
* **Hyper-Lightweight Build:** Pure native JavaScript with zero bloated external framework dependencies for lightning-fast performance.

---

## 🛠️ Getting Started
1. Click 'Add to Chrome' and pin **YourKey AI** to your toolbar.

2. Open **YourKey AI**, click the gear icon (⚙️ - **API Settings**), securely paste your personal API keys (OpenAI, Claude, and/or Gemini).

3. Click your **'Select Active Model'** from the dropdown menu.

4. Click **'Save Settings'** and start chatting!

Note: Users must input their own personal API keys (OpenAI, Claude, and/or Gemini) to establish connectivity. New users can sign up for credits directly through these providers.

💡 Tip: Gemini models are free key friendly. OpenAI and Claude require paid key credits, though some OpenAI models may grant temporary free key access.

---

## 📞 Support & Feedback
If you encounter any bugs, have feature requests, or need technical assistance, please reach out via email:
* **Email:** mailto:corsandeffect@gmail.com

---

## 🔒 Privacy Policy

### 1. Data Handling & Privacy Declarations
To function, this extension processes and handles **Authentication information** (API Keys), **Personal communications** (chat history) and **Website content** (user-highlighted text). We do not collect, track, or store any of this data on external databases or developer servers. All user-generated text inputs, credential assets, and conversation history records remain strictly within your browser's local ecosystem.

### 2. API Key Security & Network Sandbox
* **Local Storage:** Keys are saved encrypted on your device using the browser's native `chrome.storage.local` API sandbox structure.
* **Network Sandbox:** The extension operates under a strict Content Security Policy (`connect-src`). It cannot send information to unauthorized third-party trackers or external tracking endpoints.
* **Direct Transmission:** Your keys and prompt text travel exclusively to the official endpoints:
  * OpenAI (`https://api.openai.com*`)
  * Anthropic Claude (`https://api.anthropic.com*`)
  * Google Gemini (`https://generativelanguage.googleapis.com*`)

### 3. Google Search Grounding Note
When explicitly activating the **Google Search Grounding** feature within Gemini settings, your specific prompt text is transmitted directly to Google Search index routers to pull real-time data into your chat response. No personal identifiers or API keys are exposed during this search.

### 4. Third-Party Disclaimers
Because you supply your own API keys, your prompt data and generation habits fall under the respective developer terms of service and data privacy agreements of the platforms you connect to:
* [OpenAI](https://openai.com/policies/row-privacy-policy/)
* [Anthropic Claude](https://www.anthropic.com/legal/privacy)
* [Google Gemini](https://support.google.com/gemini/answer/13594961?hl=en)

### 5. Policy Updates
Any future revisions to this document will be updated transparently on this landing page. Contact us at the support email above for code review inquiries.

---
