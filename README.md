Idea Griller 

Turn vague ideas into clear, actionable project plans through intelligent AI interviews.

Idea Griller is an AI Agent Skill that helps founders, developers, creators, and entrepreneurs refine their ideas before investing time and money into building them.

Instead of blindly agreeing with your ideas, it asks thoughtful questions, challenges assumptions, identifies risks, and helps define a realistic MVP.

✨ Features
Interactive, one-question-at-a-time interviews
Target audience discovery
Assumption identification and validation
Competitive and alternative solution exploration
MVP feature prioritization
Risk identification
Structured project brief generation
🚀 Installation

Clone the repository:

bash
git clone https://github.com/Shubh484/idea-griller.git


For Codex, copy the skill into your project:

bash
mkdir -p .agents/skills

cp -r idea-griller/.agents/skills/idea-griller \
  .agents/skills/


For Claude Code, install the skill into .claude/skills/ using the supported project-level skill structure.

💡 Example

Prompt:

"I want to build an Airbnb-like platform for renting cameras."

Idea Griller will help investigate:

Who needs this platform?
Why would they rent instead of buying?
How will equipment owners trust renters?
How will payments and deposits work?
What should the MVP include?
📁 Project Structure
text
idea-griller/
├── .agents/
│   └── skills/
│       └── idea-griller/
│           └── SKILL.md
├── tests/
│   └── test-scenarios.md
├── README.md
└── LICENSE

🧪 Testing

See tests/test-scenarios.md for example evaluation scenarios.

🤝 Contributions

Contributions, suggestions, and improvements are welcome.

📄 License

MIT License.
