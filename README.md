Alta: Mindset, Refined.
Alta is a high-performance affirmation and mental-wellness platform designed for those who value both aesthetic minimalism and cognitive science. Built with a sleek black-and-blue interface, Alta moves beyond static quotes by leveraging edge-computing AI to deliver personalized psychological reframing in real-time.

View the Repository

🌌 The Aesthetic
Alta is built on a "Midnight Command" design language.

Primary: Deep Onyx (#000000)

Accent: Electric Cobalt (#0047AB)

Vibe: Focused, calm, and high-tech.

🚀 Key Features
🧠 AI-Driven Recommendations
Unlike traditional apps that cycle through a static list, Alta uses a Llama 3.3 backend deployed via Cloudflare Workers.

Context-Aware: Analyzes user goals and current mood to generate custom affirmations.

Edge Latency: Sub-second response times for instant cognitive reframing.

Durable Objects: Maintains a persistent "Memory Layer" of your mental journey without compromising privacy.

🖼️ Dynamic Widgets
Keep your mindset on your home screen.

System-Wide Integration: Beautifully designed iOS widgets in Small and Medium formats.

Real-time Updates: Automatically cycles through your most impactful affirmations throughout the day.

⚡ Performance & Persistence
Offline First: Powered by a robust CoreData caching layer to ensure your affirmations are available even without a connection.

Streak System: A gamified consistency engine that tracks your daily mindfulness progress, encouraging long-term habit formation.

Optimized Networking: Implements request batching to reduce battery drain and network overhead.

🛠️ Technical Stack
Frontend: SwiftUI (Modern declarative UI)

Local Persistence: CoreData (Persistent caching)

Backend/AI: Cloudflare Workers + Llama 3.3 (Edge Intelligence)

State Management: Durable Objects (Persistent user context)

Architecture: MVVM (Model-View-ViewModel)

📦 Installation
Bash
# Clone the repository
git clone https://github.com/megangadiparthy/alta-affirmation-app.git

# Navigate to the project directory
cd alta-affirmation-app

# Open in Xcode
open Alta.xcodeproj
Ensure you have Xcode 15.0+ installed.

Set your Cloudflare API credentials in the Config.xcconfig (if contributing to the AI module).

Build and Run on your physical device or simulator.

🗺️ Roadmap
[ ] Biometric Triggering: Integrating Apple HealthKit to trigger affirmations based on Heart Rate Variability (HRV) spikes.

[ ] Collaborative Circles: Private, end-to-end encrypted groups for sharing affirmations with close peers.

[ ] Apple Watch Complications: Glanceable affirmations for the wrist.

🤝 Contributing
Contributions are what make the open-source community such an amazing place to learn, inspire, and create.

Fork the Project

Create your Feature Branch (git checkout -b feature/AmazingFeature)

Commit your Changes (git commit -m 'Add some AmazingFeature')

Push to the Branch (git push origin feature/AmazingFeature)

Open a Pull Request

📄 License
Distributed under the MIT License. See LICENSE for more information.

Built with 💙 by Megan Gadiparthy
