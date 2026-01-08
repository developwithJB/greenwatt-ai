🌍 AI Impact Tracker

A live-updating dashboard tracking the environmental cost of Artificial Intelligence.

View Live Site: https://developwithjb.github.io/greenwatt-ai/

📖 About

As AI models like GPT-4, Gemini, and Claude become ubiquitous, their environmental footprint grows. This project is an Open Source initiative to visualize the invisible costs of AI—specifically water consumption (for cooling datacenters) and electricity usage.

The goal is not to shame AI, but to bring awareness to the physics behind the prompt.

✨ Features

Live "Pulse" Tracking: Dramatic, real-time simulated counters showing daily accumulation of water (L) and electricity (kWh) usage.

Top 5 Rankings: Comparative table of major models (ChatGPT, Gemini, etc.) based on estimated user base and TDP.

Contextual Analysis: Translates abstract numbers into real-world terms (e.g., "Water Bottles Used," "Households Powered").

Social Integration: Direct links to AI thought leaders @developwithjb and @agbcoaching.

Open Source Data: Transparent methodology allowing the community to update coefficients as models become more efficient (or demanding).

🚀 How to Run (GitHub Pages)

This project is built as a single-file static site, making it incredibly easy to host for free on GitHub Pages.

Fork this repository.

Go to Settings > Pages.

Under Source, select main (or master) branch.

Click Save.

Your site will be live at https://[your-username].github.io/ai-impact-tracker.

🛠️ Methodology & Logic

Since AI companies do not publish real-time consumption APIs, this site uses a Client-Side Estimation Engine.

The JavaScript logic calculates usage based on the time of day relative to midnight (Local User Time) using these base coefficients:

Water: ~500ml per 20-50 queries (Source: UCR Study).

Energy: ~0.3Wh per average query.

Note: These are global estimates and subject to change based on model optimizations.

🤝 How to Contribute

We want this data to be as accurate as possible.

Found a new research paper on AI energy consumption?

Open an Issue with the source.

Or submit a Pull Request updating the const RATE_... variables in index.html.

🔗 Connect

Dev: Instagram @developwithjb

Strategy: Instagram @agbcoaching

Built with HTML5, Tailwind CSS, and FontAwesome.
