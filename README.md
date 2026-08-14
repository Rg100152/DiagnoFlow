# 🏥 DiagnoFlow - AI Health Assistant & Predictive Triage System

An intelligent healthcare triage assistant that combines conversational AI with predictive analytics to provide real-time health risk assessment and actionable care recommendations.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Healthcare](https://img.shields.io/badge/Healthcare-AI_Triage-008080?style=for-the-badge&logo=healthcare&logoColor=white)
![HIPAA](https://img.shields.io/badge/HIPAA-Compliant-9CAF88?style=for-the-badge&logo=security&logoColor=white)

## 📋 Table of Contents
- [Overview](#-overview)
- [Key Features](#-key-features)
- [Live Demo](#-live-demo)
- [Technology Stack](#-technology-stack)
- [Design Philosophy](#-design-philosophy)
- [How It Works](#-how-it-works)
- [Installation](#-installation)
- [Usage Guide](#-usage-guide)
- [Risk Assessment System](#-risk-assessment-system)
- [Visual Feedback](#-visual-feedback)
- [Project Structure](#-project-structure)
- [Security & Compliance](#-security--compliance)
- [Contributing](#-contributing)
- [Future Enhancements](#-future-enhancements)
- [License](#-license)
- [Author](#-author)
- [Disclaimer](#-disclaimer)

## 🎯 Overview

**DiagnoFlow** is a revolutionary AI-powered health triage assistant that provides preliminary medical assessment through natural conversation. The system uses advanced algorithms to analyze symptoms, assess risk levels, and provide actionable healthcare recommendations.

The platform features:
- **Conversational AI** - Natural language symptom assessment
- **Predictive Analytics** - Real-time risk evaluation
- **Visual Risk Indicators** - 3D health orb with dynamic states
- **Actionable Recommendations** - Immediate care guidance
- **Health Passport** - Portable health records

## ✨ Key Features

### Core Functionality
- 💬 **Agentic Triage** - Conversational symptom analysis
- 🎯 **Risk Assessment** - Real-time health risk evaluation
- 📊 **Confidence Metrics** - Diagnostic confidence tracking
- 🚨 **Emergency Detection** - Critical condition identification
- 📄 **Health Passport** - Portable medical records
- 🔒 **HIPAA Compliance** - Patient data protection

### Visual & UX Excellence
- 🌸 **Geometric Lotus Logo** - Animated brand identity
- 🔮 **3D Health Orb** - Dynamic risk visualization
- 📈 **Confidence Flow** - Liquid animation for diagnostics
- 💫 **Breathing Input** - Calming interaction design
- ⚡ **Haptic Feedback** - Visual alerts for high-risk cases
- 🎨 **Neuro-Inclusive Design** - Low eye strain color palette

## 🚀 Live Demo

Experience DiagnoFlow: [Live Demo](https://rg100152.github.io/diagnoflow/)

## 🛠️ Technology Stack

| Technology | Purpose |
|------------|---------|
| HTML5 | Structure & Semantics |
| CSS3 | Styling, Animations, 3D Effects |
| JavaScript ES6+ | Logic, AI Simulation |
| Font Awesome 6.4 | Icons |
| Google Fonts | Nunito Typography |
| Web Speech API | (Planned) Voice Input |
| Infermedica API | (Simulated) Symptom Analysis |

## 🎨 Design Philosophy

### Neuro-Inclusive Color Palette
```css
--teal: #008080;          /* Trust & Stability */
--soft-coral: #FF6F61;    /* Warmth & Urgency */
--sage-green: #9CAF88;    /* Health & Positivity */
--warm-sand: #F4E4D5;     /* Low Eye Strain */
--muted-indigo: #4B5563;  /* Readability */
--amber: #F59E0B;         /* Caution & Monitoring */
```

### Design Principles
- **Calm-First Approach** - Reduces anxiety during health assessment
- **Progressive Disclosure** - Information revealed gradually
- **Emotional Intelligence** - Empathetic responses
- **Visual Hierarchy** - Clear risk indication
- **Accessibility** - Inclusive design for all users

## 🔬 How It Works

### System Architecture
```
User Input → NLP Processing → Symptom Analysis → Risk Assessment → Visual Feedback → Actionable Output
```

### Triage Flow
1. **Initial Contact** - AI greets and listens
2. **Symptom Collection** - Structured questioning
3. **Risk Evaluation** - Pattern matching & analysis
4. **Confidence Building** - Progressive diagnostic certainty
5. **Action Generation** - Personalized recommendations

## 📦 Installation

### Prerequisites
- Modern web browser
- Internet connection for CDN resources

### Setup Steps

1. **Clone Repository**
   ```bash
   git clone https://github.com/Rg100152/diagnoflow.git
   ```

2. **Navigate to Directory**
   ```bash
   cd diagnoflow
   ```

3. **Run Application**
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve
   
   # Using VS Code
   # Install Live Server and click "Go Live"
   ```

4. **Access Application**
   - Open `http://localhost:8000`

## 🎮 Usage Guide

### Starting Assessment
1. **Read Greeting** - AI introduces itself
2. **Type Symptoms** - Describe how you're feeling
3. **Answer Questions** - Respond to follow-up inquiries
4. **Monitor Risk Level** - Watch the health orb change
5. **Review Recommendations** - Follow action steps

### Understanding Indicators

| Indicator | State | Meaning |
|-----------|-------|---------|
| 🟢 Green Orb | Stable | Low risk detected |
| 🟡 Amber Orb | Monitoring | Moderate concern |
| 🔴 Red Orb | Critical | Immediate action needed |
| Confidence % | 30-98% | Diagnostic certainty |
| Action Cards | Visible | Care recommendations |

### Example Conversation Flow
```
User: "I have chest pain"
AI: "Does the pain radiate to your jaw or left arm?"
User: "Yes, it does"
AI: "Are you experiencing shortness of breath?"
User: "Yes"
AI: "HIGH RISK DETECTED - Please seek immediate medical attention"
```

## 🏥 Risk Assessment System

### Risk Levels
- **Stable** (Green) - No immediate concern
- **Monitoring** (Amber) - Requires observation
- **High Risk** (Red) - Emergency intervention

### Assessment Factors
- Symptom severity
- Pain radiation patterns
- Associated symptoms
- Duration of symptoms
- Patient history

## 📊 Visual Feedback System

### Health Orb States
```css
/* Stable State */
background: radial-gradient(circle at 30% 30%, #e0f2cd, var(--sage-green));

/* Monitoring State */
background: radial-gradient(circle at 30% 30%, #ffeaa7, var(--amber));

/* Critical State */
background: radial-gradient(circle at 30% 30%, #ff9a9e, var(--soft-coral));
```

### Confidence Flow Animation
- **30% Initial** - Uncertain, collecting data
- **65% Developing** - Pattern recognition
- **80% Strong** - Clear diagnosis emerging
- **98% Confirmed** - High confidence diagnosis

## 📁 Project Structure

```
diagnoflow/
│
├── index.html              # Main application
├── README.md               # Documentation
│
├── assets/
│   ├── css/
│   │   ├── main.css       # Core styles
│   │   └── animations.css # Animations
│   ├── js/
│   │   ├── triage.js     # Assessment logic
│   │   ├── ui.js         # UI updates
│   │   └── api.js        # API integration
│   └── images/
│       └── logo.svg      # Brand assets
│
└── docs/
    ├── medical-guidelines.md
    └── api-documentation.md
```

## 🔒 Security & Compliance

### HIPAA Compliance Features
- **Data Encryption** - Secure symptom transmission
- **Privacy Protection** - No data persistence
- **Access Control** - Authorized personnel only
- **Audit Trail** - Complete interaction history

### Security Measures
- **Client-Side Processing** - Data stays on device
- **No Cookies** - Zero tracking
- **Session Isolation** - Independent assessments
- **Secure Communication** - HTTPS ready

## 🤝 Contributing

We welcome contributions! Follow these steps:

1. **Fork Repository**
2. **Create Feature Branch**
   ```bash
   git checkout -b feature/NewFeature
   ```
3. **Commit Changes**
   ```bash
   git commit -m 'Add NewFeature'
   ```
4. **Push Branch**
   ```bash
   git push origin feature/NewFeature
   ```
5. **Open Pull Request**

### Contribution Areas
- Medical knowledge base expansion
- API integration (Infermedica, Mayo Clinic)
- Voice recognition implementation
- Accessibility improvements
- Testing & validation

## 🔮 Future Enhancements

### Phase 1 - Core Improvements
- [ ] **Real API Integration** - Connect to Infermedica
- [ ] **Voice Input** - Web Speech API integration
- [ ] **Multi-language Support** - International expansion
- [ ] **Symptom Database** - Comprehensive medical library

### Phase 2 - Advanced Features
- [ ] **Machine Learning** - Personalized risk assessment
- [ ] **Wearable Integration** - Real-time vitals monitoring
- [ ] **Telemedicine** - Direct doctor consultation
- [ ] **EHR Integration** - Electronic health records

### Phase 3 - Ecosystem
- [ ] **Mobile App** - iOS & Android
- [ ] **Family Profiles** - Multi-user support
- [ ] **Insurance Integration** - Claims processing
- [ ] **Pharmacy Connection** - Prescription management

## 📱 Browser Support

| Browser | Support | Performance |
|---------|---------|-------------|
| Chrome 90+ | ✅ Full | ⚡ Excellent |
| Edge 90+ | ✅ Full | ⚡ Excellent |
| Firefox 88+ | ✅ Full | ⚡ Excellent |
| Safari 14+ | ✅ Full | ⚡ Good |
| Opera 76+ | ✅ Full | ⚡ Good |

## ⚠️ Disclaimer

**IMPORTANT**: DiagnoFlow is a demonstration project and should NOT be used for actual medical diagnosis. Always consult with qualified healthcare professionals for medical advice. In case of emergency, call your local emergency services immediately.

## 📄 License

This project is licensed under the MIT License - see [LICENSE](LICENSE) file.

## 👨‍💻 Author

**Ritesh Gupta**

- GitHub: [@Rg100152](https://github.com/Rg100152)
- Repository: [DiagnoFlow](https://github.com/Rg100152/diagnoflow)
- LinkedIn: [Ritesh Gupta](https://linkedin.com/in/ritesh-gupta)

## 🙏 Acknowledgments

- [Infermedica](https://infermedica.com/) - Medical AI inspiration
- [Mayo Clinic](https://www.mayoclinic.org/) - Medical guidelines
- [Font Awesome](https://fontawesome.com/) - Icons
- [Google Fonts](https://fonts.google.com/) - Typography
- Healthcare Professionals - Domain expertise

## 📈 Project Stats

![GitHub stars](https://img.shields.io/github/stars/Rg100152/diagnoflow)
![GitHub forks](https://img.shields.io/github/forks/Rg100152/diagnoflow)
![GitHub issues](https://img.shields.io/github/issues/Rg100152/diagnoflow)
![GitHub license](https://img.shields.io/github/license/Rg100152/diagnoflow)

---

<div align="center">
  <strong>🏥 DiagnoFlow - Intelligent Healthcare Triage</strong>
  
  <sub>Built with ❤️ for accessible healthcare</sub>
  
  <br>
  
  ⭐ Star this repo if you find it useful!
</div>
