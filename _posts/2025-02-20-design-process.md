---
title: "The Design Process of a Health Companion Super App"
date: 2025-02-20T15:34:30-04:00
header:
  overlay_image: /assets/images/header.jpg
  overlay_filter: linear-gradient(rgba(44, 62, 80, 0.7), rgba(0, 0, 0, 0.6))
  caption: "Photo credit: [**Unsplash**](https://unsplash.com/photos/a-close-up-of-a-piece-of-paper-xzzgY__zX8A)"
  show_overlay_excerpt: false
toc: true
toc_label: "Table of Contents"
toc_icon: "cog"
toc_sticky: true
categories:
  - Blog
tags:
  - ui
  - ux
  - mobile

gallery-personas:
  - url: /assets/images/personas/The_Social_Connector.png
    image_path: /assets/images/personas/The_Social_Connector.png
    alt: "Persona #1"
    title: "Persona #1: The Social Connector"
  - url: /assets/images/personas/The_Disconnected.png
    image_path: /assets/images/personas/The_Disconnected.png
    alt: "Persona #2"
    title: "Persona #2: The Disconnected"
  - url: /assets/images/personas/The_Overwhelmed_Patient.png
    image_path: /assets/images/personas/The_Overwhelmed_Patient.png
    alt: "Persona #3"
    title: "Persona #3: The Overwhelmed Patient"

gallery-user-journey:
  - url: /assets/images/User_Journey_Map.png
    image_path: /assets/images/User_Journey_Map.png
    alt: "User Journey Map"
    title: "User Journey Map"

gallery-typography:
  - url: /assets/images/typeface.png
    image_path: /assets/images/typeface.png
    alt: Typography for the Health Companion Super App 
    title: Typography for the Health Companion Super App 

gallery-wireframe:
  - url: /assets/images/prototypes/wireframe/Signup.png
    image_path: /assets/images/prototypes/wireframe/Signup.png
    alt: "Screen #1: Signup"
    title: "Screen #1: Signup"
  - url: /assets/images/prototypes/wireframe/Home_Page.png
    image_path: /assets/images/prototypes/wireframe/Home_Page.png
    alt: "Screen #2: Home Page"
    title: "Screen #2: Home Page"
  - url: /assets/images/prototypes/wireframe/Schedule.png
    image_path: /assets/images/prototypes/wireframe/Schedule.png
    alt: "Screen #3: Schedule"
    title: "Screen #3: Schedule"
  - url: /assets/images/prototypes/wireframe/Connect.png
    image_path: /assets/images/prototypes/wireframe/Connect.png
    alt: "Screen #4: Connect"
    title: "Screen #4: Connect"
  - url: /assets/images/prototypes/wireframe/Settings.png
    image_path: /assets/images/prototypes/wireframe/Settings.png
    alt: "Screen #5: Settings"
    title: "Screen #5: Settings"
  - url: /assets/images/prototypes/wireframe/Feedback.png
    image_path: /assets/images/prototypes/wireframe/Feedback.png
    alt: "Screen #6: Feedback"
    title: "Screen #6: Feedback"

gallery-final-prototype:
  - url: /assets/images/prototypes/prototype/Splash_Screen.png
    image_path: /assets/images/prototypes/prototype/Splash_Screen.png
    alt: "Screen #1: Splash Screen"
    title: "Screen #1: Splash Screen"
  - url: /assets/images/prototypes/prototype/Onboarding.png
    image_path: /assets/images/prototypes/prototype/Onboarding.png
    alt: "Screen #2: Onboarding"
    title: "Screen #2: Onboarding"
  - url: /assets/images/prototypes/prototype/Home_Screen.png
    image_path: /assets/images/prototypes/prototype/Home_Screen.png
    alt: "Screen #3: Home Screen"
    title: "Screen #3: Home Screen"
  - url: /assets/images/prototypes/prototype/Blood_Pressure.png
    image_path: /assets/images/prototypes/prototype/Blood_Pressure.png
    alt: "Screen #4: Blood Pressure"
    title: "Screen #4: Blood Pressure"
  - url: /assets/images/prototypes/prototype/Weight_Overview.png
    image_path: /assets/images/prototypes/prototype/Weight_Overview.png
    alt: "Screen #5: Weight Overview"
    title: "Screen #5: Weight Overview"
  - url: /assets/images/prototypes/prototype/Schedule.png
    image_path: /assets/images/prototypes/prototype/Schedule.png
    alt: "Screen #6: Schedule"
    title: "Screen #6: Schedule"
  - url: /assets/images/prototypes/prototype/Connect.png
    image_path: /assets/images/prototypes/prototype/Connect.png
    alt: "Screen #7: Connect"
    title: "Screen #7: Connect"
  - url: /assets/images/prototypes/prototype/Feedback.png
    image_path: /assets/images/prototypes/prototype/Feedback.png
    alt: "Screen #8: Feedback"
    title: "Screen #8: Feedback"
  - url: /assets/images/prototypes/prototype/Preferences.png
    image_path: /assets/images/prototypes/prototype/Preferences.png
    alt: "Screen #9: Preferences"
    title: "Screen #9: Preferences"
