# AI and Development Tool Ledger
*Brandon's comprehensive tracker for tools, resources, and project ideas*

---

## 🎯 Purpose
Track AI tools, development resources, installed software, and project ideas to maintain context across conversations and avoid redundant setup. This ledger serves as both a technical inventory and a project roadmap for Hacking the Homestead.

---

## 🤖 AI Tools in Use

### Primary AI Assistant
- **Claude (Anthropic)** - Current primary assistant
  - Model: Claude Sonnet 4.5
  - Capabilities: Web search, code execution, file creation, past chat memory
  - Switched from ChatGPT for enhanced capabilities
  - Used for: Development assistance, technical problem-solving, documentation

### AI-Powered Development Tools
- **Claude Code** - Command line tool for agentic coding
  - Status: Mentioned, not yet actively used
  - Potential use: Terminal-based development workflows

### Automation Tools Explored
- **Ralph Wiggum** - AI automation tool
  - Status: Discussed for educational workflows
  - Not yet implemented

- **Clawdbot** - AI automation tool
  - Status: Discussed for educational workflows
  - Not yet implemented

---

## 💻 Development Environment

### Hardware
- **MacBook with M3 chip**
  - Compatibility considerations for Docker/VM environments
  - Successfully resolved Kali Linux Docker issues

### Operating Systems & Environments
- **macOS** (primary)
- **Kali Linux** via Docker
  - Image: `kalilinux/kali-rolling:arm64`
  - Status: Successfully installed and configured
  - Use case: Cybersecurity education and penetration testing

### Terminal & Shell
- **Terminal.app** (Mac native)
  - Skill level: Building foundational skills
  - Recent progress: File navigation, basic commands, Firebase deployment
  - Pain points: Path confusion, tool installation complexity

### Code Editors & IDEs
- **TextEdit** 
  - Status: Used initially, learned limitations for code
  - Issue: Rich text format causes problems with code files

- **VS Code**
  - Status: Installed and learning
  - First real use: Firebase meal planner project
  - Benefits discovered: Syntax highlighting, file management

---

## 🔧 Development Tools & Frameworks

### Firebase Platform
- **Firebase CLI** (v15.4.0)
  - Installation method: `curl -sL https://firebase.tools | bash`
  - Status: Installed and configured
  - First project: "Weekly Grocery and Meal Plan"
  - Components used:
    - Realtime Database (active)
    - Hosting (deployed)
  - Skill level: Functional understanding - can set up and deploy, building toward custom features

### Web Technologies
- **HTML/CSS/JavaScript**
  - Philosophy: Simple, no build toolchain
  - Preference: Single-file solutions when possible
  - Recent project: Firebase meal planner PWA

### Version Control
- **Git/GitHub**
  - Organization: ParklandPackets-1
  - Use case: Progress tracking ("Boy Scout sash")
  - Philosophy: Repositories document learning progression, not seeking external validation
  - Notable repos:
    - search-cognitive-firewall (public)
    - amazon-cognitive-firewall (private)
    - Kali Docker setup guide

---

## 🛠️ Installed Tools & Packages

### System Tools
- **Docker**
  - Status: Installed and configured
  - Use case: Running Kali Linux on M3 Mac
  - Successfully resolved ARM64 compatibility issues

- **Homebrew**
  - Status: Likely installed (standard Mac package manager)
  - Use: Package management on macOS

### Python Environment
- **pip**
  - Status: Available
  - Note: M3 Mac requires `--break-system-packages` flag

### Node.js/JavaScript
- **npm**
  - Status: Available
  - Global packages location: `/home/claude/.npm-global`

---

## 📚 Learning Resources & Courses

### Active Learning
- **Linux Fundamentals Book**
  - Status: In progress
  - Goal: Master paths, commands, file systems
  - Priority: Foundation for all other technical work

- **Python Fundamentals Book**
  - Status: Queued after Linux book
  - Goal: Scripting and automation skills

