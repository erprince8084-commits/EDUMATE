# EDUMATE
AI-Assisted Vernacular Pedagogy &amp; Real-Time Translation Tool for Mother Tongue-Based Primary Education

# 🌱 Edumate — AI-Powered Mother Tongue Learning Platform

> **Empowering tribal education through AI-powered multilingual learning**

Edumate is an AI-powered educational platform designed to support **Mother Tongue-Based Multilingual Education (MTB-MLE)** in tribal primary schools.

The platform helps teachers and students overcome language barriers by converting educational content from **Hindi into tribal languages such as Mundari and Santhali**, with support for text, voice, learning activities, and bilingual educational resources.

---

## 🎯 Problem Statement

Many tribal primary schools face a significant language barrier:

* Teachers may primarily use Hindi while students are more comfortable with their native tribal language.
* Educational resources in tribal languages are limited.
* Teachers often have to manually translate classroom content.
* Existing translation tools may not be optimized for local tribal languages.
* Lack of audio-based resources makes learning difficult for early-grade students.
* Low-resource environments require solutions that can work with limited internet connectivity.

These challenges can affect classroom communication, comprehension, and student engagement.

---

## 💡 Our Solution

**Edumate** provides a single platform where teachers can create and use multilingual educational content.

### Core workflow

```text
Hindi Educational Content
          ↓
     AI Translation
          ↓
  Tribal Language Output
   ┌──────┼──────┐
   ↓      ↓      ↓
  Text   Audio  Activities
   ↓      ↓      ↓
        Students
```

The system is designed around a **Hindi → Tribal Language** workflow and can be extended to support additional Indian languages.

---

# 🚀 Key Features

### 🌐 Multilingual Translation

Translate educational content from Hindi into supported tribal languages.

Currently targeted languages include:

* 🟢 Mundari
* 🟢 Santhali

The architecture is designed so that additional languages can be added later.

---

### 🎙️ Voice-Based Learning

Edumate is designed to support:

* Voice input
* Speech-to-text
* Text-to-speech
* Educational audio generation
* Voice-based interaction

This allows students to learn beyond traditional text-based content.

---

### 📚 Bilingual Learning Content

Educational content can be presented in both:

**Hindi + Tribal Language**

This helps teachers explain concepts while allowing students to learn using their familiar language.

---

### 📝 AI-Generated Learning Material

The platform can be extended to generate:

* Lesson content
* Classroom activities
* Practice questions
* Assessment prompts
* Bilingual worksheets
* Learning exercises

---

### 🧑‍🏫 Teacher Support

Teachers can use Edumate to:

* Translate classroom material
* Generate learning resources
* Access bilingual content
* Use audio-assisted teaching
* Prepare activities for students

---

### 👨‍🎓 Student Learning

Students can use the platform for:

* Vocabulary learning
* Flashcards
* Listening practice
* Reading practice
* Voice-based learning
* Interactive educational activities

---

### 📱 Low-Resource Friendly Architecture

The project is designed with low-end Android devices and limited-connectivity environments in mind.

Future optimization includes:

* Lightweight AI models
* ONNX Runtime / TensorFlow Lite
* Quantized models
* Local language packs
* Offline translation
* Local educational content

---

# 🏗️ Technical Architecture

```text
                    ┌─────────────────────┐
                    │      Edumate App    │
                    │    Flutter Frontend │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │   Application Layer │
                    │  Translation / AI   │
                    └──────────┬──────────┘
                               │
              ┌────────────────┼────────────────┐
              ▼                ▼                ▼
       ┌────────────┐   ┌────────────┐   ┌────────────┐
       │ Translation│   │    Voice   │   │ Curriculum │
       │    Engine  │   │   Engine   │   │   Engine   │
       └─────┬──────┘   └─────┬──────┘   └─────┬──────┘
             │                │                │
             └────────────────┼────────────────┘
                              ▼
                    ┌─────────────────────┐
                    │ Language / Content  │
                    │      Database       │
                    └─────────────────────┘
```

