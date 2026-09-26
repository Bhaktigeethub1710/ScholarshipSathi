# 🎓 ScholarshipSathi

### One Platform. Every Scholarship Journey. Simplified.

<p align="center">

**A unified mobile-first scholarship experience designed to simplify scholarship discovery, eligibility, verification and tracking.**

</p>

---

## 🌟 What is ScholarshipSathi?

Students often have to navigate multiple scholarship portals, repeatedly submit documents, manually check eligibility and track applications across different systems.

**ScholarshipSathi brings the important parts of this journey together in one simple mobile application.**

The prototype focuses on creating a student-friendly experience where students can:

🎯 Discover relevant scholarships  
📊 Understand their eligibility  
📄 Manage scholarship documents  
🔐 Reuse verified documents  
📌 Track applications  
💰 Monitor scholarship payments  
🔔 Receive important updates  
🤖 Get assistance from JAGO

---

## ✨ Core Features

### 🎯 1. Scholarship Eligibility Radar

ScholarshipSathi analyses the student's profile and highlights scholarship opportunities that may match their eligibility.

Instead of making students search through multiple schemes, the application brings relevant opportunities directly to the student.

**Example:**

- 🟢 **Post-Matric Scholarship** — 92% profile match
- 🟡 **Top Class Scholarship** — 68% profile match

---

### 🔐 2. Zero-Reupload Verification

#### Verify once. Reuse across eligible scholarships.

Once a document has been verified, the student can see its verification status and reuse it across eligible scholarship applications.

| Document | Status | Reuse |
|---|---|---|
| ST / Caste Certificate | 🟢 Verified | ♻ Reusable |
| Academic Record | 🟢 Verified | ♻ Reusable |
| Income Certificate | 🟡 Pending | ⚠ Action Required |

This reduces repetitive document submission and creates a smoother scholarship application experience.

---

### 📊 3. Scholarship 360

A consolidated view of the student's scholarship journey.

| Active | Documents | Received |
|---|---|---|
| **2** | **8/9 Verified** | **₹24K** |

Students can quickly understand:

- Active scholarship applications
- Document verification progress
- Scholarship amounts received
- Recent scholarship activity

---

### 🤖 4. Meet JAGO

#### Your personal scholarship assistant

JAGO is designed to help students understand their scholarship journey.

Students can ask about:

- 🎯 Eligibility
- 📄 Documents
- 📌 Application status
- 💰 Payments
- 🔔 Important updates

**Example interaction:**

> 🤖 **JAGO**
>
> Hi RAM! 👋
>
> 🎯 2 scholarship schemes matched  
> 📄 1 document needs attention  
> 💰 Latest payment has been sanctioned
>
> What would you like to know?

---

### 📄 5. Unified Documents

ScholarshipSathi provides a single place to understand document verification.

Each document can have a clear status:

- 🟢 **Verified**
- 🟡 **Pending**
- 🔴 **Action Required**

Students can also see whether a verified document can be reused across scholarship applications.

---

### 🔔 6. Unified Updates

Students can view important scholarship events in one place.

Examples:

- Application verified
- Documents verified
- Scholarship sanctioned
- Payment updates
- Action-required notifications

---

### 👤 7. Unified Student Profile

The student profile brings relevant information together.

#### Personal Information

Name, mobile number and email.

#### Academic Information

Institution, course and academic year.

#### Scholarship Profile

Relevant scholarship information and verification status.

#### Connected Services

A unified view of connected information sources.

---

# 🧭 Application Flow

```text
                    🎓 Welcome
                         │
                         ▼
                🔐 Login / Register
                         │
                         ▼
                  📱 OTP Verification
                         │
                         ▼
                     🏠 Home
                         │
          ┌──────────────┼──────────────┐
          ▼              ▼              ▼
     🎯 Eligibility   📄 Documents   🔔 Updates
         Radar       Zero-Reupload
          │              │
          ▼              ▼
     Eligibility     Document
       Details        Details
                         │
                         ▼
                       🤖 JAGO

---

🏗️ Project Architecture

```text
        

The current repository is a **static but interactive Android prototype** built to demonstrate the complete student experience.

