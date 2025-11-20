# This file is only for editing file nodes, do not break the structure
## Project Description
[TODO: Add project description - describe core functionality, unique value, and target users]

## Key Features
- [Core Feature 1 - main capability]
- [Core Feature 2 - unique highlight]
- [Core Feature 3 - user value]

## Data Storage
Tables: [list table names, use table_list tool for details]
Local: [if storing locally only, note here]

## Devv SDK Integration
Built-in: [used built-in features like auth, table, DevvAI, image, etc.]
External: [external services requiring API keys like OpenRouter, Replicate, ElevenLabs, etc.]

## Special Requirements
[User's special requirements or constraints if any]

/src
├── assets/          # Static resources directory
│
├── components/      # Components directory
│   ├── ui/         # Pre-installed shadcn/ui components
│
├── hooks/          # Custom Hooks directory
│   ├── use-mobile.ts # Mobile detection Hook
│   └── use-toast.ts  # Toast notification system Hook
│
├── lib/            # Utility library directory
│   └── utils.ts    # Utility functions, including cn function for merging Tailwind classes
│
├── pages/          # Page components directory (React Router structure)
│   ├── HomePage.tsx # Home page [next: replace initial template code]
│   └── NotFoundPage.tsx # 404 error page
│
├── store/          # State management directory (Zustand)
│   └── [list store files if any]
│
├── features/       # Feature modules directory (if any)
│   └── [feature-name]/
│       ├── components/
│       ├── hooks/
│       └── types.ts
│
├── App.tsx         # Root component with React Router configuration
│                   # Add new route configurations in this file
│                   # Includes catch-all route (*) for 404 handling
│
├── main.tsx        # Entry file, renders root component and mounts to DOM
│
├── index.css       # Global styles file with Tailwind config and design system [next: define design system]
│                   # Modify theme colors and design variables in this file
│
└── tailwind.config.js  # Tailwind CSS v3 configuration file