---

# 🛠️ Technology Stack

## Frontend

* **Flutter**
* **Dart**
* Material UI

## AI / Machine Learning

* Python
* Transformer-based NLP
* Multilingual Translation Models
* Indic NLP
* Speech Recognition
* Text-to-Speech
* ONNX Runtime / TensorFlow Lite

## Backend

* FastAPI
* Python
* REST APIs

## Database

* SQLite
* Structured language datasets
* Curriculum database
* Language glossary

## AI Retrieval

* FAISS
* Retrieval-Augmented Generation (RAG)

## Development Tools

* VS Code
* Git
* GitHub
* Android Studio
* Flutter SDK

---

# 📂 Project Structure

```text
edumate/
│
├── android/
├── ios/
├── lib/
│   ├── main.dart
│   ├── screens/
│   ├── widgets/
│   ├── services/
│   ├── models/
│   └── data/
│
├── assets/
│   ├── images/
│   ├── audio/
│   └── datasets/
│
├── test/
│
├── pubspec.yaml
├── README.md
└── .gitignore
```

> The exact folder structure may evolve as new modules and AI features are integrated.

---

# 🔄 Application Workflow

### Step 1 — Select Language

The teacher/student selects the required tribal language.

### Step 2 — Enter Content

Educational content can be entered in Hindi using text or voice.

### Step 3 — AI Processing

The system processes the input using the translation and language-processing pipeline.

### Step 4 — Translation

Hindi content is converted into the selected tribal language.

### Step 5 — Audio Generation

The translated content can be converted into speech.

### Step 6 — Learning

Students can read, listen, practice, and interact with the generated content.

---

# 🧪 Example

### Input

**Hindi:**

> यह एक पेड़ है।

### Output

**Mundari:**

> [Mundari translation]

### Learning Output

```text
┌───────────────────────────────┐
│ Hindi                         │
│ यह एक पेड़ है।                │
├───────────────────────────────┤
│ Tribal Language               │
│ Translated Content            │
├───────────────────────────────┤
│ 🔊 Listen                     │
│ 📝 Practice                   │
│ 🎯 Quiz                       │
└───────────────────────────────┘
```

---

# 🎓 Educational Focus

Edumate is particularly focused on **Foundational Literacy and Numeracy (FLN)** and primary-level educational content.

The platform can support:

* Basic vocabulary
* Numbers
* Letters
* Reading
* Writing
* Classroom instructions
* Simple mathematics
* Environmental studies
* Stories
* Activities
* Assessments

---

# 🌍 Target Users

### 👩‍🏫 Teachers

Teachers can use Edumate to create and deliver multilingual classroom content.

### 👧 Students

Students can learn concepts using their familiar mother tongue.

### 🏫 Schools

Schools can use the platform to support multilingual classroom environments.

### 🏛️ Education Departments

The platform can potentially support large-scale multilingual education initiatives.

---

# 📈 Future Roadmap

```text
Phase 1
   ↓
Hindi → One Tribal Language
   ↓
Text Translation
   ↓
Basic Learning Content
   ↓
Voice Support
   ↓
Multiple Tribal Languages
   ↓
Offline AI
   ↓
District-Level Deployment
   ↓
State-Level Deployment
```

### Planned Improvements

* [ ] Advanced Hindi → Mundari translation
* [ ] Hindi → Santhali translation
* [ ] Real-time voice-to-voice translation
* [ ] Offline AI inference
* [ ] AI-generated worksheets
* [ ] AI-generated lesson plans
* [ ] Native-speaker validation system
* [ ] Teacher dashboard
* [ ] Student progress tracking
* [ ] More tribal languages
* [ ] Lightweight models for low-end Android devices

---

# 🔐 Data & Privacy

Edumate is designed with educational data privacy in mind.

The long-term architecture aims to:

* Minimize unnecessary data collection
* Support local/offline processing where possible
* Keep educational content securely stored
* Avoid unnecessary transmission of student information

---

# ⚙️ Getting Started