```text
ScholarshipSathi/
│
├── app/
│   └── src/
│       └── main/
│           ├── java/
│           │   └── com/
│           │       └── example/
│           │           └── scholarshipsathi/
│           │               │
│           │               ├── MainActivity.kt
│           │               │
│           │               └── ui/
│           │                   ├── navigation/
│           │                   │
│           │                   ├── screens/
│           │                   │   ├── WelcomeScreen.kt
│           │                   │   ├── LoginScreen.kt
│           │                   │   ├── OtpScreen.kt
│           │                   │   ├── HomeScreen.kt
│           │                   │   ├── ScholarshipsScreen.kt
│           │                   │   ├── EligibilityDetailsScreen.kt
│           │                   │   ├── DocumentsScreen.kt
│           │                   │   ├── DocumentDetailsScreen.kt
│           │                   │   ├── AlertsScreen.kt
│           │                   │   └── ProfileScreen.kt
│           │                   │
│           │                   └── theme/
│           │
│           └── res/
│
├── gradle/
│
├── .gitignore
├── build.gradle.kts
├── gradle.properties
├── gradlew
├── gradlew.bat
├── settings.gradle.kts
└── README.md

🛠️ Technology Stack
Category	Technology
Language	Kotlin
UI Framework	Jetpack Compose
Design System	Material 3
Navigation	Navigation Compose
IDE	Android Studio
Version Control	Git
Repository	GitHub
Platform	Android


📱 Prototype Screens

The current prototype demonstrates the following user journey:

Screen	Purpose
🎓 Welcome	Application introduction
🔐 Login	Student authentication
📝 Create Account	New student registration
📱 OTP	Mobile verification
🏠 Home	Scholarship dashboard
🎯 Scholarships	Eligibility Radar
📊 Eligibility Details	Detailed eligibility information
📄 Documents	Unified document management
🔐 Document Details	Verification and Zero-Reupload
🔔 Updates	Scholarship notifications
👤 Profile	Unified student profile
🤖 JAGO	Scholarship assistance


🎨 Design System

ScholarshipSathi uses a simple status-based visual language.

Indicator	Meaning
🟢	Verified / Eligible
🟡	Pending / Potentially Eligible
🔴	Action Required
🟣	Interactive / Navigation

The UI uses:

Consistent rounded cards
Clear typography
Status indicators
Action-oriented information
Simple navigation
Student-friendly terminology

The goal is to make scholarship information understandable at a glance.

🚀 Getting Started
Requirements

Before running the project, make sure you have:

Android Studio
Android SDK
JDK compatible with the project
Git
Clone the Repository
git clone https://github.com/Bhaktigeethub1710/ScholarshipSathi.git
Open the Project

Open the cloned ScholarshipSathi folder in Android Studio.

Allow Android Studio to complete Gradle synchronization.

Build the Project

From Android Studio:

Build → Make Project

or press:

Ctrl + F9
Run the Application

Connect an Android device or start an emulator and press:

▶ Run
🧪 Prototype Scope

This repository represents a functional UI prototype developed for hackathon demonstration purposes.

The current prototype focuses on demonstrating:

Student onboarding
Login and account creation
OTP verification flow
Scholarship discovery
Eligibility visualization
Document verification concepts
Zero-Reupload workflow
Scholarship tracking
Notifications
Student profile
JAGO interaction

The current application uses static/demo data to demonstrate the intended user experience.

The prototype is designed to communicate the proposed workflow and user experience without requiring production backend integrations.

🔮 Future Scope

The prototype can be extended into a production-ready platform through integration with relevant authoritative systems and services such as:

DigiLocker
UDISE+
APAAR
AISHE
UIDAI
State e-District services
UGC / NTA systems
Existing scholarship platforms
Real-time application status
Secure document verification
DBT / payment tracking
Multilingual JAGO
Beneficiary Gap Detection
Automated verification
Exception-based manual verification
🔒 Security Considerations

A production implementation would require:

Secure authentication
Encrypted communication
Secure document storage
Role-based access control
Consent-based data sharing
Audit logging
Secure API integration
Appropriate government data protection and compliance mechanisms
💡 Core Concept

ScholarshipSathi is built around three major ideas:

🎯 Eligibility Radar

Help students discover scholarship opportunities relevant to their profile.

🔐 Zero-Reupload Verification

Reduce repetitive document submission by allowing verified documents to be reused across eligible scholarship applications.

📊 Beneficiary Gap Detection

Identify students who may be eligible for scholarship benefits but are not currently receiving them, enabling targeted intervention and outreach.

🧩 Why ScholarshipSathi?

The scholarship journey can involve multiple disconnected activities:

Search
  ↓
Check Eligibility
  ↓
Collect Documents
  ↓
Upload Documents
  ↓
Verify
  ↓
Apply
  ↓
Track
  ↓
Wait for Sanction
  ↓
Track Payment

ScholarshipSathi brings these activities into a unified student experience:

        ┌──────────────────────────┐
        │      SCHOLARSHIPSATHI    │
        └────────────┬─────────────┘
                     │
        ┌────────────┼────────────┐
        ▼            ▼            ▼
    Discover      Verify       Track
        │            │            │
        ▼            ▼            ▼
   Eligibility   Documents    Applications
        │            │            │
        └────────────┼────────────┘
                     ▼
                  🤖 JAGO
🌱 Vision

From searching for scholarships to understanding your entire scholarship journey — all in one place.

Discover → Understand → Verify → Track

ScholarshipSathi aims to create a simpler, more transparent and student-friendly scholarship experience.

🎓 Hackathon Project
ScholarshipSathi

A unified mobile-first scholarship experience built with Kotlin and Jetpack Compose.

Built with ❤️ for a simpler scholarship journey.

### After you've pasted that

1. **Don't add anything else.**
2. Scroll all the way to the bottom of the GitHub editor.
3. Find **Commit changes**.
4. Commit message:

```text
Add project documentation
Select Commit directly to the main branch.
Click Commit changes.