### Cybersecurity Education
- **TryHackMe**
  - Status: Planned/explored
  - Use case: Structured pentesting education
  - Content opportunity: Document learning journey

- **Steganography Course**
  - Status: Attempted, struggled with tooling
  - Barrier: Docker/Kali setup issues (now resolved)
  - Potential: Return after Linux fundamentals

- **Penetration Testing**
  - Tools explored: Caido
  - Status: Early exploration stage

### Explored but Not Adopted
- **Scammer Honeypot Operations**
  - Interest level: High
  - Status: Conceptual exploration
  - Alignment: Rural cybersecurity education mission

---

## 🎨 Projects & Tools Built

### Cognitive Firewall Suite

#### Google Cognitive Firewall (GCF)
- **Repository**: search-cognitive-firewall (public)
- **Status**: Shipped and functional
- **Technology**: Userscript (Tampermonkey/Violentmonkey)
- **Purpose**: Subtractive SERP cleanup for Google Search
- **Features**:
  - Session-only persistence
  - User-controlled toggle
  - CSS class approach for hiding elements
  - Text-only search experience
- **Philosophy**: Reduce cognitive noise, preserve user agency
- **Achievement**: Successfully cracked Google SERP structure

#### Amazon Cognitive Firewall (ACF)
- **Repository**: amazon-cognitive-firewall (private)
- **Status**: Shipped and functional
- **Technology**: Userscript
- **Purpose**: Reduce Amazon clutter and recommendation pressure
- **Features**:
  - Checkout-safe (paranoid protection)
  - Mode switching (balanced/minimal)
  - Intent-aware behavior (home/search/product pages)
- **Safety**: Multiple layers to avoid breaking purchase flows

### Idea Management

#### Idea Ledger
- **Status**: Built and deployed
- **Technology**: HTML/CSS/JS (single file)
- **Aesthetic**: Matrix/terminal theme
- **Purpose**: Capture project overflow to manage cognitive load
- **Features**:
  - Quick idea capture
  - Status tracking (Inbox → Working → Done)
  - Category tagging
  - JSON export
- **Philosophy**: Subtractive engineering - manage ideas before they cause overwhelm

### Family & Practical Tools

#### Firebase Family Meal Planner
- **Repository**: Weekly Grocery and Meal Plan
- **Status**: Deployed and in family use
- **Technology**: Firebase Realtime Database + PWA
- **Purpose**: Real-time collaborative meal planning and grocery management
- **Features**:
  - Real-time sync across 6 family members
  - Category-organized grocery list
  - Weekly meal planning
  - Mobile-optimized (iOS home screen install)
  - Offline capable
- **Hosting**: https://weekly-grocery-and-meal-plan.web.app
- **Learning outcomes**: 
  - Firebase setup and deployment
  - Real-time database concepts
  - Terminal proficiency gains
  - VS Code adoption
  - Understanding when tools fit (vs. forcing solutions)

---

## 💡 Project Ideas (Queued)

### High-Priority Novel Projects

#### Color-Coded Steganographic IoT Automation System
- **Status**: Concept validated, needs skill development
- **Novelty**: Legitimately novel - no existing documentation of this combo
- **Core Concept**: 
  - Visual signal protocol using color-tinted steganographic images
  - IoT sensors read colors and trigger automated workflows
  - Integration with mesh networks (Meshtastic/LoRa)
  - Multi-layer communication: covert (stego) + overt (color) + automated (sensor)
- **Components Needed**:
  - Steganography (embedding/extraction)
  - Color sensors (TCS34725 or similar)
  - ESP32/Arduino/Raspberry Pi controllers
  - Mesh networking protocols
  - Workflow automation logic
- **Use Cases**:
  - Agricultural automation triggered by community alerts
  - Security status coordination across properties
  - Emergency protocols with automated response
  - Supply chain/market status signaling
- **Prerequisites**:
  - Solid Linux fundamentals
  - Python proficiency
  - IoT hardware experience
  - Mesh networking knowledge