## Prerequisites

Make sure you have installed:

* Flutter SDK
* Dart
* Android Studio
* Android SDK
* Git

Check Flutter installation:

```bash
flutter --version
```

---

## Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/edumate.git
```

Move into the project:

```bash
cd edumate
```

---

## Install Dependencies

```bash
flutter pub get
```

---

## Run the Application

Connect an Android device or start an Android emulator.

Then run:

```bash
flutter run
```

---

# 🧪 Testing

Run Flutter tests using:

```bash
flutter test
```

Check the project environment:

```bash
flutter doctor
```

---

# 🤝 Team

**Edumate** is developed as a Smart India Hackathon project.

### Team

* Team Lead / Developer
* AI / ML
* Flutter Development
* UI/UX
* Research & Documentation
* Testing & Presentation

---

# 🏆 Smart India Hackathon

Edumate is developed as a prototype addressing the challenge of **Mother Tongue-Based Multilingual Education (MTB-MLE)** for tribal primary schools.

The project focuses on using AI and multilingual technology to make educational resources more accessible to students and teachers.

---

# 📌 Project Status

🚧 **Prototype / Under Development**

The current version focuses on demonstrating the core Edumate concept and multilingual educational workflow.

More AI, voice, offline, and curriculum-generation capabilities are being developed incrementally.

---

# 📜 License

This project is currently developed for educational and hackathon purposes.

License information will be added as the project moves toward public release.

---

## ⭐ Support the Project

If you find **Edumate** useful or interesting:

⭐ Star the repository
🍴 Fork the repository
🐛 Report issues
💡 Suggest improvements
🤝 Contribute to the project

---

### 🌱 Edumate

**Learn in your language. Teach without language barriers.**

# 📦 Repository Contents

The Edumate repository contains the complete Flutter project along with the supporting documentation, assets, AI/NLP resources, and platform-specific project files.

### 📱 Flutter Platform Files

* `android.zip` — Android platform configuration and native Android project files
* `ios.zip` — iOS platform configuration and native iOS project files
* `web.zip` — Web platform configuration
* `macos.zip` — macOS platform configuration
* `windows.zip` — Windows platform configuration

### 💻 Application Source Code

* `lib.zip` — Main Flutter/Dart application source code, including screens, widgets, services, models, and application logic
* `test.zip` — Application test files

### 📦 Project Configuration

* `pubspec.yaml.zip` — Flutter project configuration and dependency definitions
* `pubspec.lock.zip` — Locked dependency versions
* `analysis_options.yaml.zip` — Dart/Flutter code analysis and linting configuration
* `edumate.iml.zip` — IDE/project configuration

### 🤖 AI / NLP Documentation

* `NLP_LAYER.md.zip` — Documentation related to the Natural Language Processing layer
* `VOICE_PIPELINE.md.zip` — Documentation for the voice-processing pipeline

### 🎨 Assets & Branding

* `assets.zip` — Application assets such as images, audio, datasets, and other resources

Branding assets:

```text
branding/
├── edumate_icon.png
├── edumate_icon_android.png
└── edumate_icon_foreground.png
```

These files contain the Edumate application branding and Android app icon resources.

### 📄 Documentation

* `README.md.zip` — Project documentation and setup information

---

## 📁 Repository Overview

```text
edumate/
│
├── android.zip
├── ios.zip
├── lib.zip
├── test.zip
├── web.zip
├── macos.zip
├── windows.zip
│
├── pubspec.yaml.zip
├── pubspec.lock.zip
├── analysis_options.yaml.zip
├── edumate.iml.zip
│
├── assets.zip
│
├── branding/
│   ├── edumate_icon.png
│   ├── edumate_icon_android.png
│   └── edumate_icon_foreground.png
│
├── NLP_LAYER.md.zip
├── VOICE_PIPELINE.md.zip
└── README.md.zip
```

> **Note:** The `.zip` files in this repository are archived versions of the corresponding Flutter project components. Extract the required archive before using or modifying its contents.