---

# Introduction
Welcome to the behind-the-scenes journey into the making of the Health Companion Super App! In this blog post, I'll be pulling back the curtain on the UI/UX design process, from early user research and persona creation to the nitty-gritty of prototyping and usability testing. This isn't just a dry report; it's a story of transforming complex healthcare challenges into an intuitive, engaging mobile experience. 

This app is designed to empower individuals with chronic conditions by helping them manage their medications, schedule doctor appointments, and securely communicate with healthcare professionals all with ease and clarity. Join me as I share my creative process, the challenges I faced, and the insights that drove my design decisions, giving you a closer look at how I developed a truly user-centered healthcare solution.

# User Research and Key Findings
In my design process for the Health Companion Super App, I relied on extensive user research to ensure a truly user-centered approach. Below is a brief overview of my research strategy and the key insights that helped shape the app's design.

## Primary Research Methods
- **In-Depth Interviews and Focus Groups**  
  I researched several semi-structured interviews and focus groups with target users such as patients with diabetes, hypertension, and other chronic conditions to explore their daily challenges, technology usage, and desired app features.

- **Surveys and Questionnaires**  
  I reviewed existing online surveys to gather quantitative data on medication consistency, appointment management challenges, and preferred communication channels. These surveys underscored the importance of clear instructions and accessible interfaces, especially for users with limited digital literacy.

## Secondary Research Methods
- **Literature Reviews and Case Studies**  
  I analyzed studies on mobile health (mHealth) apps for chronic disease management. Research such as mHealth 2019 (Wellframe User Personas) provided deep insights into user behaviors and adherence challenges, revealing that high mobile penetration does not automatically lead to app adoption. Cultural and physical barriers, like language preferences and poor eyesight, emerged as critical factors that require thoughtful design adaptations.

- **Competitive Analysis**  
  I examined established platforms like Wellframe to understand best practices in user-centered design. Key takeaways included the need for:
  - **Localization and Accessibility:** Automatically adapting content for diverse users (e.g., Spanish, Haitian Creole).
  - **Ease of Support Communication:** Incorporating care advocates and in-app messaging to enhance user engagement.
  - **Personalization:** Delivering tailored health checklists and reminders that cater to unique user needs.

## Design Implications
Based on my research, I ensured that the app would:
- **Incorporate Multi-Modal Communication:** Utilize both SMS and in-app alerts.
- **Provide Personalized Content:** Leverage language localization.
- **Simplify Interfaces:** Make sure the app is accessible for users with varying levels of digital literacy.
- **Integrate with Health Services:** Seamlessly connect with appointment scheduling.
- **Offer Robust Support and Training:** Include comprehensive onboarding.

