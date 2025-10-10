# Study Tracker Mobile App

🎯 **A comprehensive Android application designed to help students and teams set academic goals, track study progress, and visualize learning achievements through interactive dashboards.**

Developed as part of CSE 230 Mobile Programming course, this app enhances learner agency by providing structured goal tracking and progress visualization tools.

---

## 🎯 Objectives & Purpose

### Primary Goals
- **Goal Setting & Tracking**: Help individuals and teams define academic goals and monitor progress towards achievement
- **Visual Progress Monitoring**: Provide structured dashboards and progress bars for clear visualization
- **Ownership Creation**: Foster personal accountability and ownership of learning outcomes
- **Learner Agency Enhancement**: Develop self-awareness and learning management skills

### Key Benefits
- 🚀 **Accelerate Learning**: Streamlined progress tracking improves learning efficiency
- 📊 **Smart Adjustments**: Make data-driven instructional modifications
- 📈 **Academic Documentation**: Comprehensive record of user's academic advancement  
- 🎯 **Focused Support**: Minimize unnecessary interventions through precise tracking
- 💪 **Self-Ownership**: Encourage learner responsibility and self-management skills

---

## 🛠️ Technology Stack

### **Core Technologies**
- **Android Studio**: Primary IDE for Android development
- **Kotlin**: Modern programming language with full Java compatibility
- **Firebase**: Backend-as-a-Service for authentication, database, and analytics

### **Development Tools**
- **Android Emulators**: Testing across multiple device configurations
- **Gradle Build System**: Dependency management and build automation
- **Android Manifest**: App configuration and permissions

---

## 📱 Features & Components

### **User Interface Components**
- **Text Views**: Display study information and progress
- **Interactive Buttons**: Navigate between app sections
- **Edit Texts**: Input study goals and session details
- **Image Views**: Visual elements and icons
- **Spinners**: Dropdown selections for subjects and time periods

### **Navigation & Layout**
- **Fragment-based Architecture**: Modular screen management
- **Constraint Layout**: Responsive UI design
- **Bottom Navigation**: Easy access to main app sections
- **List Views**: Display study subjects and session history

### **User Experience**
- **Toast & Snackbar Messages**: Real-time feedback and notifications
- **Shared Preferences**: User settings and login persistence
- **Intent System**: Seamless navigation between activities

---

## 🏗️ App Architecture

### **Main Components**

#### **Authentication System**
- **Google Sign-In Integration**: Secure user authentication
- **Firebase Auth**: User management and session handling
- **User Registration**: Account creation with validation
- **Login Persistence**: Remember user sessions

#### **Core Activities**
- **MainActivity.kt**: Entry point with authentication logic
- **HomeActivity.kt**: Main dashboard with navigation
- **Fragment Management**: Home, Subjects, Analytics, Profile screens

#### **Data Management**
- **Firebase Realtime Database**: Cloud storage for user data
- **Subject Tracking**: Store and retrieve study subjects
- **Time Management**: Track study sessions and schedules
- **Progress Analytics**: Calculate and display learning metrics

---

## 📊 Key Screens & Functionality

### **1. Splash Screen**
- App branding and loading interface
- Automatic navigation to login/home based on auth status

### **2. Authentication Flow**
- **Login Screen**: Email/password and Google Sign-In options
- **Registration**: New user account creation with validation
- **Bottom Sheet UI**: Smooth transition between login/signup

### **3. Home Dashboard**  
- **Today's Schedule**: Display current day's study subjects
- **Live Clock**: Analog clock for time awareness
- **Quick Access**: Fast navigation to key features
- **Progress Overview**: Daily study summary

### **4. Subjects Management**
- **Subject Grid**: Visual display of all study subjects
- **Add New Subject**: Create subjects with schedules
- **Time Slots**: Assign specific days and time ranges
- **Subject Details**: View and edit subject information

### **5. Timer & Tracking**
- **Study Timer**: Track active study sessions  
- **Session History**: Review past study activities
- **Goal Progress**: Visual progress towards targets

### **6. Analytics & Reports**
- **Progress Visualization**: Charts and graphs of study patterns
- **Performance Metrics**: Learning efficiency analysis
- **Goal Achievement**: Track completion rates

### **7. User Profile**
- **Personal Information**: User details and preferences
- **Settings**: App configuration and customization
- **Achievement Badges**: Gamification elements

---

## 🔧 Installation & Setup

### **Prerequisites**
- Android Studio 4.0+
- Android SDK (API level 21+)
- Google Play Services
- Firebase Account


### **Firebase Configuration**
1. Create new Firebase project
2. Enable Authentication (Email/Password, Google)
3. Set up Realtime Database with appropriate rules
4. Download `google-services.json` and add to `app/` folder

---

## 🎨 User Interface Design

### **Design Principles**
- **Material Design**: Following Google's design guidelines
- **Intuitive Navigation**: Bottom navigation for main sections
- **Visual Feedback**: Toast messages and progress indicators
- **Responsive Layout**: Constraint Layout for multiple screen sizes

### **Color Scheme & Theming**
- Modern gradient backgrounds
- Card-based layout for content organization
- Consistent typography and spacing
- Dark/Light theme compatibility

---

## 📈 App Workflow

1. **User Authentication**: Login or register new account
2. **Dashboard Overview**: View today's schedule and progress
3. **Subject Management**: Add, edit, or remove study subjects
4. **Study Sessions**: Start timer, track active learning
5. **Progress Review**: Analyze performance through analytics
6. **Goal Adjustment**: Modify targets based on progress

---

## 🔒 Data Security & Privacy

- **Firebase Authentication**: Secure user identity management
- **Encrypted Storage**: Sensitive data protection
- **Privacy Controls**: User data ownership and control
- **GDPR Compliance**: Respecting user privacy rights

---


## 🔄 Future Enhancements

### **Planned Features**
- **Offline Mode**: Study tracking without internet
- **Team Collaboration**: Group study features
- **AI Recommendations**: Personalized study suggestions  
- **Cross-platform Sync**: Web and desktop versions
- **Advanced Analytics**: Machine learning insights
- **Gamification**: Achievement system and leaderboards

---

## 🐛 Known Issues & Troubleshooting

### **Common Issues**
- **Login Problems**: Check internet connection and Firebase config
- **Data Sync**: Ensure Firebase permissions are correctly set
- **UI Display**: Update to latest Android System WebView

### **Support**
- Check Firebase console for backend issues
- Verify google-services.json configuration
- Ensure proper Android SDK setup

---

## 📚 Educational Impact

### **Learning Outcomes**
- **Self-regulated Learning**: Students develop autonomous learning skills
- **Goal Achievement**: Structured approach to academic success
- **Time Management**: Effective study schedule planning
- **Progress Awareness**: Data-driven learning decisions

### **Institutional Benefits**
- **Quality Assurance**: Evidence-based learning monitoring
- **Intervention Targeting**: Identify students needing support
- **Outcome Tracking**: Measure educational effectiveness
- **Safeguarding Evidence**: Document student development progress

---

### **Key Classes**
- **User.kt**: User data model
- **SubjectAdapter.kt**: Subject list management
- **GridAdapter.kt**: Subject grid display
- **Fragment Management**: Home, Subjects, Analytics, Profile

---

## 📄 License

This project is developed for educational purposes as part of CSE 230 Mobile Programming coursework.

---

## 🙏 Acknowledgments

- Course instructors and teaching assistants
- Firebase documentation and community
- Android development community resources
- Team collaboration and peer learning