- **Timeline**: 3-6 months of foundational learning
- **Impact Potential**: Foundational tool for Hacking the Homestead education platform

### Mesh Networking Projects
- **Technologies**: LoRa, Meshtastic
- **Status**: Explored, documented interest
- **Alignment**: Rural emergency communications, homestead coordination
- **Content opportunities**:
  - "Building a homestead mesh network for $200"
  - "Emergency comms when the grid goes down"
  - "Coordinating with neighbors without cell service"

### IoT & Hardware
- **Raspberry Pi Projects**
  - Status: Hardware available, multiple use cases identified
  - Use cases: Home lab, network monitoring, mesh nodes
  
- **Arduino/ESP32**
  - Status: Discussed, not yet hands-on
  - Interest: Sensor integration, automation

- **Pi-hole Tutorial**
  - Status: Planned
  - Use case: Network security for homesteads
  - Content opportunity: First defensive demo

---

## 🎓 Hacking the Homestead Platform

### Mission
Educational platform teaching rural communities practical cybersecurity, technology sovereignty, and resilient living using accessible technologies.

### Core Concerns
- Rural cybersecurity vulnerabilities
- Suicide rates in rural communities
- Trend toward proprietary cloud services eliminating open source access
- Digital platform manipulation
- Need for cognitive sovereignty tools

### Content Pillars

#### 1. Homestead Tech Integration
- IoT projects with kids
- Practical applications of technology on rural properties
- DIY solutions with Raspberry Pi, Arduino

#### 2. Rural Cybersecurity
- Accessible security education for underserved communities
- Lightweight, remotely accessible tools
- Making advanced concepts understandable

#### 3. Learning Journey Documentation
- Terminal and development skills
- "Learning in public" approach
- Demonstrating authentic struggle and growth

#### 4. Community Building
- Discord/Forum + newsletter planned
- Knowledge sharing platform
- Mental health support through making

### Monetization Strategy (Planned)
- **Content**: YouTube + blog (ad revenue, sponsorships)
- **Products**: Open source tools with premium support
- **Consulting**: Local homestead/farm security
- **Courses**: Online workshops and training
- **Community**: Membership tiers, Patreon

### Business Model Philosophy
- Local-first approach (build trust in community)
- Own the infrastructure (self-hosted when possible)
- Platform independence (antifragile to algorithm changes)
- Multiple revenue streams
- Open source with sustainable support model

---

## 🧠 Working Style & Preferences

### Cognitive Approach
- **Neurodivergent considerations**: 
  - Prefer methodical, batched learning
  - Manage cognitive overload when working with multiple technologies
  - "Boy Scout sash" approach to GitHub (personal progress tracking)

### Engineering Philosophy
- **Subtractive Engineering**: Focus on removing harmful/distracting elements vs. adding features
- **Local-first**: No telemetry, no network interception, user privacy paramount
- **Fail-open design**: If tools break, underlying systems remain usable
- **Fork-friendly**: Open source, well-documented, easy to modify

### Project Management
- **Resource checks FIRST**: Always verify tool availability before starting
- **Batch installation**: Avoid mid-project installation breaks
- **Avoid complexity**: Prefer simple solutions over complex toolchains
- **Documentation during building**: Capture process for content and teaching

### Pain Points & Preferences
- Mac M3 compounds installation issues
- Gets frustrated with tool configuration → goes to hang with chickens (valid coping)
- Prefers clear, direct instructions matched to actual skill level
- Values honest assessment over encouragement platitudes

---

## 🎯 Current Focus (January 2026)

### Immediate Priorities
1. **Linux Fundamentals Book** - Foundation for all technical work
2. **Firebase Meal Planner** - Family tool in active use, potential for feature expansion
3. **Cognitive Firewall Maintenance** - Keep tools functional as platforms change
4. **Docker/Kali Environment** - Now resolved, ready for cybersecurity education