# User Personas
Based on the previous [research findings](#user-research-and-key-findings), three detailed personas were created to encapsulate the diverse needs of the app's target users. These personas serve as reference points throughout the design process to ensure that every feature meets a real user need.

The personas are as follows:
1. <a href="https://www.figma.com/board/8aKtgnHVLFzGfnBt6miREo/User-Personas?node-id=0-1&t=TgFMl9tZ5ph4yiuV-1" target="_blank" rel="noopener noreferrer">The Social Connector</a>
2. <a href="https://www.figma.com/board/8aKtgnHVLFzGfnBt6miREo/User-Personas?node-id=11610-106&t=TgFMl9tZ5ph4yiuV-1" target="_blank" rel="noopener noreferrer">The Disconnected</a>
3. <a href="https://www.figma.com/board/8aKtgnHVLFzGfnBt6miREo/User-Personas?node-id=11610-315&t=TgFMl9tZ5ph4yiuV-1" target="_blank" rel="noopener noreferrer">The Overwhelmed Patient</a>

{% include gallery layout="single" id="gallery-personas" caption="Gallery of User Personas" %}

# User Journey Map
The following user journey map provides a comprehensive overview of the Health Companion Super App experience, from discovery and registration to daily engagement and ongoing re-engagement. It outlines each key touchpoint, detailing user actions, goals, emotions, and pain points encountered along the way.

The map helped identify pain points and opportunities for improvement in the user experience, from initial onboarding through to regular app usage.

{% include gallery layout="single" id="gallery-user-journey" caption="User Journey Map" %}

# Design Principles
The design system for the Health Companion Super App was carefully crafted to ensure consistency, accessibility, and user-friendliness across all interfaces. 

My design choices focus on creating a calming, professional healthcare environment while maintaining excellent readability and visual hierarchy. The following key design elements form the foundation of the user interface:

## Color Palette
The color scheme was carefully selected to create a calming and trustworthy healthcare environment while ensuring optimal accessibility. 

The <span style="color:#4A90E2">soft blue</span> primary color conveys professionalism and reliability, while the <span style="color:#50E3C2">soft cyan</span> and <span style="color:#7ED321">light green</span> accents add a fresh, modern touch that promotes wellness. 

These colors maintain WCAG 2.1 compliance for accessibility while creating visual harmony throughout the interface.

- **Primary:** <span style="color:#4A90E2">Soft Blue</span> (`#4A90E2`)
- **Secondary:** <span style="color:#50E3C2">Soft Cyan</span> (`#50E3C2`)
- **Accent:** <span style="color:#7ED321">Light Green</span> (`#7ED321`)
- **Background:** <span style="color:#FFFFFF;background-color:#666666">White</span> (`#FFFFFF`)

<img src="/assets/images/Color_Palette.png" alt="Health Companion Super App Color Palette" title="Health Companion Super App Color Palette" style="border: 1px solid #ddd;">

## Typography
Typography plays a crucial role in any mobile app's accessibility and readability. I chose Roboto for its clean, modern appearance and excellent legibility across different screen sizes. 

The font sizing hierarchy ensures clear visual organization while maintaining comfortable reading sizes for users with varying visual abilities.

- **Font:** <span style="font-family: Roboto, sans-serif">Roboto</span>
- **Font Size:** 
  - Body Text: 16px 
  - Headings: 18–24px

{% include gallery layout="single" id="gallery-typography" caption="Typography of the Health Companion Super App" %}

## Sizing
Consistent spacing and sizing are crucial for creating a balanced, accessible interface. 

I implemented a standardized 16px unit system throughout the app to maintain visual harmony and improve usability. 

The rounded corners and consistent padding create a friendly, approachable feel while ensuring content remains easily readable and interactive elements are comfortably tapable.

- **Border Radius:** 16px
- **Spacing:**
  - Padding of 16px
  - Margin of 16px

<img src="/assets/images/Sizing_Guidelines.png" style="display:block;float:none;margin-left:auto;margin-right:auto;width:60%" alt="Health Companion Super App Sizing Guidelines" title="Health Companion Super App Sizing Guidelines">

# Prototypes
Moving from concept to reality, the development of the Health Companion Super App began with essential wireframe designs that laid the groundwork for a comprehensive health management solution.

As the design evolved into the final prototype, the basic structure was enhanced with refined user interfaces, intuitive navigation patterns, and a cohesive visual language. The progression maintained the app's fundamental purpose while introducing more sophisticated features like personalized health insights, detailed medication adherence tracking, and interactive health data visualizations. 

The following sections showcase both the initial wireframes and the polished prototype, highlighting how the design matured while maintaining its user-centric approach to health tracking and management.

## Wireframe
These initial wireframes served as a skeletal blueprint, mapping out the core functionalities: 
- Onboarding
- Medication Tracking
- Appointment Scheduling
- Healthcare Team Communication
- Setting User Preferences
- Enabling User Feedback

{% include gallery layout="half" id="gallery-wireframe" caption="Wireframe Prototype" %}

## Final Prototype
After iterating on our initial wireframes, I developed the final prototype of the Health Companion Super App, transforming the early concepts into a fully-realized, interactive design. In this phase, I not only refined the user interface and navigation patterns but also introduced several key enhancements to elevate the user experience.

Notably, the final prototype includes:
- **Health Metrics Monitoring:** A dedicated module that continuously tracks and displays vital health metrics, giving users clear insights into their progress over time.
- **Splash Screen:** A welcoming splash screen that establishes the app's calm and accessible visual language, setting the tone from the first interaction.
- **Interactive Health Metric Visualization:** Dynamic, engaging visualizations that allow users to interact with and interpret their health data easily.

The following sections showcase the screens that make up the final prototype.

{% include gallery layout="half" id="gallery-final-prototype" caption="Final Prototype" %}

# Usability Testing
## Putting the App to the Test  
No matter how polished a prototype looks, real user feedback is what makes or breaks a design. For the Health Companion Super App usability testing wasn't just a checkbox, it was a critical step to ensure the app truly served its users. Here's how I approached it.  

### Defining Goals and Tasks  
I focused on three core goals:  
1. **Simplifying Onboarding:** Could users with limited digital literacy easily register and input medical details?  
2. **Validating Core Features:** Were setting reminders, booking appointments, and messaging providers intuitive?  
3. **Clarity in Data Visualization:** Could users understand their health metrics at a glance?  

---

To test these, I designed scenario-based tasks mirroring real-life use:  
- Creating a profile with chronic condition details.  
- Setting a daily medication reminder.  
- Booking, then rescheduling, a doctor's appointment.  
- Sending a message to a healthcare provider.  
- Interpreting dashboard stats like blood pressure trends.  

### Gathering Real-World Insights  
I recruited a diverse group reflecting our personas to test both in-person and remotely. This included older adults, caregivers, and tech-savvy organizers. During sessions, I asked participants to *"think aloud"* while completing tasks, observing where they hesitated or struggled.  

---

Feedback came from multiple angles:
- **Live Reactions:** Hearing users vocalize confusion during tasks (e.g., `"Where's the 'reschedule' button?"`).  
- **Post-Test Surveys:** Ratings on ease of use and clarity.  
- **Follow-Up Interviews:** Deeper dives into pain points, like unclear terminology in the scheduling flow.  

### Learning and Iterating  
After each test, I categorized issues by severity and frequency. For example:  
- Many users missed the rescheduling button (*critical flaw*).  
- Others found the dashboard charts overwhelming.  

This led to rapid cycles of:  
1. **Redesigning Problematic Flows** (e.g., adding a prominent `"Reschedule"` option).  
2. **Simplifying Data Visualizations** with clearer labels and progressive disclosure.  
3. **Retesting** to confirm fixes worked.  

**One key takeaway?** Even small tweaks, like swapping medical jargon for plain language, dramatically improved usability for older adults.

# Reflection  
Designing the Health Companion Super App taught me how deeply user insights can transform a product, and how humbling it is to realize your first draft is never the final answer. Here's what I learned along the way.  

## Learning from Real Users  
Through interviews, surveys, and focus groups, I discovered just how varied user needs could be. For example:  
- **Digital literacy gaps** shaped my approach: I streamlined onboarding with bite-sized forms and added guided tutorials after hearing users describe registration as "overwhelming."
- **Personas became my compass.** "The Overwhelmed Patient" reminded me to prioritize clear language, while "The Disconnected" pushed me to simplify navigation for users anxious about complex interfaces.  

## When Testing Reveals Blind Spots  
Usability testing was a reality check. Watching users struggle with the appointment scheduler, a feature I'd assumed was intuitive, forced me to rethink my assumptions. Key takeaways:  
- **Clarity Trumps Cleverness:** Charts I designed to be "comprehensive" were seen as cluttered. This resulted in me simplifying their design to eliminate any unnecessary clutter.

## Balancing Complexity and Simplicity  
The biggest challenge? Building a feature-rich app that still felt simple. For example:  
- **Voice-assisted features** emerged as a solution for low-literacy users during testing.  
- **Iteration saved the day:** Every round of feedback led to small tweaks, like swapping medical jargon ("hypertension") for plain language ("high blood pressure").  