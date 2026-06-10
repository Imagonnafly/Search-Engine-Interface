Re:Search
Starting Search from Zero

A lightweight, customizable multi-realm search engine built with semantic HTML, advanced CSS animations, and vanilla JavaScript. Re:Search combines traditional web searching with user-defined search portals, voice commands, search memory, and personalized shortcuts in a fantasy-inspired interface.

Overview

This project focuses on creating a unique search experience rather than replicating existing search engines. Users can switch between multiple search realms, manage shortcuts, use voice search, access search history, and receive live query suggestions—all within a responsive, animated interface.

Goal	Create a customizable multi-engine search portal
Stack	Pure HTML, CSS, and JavaScript
Behavior	Realm switching, autocomplete, voice search, and local persistence
Accessibility	Keyboard shortcuts, focus states, and semantic structure
What's Included
Custom Re:Search branding and animated logo
Dark and Light theme switching
Multi-Realm Search Engine System
Google
YouTube
Wikipedia
User-created search portals
Dynamic Realm Manager
Create custom search engines
Edit existing realms
Delete custom realms
Voice Search using Web Speech API
Google-powered autocomplete suggestions
Search History Memory System
Search history management and deletion
"I'm Feeling Lucky" functionality
Custom Shortcut Dashboard
Add, edit, and remove shortcut cards
Automatic website favicon detection
LocalStorage persistence for all user data
Animated modal system for creating realms and shortcuts
Keyboard shortcut support
Press / to focus search
Press Escape to close menus and modals
Responsive mobile and desktop layouts
Advanced fantasy-themed visual effects and animations
Project Structure
.

|-- index.html
|-- style.css
`-- README.md
How It Works
Realm Engine

Users can select different search realms from the realm selector beside the search bar.

Each realm contains:

Search endpoint URL
Query parameter mapping
Custom branding icon

New realms can be created and saved locally for future sessions.

Search Experience

The search field acts as a unified command interface.

Features include:

Real-time autocomplete suggestions
Search history recall
Voice-based query input
Persistent query memory

Searches are automatically routed through the currently active realm.

Shortcut Matrix

Frequently used websites can be stored as shortcut cards.

Users can:

Add shortcuts
Edit shortcuts
Delete shortcuts
Launch websites directly from the dashboard

All shortcuts are stored locally in the browser.

Voice Command System

When supported by the browser:

Microphone button activates speech recognition
Spoken queries populate the search field
Search executes automatically after transcription

Browsers without speech recognition gracefully disable the feature.

Theme Architecture

Re:Search includes a dynamic theme engine.

Dark Mode (default)
Light Mode

Theme changes update:

Colors
Glow effects
Background gradients
Interface accents

without requiring page reloads.

Core Features
Dynamic Search Realms

Switch instantly between multiple search providers and custom engines.

Search Memory

Recent searches are stored locally and can be reused or removed at any time.

Predictive Suggestions

Live query suggestions are fetched while typing to improve search speed.

Voice Search

Speak naturally to perform searches without typing.

Custom Shortcuts

Create a personalized launchpad for frequently visited websites.

Persistent Storage

Realms, shortcuts, settings, and search history remain available across browser sessions through LocalStorage.

Accessibility Notes
Semantic HTML structure
Keyboard navigation support
Visible focus states
Accessible theme toggle controls
Search focus shortcut (/)
Escape key dismissal support
Touch-friendly mobile interactions
Run Locally
Open index.html in any modern browser.
Select a search realm.
Enter a query or use voice search.
Press Return With Results.
Manage shortcuts and custom realms through the interface controls.
Toggle between Dark and Light modes using the theme button.
Implementation Details

The application is built entirely without frameworks.

Key technologies include:

HTML5
CSS3
Vanilla JavaScript
LocalStorage API
Web Speech API
Google Suggest API (JSONP)
Dynamic DOM rendering

All customization data is stored locally, requiring no backend or database.

Design Philosophy

Re:Search is designed as a personal search gateway rather than a conventional search engine. Instead of indexing the web itself, it provides a customizable interface for navigating multiple search ecosystems while maintaining a fast, lightweight, and visually immersive experience.

Built for explorers who want to start searching from zero. 🚀