### Skill-Building Goals
- Terminal proficiency (paths, commands, file operations)
- Python scripting (after Linux foundation)
- Firebase/real-time database concepts
- IoT hardware basics (ESP32, sensors, wiring)

### Content Development
- Document learning journey for Hacking the Homestead
- Build portfolio showing progression
- Create tutorials from actual building process

### Mindset Shift Achievement
- Successfully avoided jumping into complex multi-technology projects
- Focused on systematic skill-building
- Completed and shipped practical tools (meal planner, cognitive firewalls)
- Demonstrated technical intuition (Firebase problem-solving without coding background)

---

## 🔄 Pattern Recognition

### What Works
- Single-file HTML/CSS/JS solutions
- Clear problem definition before building
- Resource checks before starting
- Building tools for actual personal use
- Documentation as learning progresses
- Subtractive approach to features

### What Doesn't Work
- Complex toolchains and build systems
- Jumping between multiple new technologies simultaneously
- Mid-project installation surprises
- Assuming tool availability without checking
- Solutions looking for problems

### Growth Indicators
- Successfully deployed production Firebase app
- Resolved M3 Mac Docker compatibility independently (with guidance)
- Shipped multiple cognitive firewall tools
- Developed technical intuition (knowing when tools fit problems)
- Building Terminal comfort through real projects
- Transitioned from TextEdit to VS Code organically

---

## 📝 Notes for Future Sessions

### Context to Maintain
- Always check tool availability before suggesting new tech
- Mac M3 ARM64 considerations for Docker/VMs
- Neurodivergent-friendly pacing and batching
- Subtractive engineering philosophy
- Local-first, privacy-respecting approach
- GitHub as learning documentation, not social validation

### Communication Preferences
- Direct, honest feedback preferred
- Match instructions to actual skill level
- Avoid overwhelming with multiple questions
- Resource checks before technical work
- Step-by-step with clear "what YOU do" instructions

### Long-Term Vision Support
- Every tool should serve Hacking the Homestead mission
- Document building process for teaching content
- Prioritize rural community impact
- Balance learning progression with practical shipping

---

## 🚀 Success Metrics

### Technical Achievements
- ✅ Resolved M3 Mac Docker/Kali setup
- ✅ Deployed production Firebase app
- ✅ Shipped Google cognitive firewall
- ✅ Shipped Amazon cognitive firewall
- ✅ Built and deployed idea ledger
- ✅ Basic Terminal proficiency (navigation, file ops, deployments)
- ✅ VS Code adoption

### Learning Progression
- ✅ Understanding when tools fit problems (vs. forcing solutions)
- ✅ Firebase concepts (real-time database, hosting, deployment)
- ✅ Git/GitHub workflow comfort
- ✅ Single-file PWA development
- 🔄 In Progress: Linux fundamentals
- 📋 Queued: Python fundamentals
- 📋 Queued: IoT hardware basics

### Platform Development
- ✅ Defined Hacking the Homestead mission clearly
- ✅ Established subtractive engineering philosophy
- ✅ Created cognitive firewall tool suite
- 🔄 Building content through documented learning
- 📋 Future: YouTube channel, blog, community platform

---

## 🔗 Repository Links
- **GitHub Organization**: [ParklandPackets-1](https://github.com/ParklandPackets-1)
- **Public Repos**: 
  - search-cognitive-firewall
  - (Other public repos as created)
- **Private Repos**: 
  - amazon-cognitive-firewall

---

## 📅 Last Updated
January 26, 2026

---

## 🎓 Key Insights

> "GitHub is my Boy Scout sash where repositories document learning progression rather than seeking external validation."

> "Subtractive engineering - focusing on removing harmful or distracting elements rather than adding features."

> "Your learning journey IS content. Record it, share it."

> "One stone, five birds: A tool you need, content for your channel, open source contribution, Terminal practice, demonstration of teaching style."

---

*This ledger evolves with each conversation and project. It serves as both memory and roadmap.*
