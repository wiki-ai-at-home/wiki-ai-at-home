# Wiki-AI-@Home: Open-Source Ethical AI Project

## Overview
Wiki-AI-@Home is an ethical, decentralized AI training system designed to enable community-driven AI development without corporate control. This project uses distributed computing to train AI models and implement volunteer-based data validation, maintaining full transparency in all aspects of its development and filtering.

## Project Goals
- **Decentralization**: Facilitate AI training across distributed systems.
- **Transparency**: Ensure all development stages are visible and open.
- **Community-Driven Validation**: Utilize volunteer efforts to validate and refine datasets.
- **Ethical AI Development**: Adhere to strict ethical guidelines in AI training and usage.

## ** Repository Structure**

```plaintext
 wiki-ai-at-home
├──  client/                 # AI-@Home Volunteer Computing Client
│   ├──  frontend/          # GUI & user interaction
│   ├──  backend/           # Compute sharing, task management
│   ├──  networking/        # Secure distributed computing framework
│   ├──  README.md         # Instructions & setup guide
│
├──  website/                # Main website & volunteer portal
│   ├──  frontend/          # Static web pages, UI/UX
│   ├──  backend/           # API for data submission, user tracking
│   ├──  README.md         # Setup & deployment guide
│
├──  models/                 # AI Models & Training
│   ├──  core-llm/          # Initial LLM trained using only open source, donated, and public domain data, validated and curated.
│   ├──  ai-training-ai/    # Specialized AI trainers (Core model will be specialized into models which will be used for training a more powerful general model, and useable independently.)
│   ├──  README.md         # Placeholder - models will each have their own README upon initialization of training.
│
├──  datasets/               # Training Data & Validation Tools
│   ├──  raw/               # Original, unfiltered data
│   ├──  cleaned/           # Verified, structured datasets
│   ├──  validation/        # Crowdsourced review tasks
│   ├──  README.md         # How to contribute & validate data
│
├──  optchanull/             # CAPTCHA Replacement
│   ├──  frontend/          # User interaction elements
│   ├──  backend/           # Task management & security
│   ├──  README.md         # Implementation details
│
├──  governance/             # Legal & Organizational Docs
│   ├──  non-profit.md      # Steps for legal non-profit formation
│   ├──  ethics.md          # Ethical safeguards & governance
│   ├──  funding.md        # Crowdfunding & grant strategies
│
├──  docs/                   # Technical Documentation
│   ├──  Optchanull.txt    # What's wrong with (re)Captcha?
│   ├──  CONTRIBUTING.md   # How to contribute (code, data, validation)
│   ├──  ARCHITECTURE.md   # System design & workflow
│   ├──  EthicalAI.txt     # Critical examination of using unethical AI to build ethical AI
│   ├── ROADMAP.md        # Milestones & progress tracking
│
├── README.md               # Project Breakdown
├── FAQ.md                  # Frequently Asked Questions
└── LICENSE                 # Open-source license (e.g., AGPLv3, MIT, etc.)
```



## How to Get Involved
- **Developers and Researchers**: Contribute to the AI-@Home client, model training, or ethical dataset curation.
- **Volunteers**: Donate computing power or participate in data validation.
- **Supporters**: Assist in funding and promoting the project.

## Licensing
This project is released under an open-source license (AGPLv3/MIT), which supports community contributions while ensuring that all derivatives remain freely available.

## Further Reading
For detailed instructions, setup guides, and project documentation, please refer to the README files within each directory and the docs folder.

---

