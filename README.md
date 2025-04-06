# SugarCube

<p align="center">
  <img src="https://via.placeholder.com/150?text=SugarCube" alt="SugarCube Logo" width="150" height="150">
</p>

<p align="center">
  <strong>Your digital memory vault for moments that matter.</strong><br>
  Built during the **418 Hackathon**, hosted by **Enigma** under **AEON 2025**.
</p>

<p align="center">
  <a href="#overview">Overview</a> •
  <a href="#key-features">Key Features</a> •
  <a href="#motivation">Motivation</a> •
  <a href="#tech-stack">Tech Stack</a> •
  <a href="#architecture">Architecture</a> •
  <a href="#installation">Installation</a> •
  <a href="#usage">Usage</a> •
  <a href="#roadmap">Roadmap</a> •
  <a href="#contributing">Contributing</a> •
  <a href="#license">License</a>
</p>

## Overview

SugarCube is a digital sanctuary designed for preserving personal memories and moments. Unlike conventional social media platforms that prioritize public sharing and engagement metrics, SugarCube focuses on private reflection and meaningful memory storage. It provides users with a space to capture and revisit life's emotional, visual, and sensory experiences.

**[Live Demo](https://your-deployed-link.com)**

## Key Features

### Core Functionality
- **🎨 Memory Creation**
  - Upload images with captions
  - Tag with moods and emojis
  - Associate songs, scents, and text descriptions
  - Organize with customizable categories

### Experience Modes
- **📚 Timeline View** - Chronological exploration of memories
- **🔀 Shuffle Mode** - Random memory surfacing
- **📊 Routine Playback** *(Prototype)* - Track patterns across regular check-ins

### Collaborative Features
- **🤝 Shared Canvas** *(Prototype)* - Collaborative memory spaces for friends, travel groups, etc.
- **📆 Routine Tracker** *(Prototype)* - Daily check-in system with reward mechanics

### AI Integration
- **🤖 Reflection Assistance** - Google Gemini Pro-powered insights
- **✨ Pattern Recognition** - Emotional trend analysis and creative prompts
- **📝 Memory Enhancement** - AI-assisted caption and tag suggestions

## Motivation

SugarCube was born from a recognized gap in the digital landscape: while numerous platforms exist for sharing curated moments with others, few provide a dedicated space for personal memory preservation.

Traditional memory-keeping methods—journals, photo albums, keepsakes—offer emotional value through their privacy and permanence. SugarCube brings these qualities into the digital realm, creating a platform that values emotional clarity and authentic self-expression over social validation.

Our inspiration comes from analog memory artifacts: slam books, passed notes, mixtapes, and personal journals—items valued not for their reach but for their emotional resonance.

## Tech Stack

### Frontend
- **React** - Component-based UI
- **Tailwind CSS** - Utility-first styling
- **React Router** - Navigation and routing
- **Framer Motion** - Animation and transitions

### Backend
- **Node.js** - Runtime environment
- **Express** - Web framework
- **MongoDB** - Document database
- **Mongoose** - ODM for MongoDB

### Services
- **Firebase** - Authentication (email/password)
- **Cloudinary** - Media storage and optimization
- **Google Gemini Pro API** - AI integration for insights

## Architecture

### Current Implementation
- **User Data:** MongoDB collections for user profiles and memories
- **Media Storage:** Cloudinary for optimized image and media handling
- **Authentication:** Firebase Auth for secure user management

### Scalability Planning
- **Large-scale Storage:** Migration path to AWS S3 for media assets
- **Database Scaling:** Transition to Amazon RDS for improved performance
- **Caching Layer:** Implementation of Redis for frequently accessed memories

## Installation

```bash
# Clone the repository
git clone https://github.com/team-enigma/sugarcube.git
cd sugarcube

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env
# Edit .env with your API keys and configuration

# Start the development server
npm run dev
```

## Usage

### Creating a Memory
1. Sign in to your SugarCube account
2. Click the "+" button to create a new memory
3. Upload an image (optional)
4. Add details: mood, caption, associated song, etc.
5. Save to your collection

### Viewing Memories
- Use Timeline view for chronological browsing
- Try Shuffle mode for serendipitous discovery
- Filter by tags, dates, or emotional categories

### AI Insights
- Request reflections on patterns across memories
- Get suggestions for memory enhancement
- Explore emotional trends over time

## Roadmap

- **Q2 2025:** Launch shared memory spaces
- **Q3 2025:** Mobile app development (iOS & Android)
- **Q4 2025:** Advanced AI features and memory correlation
- **Q1 2026:** API for third-party integrations

## Contributing

We welcome contributions to SugarCube! Please see our [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

---

<p align="center">
  Made with 💙 by Team Enigma | <a href="mailto:team@sugarcube-app.com">Contact Us</a>
</p>
