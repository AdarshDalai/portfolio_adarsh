---
title: Utter
publishDate: 2025-01-20 00:00:00
img: /assets/AndroidSpotlight_Adaptive_CameraX_Banner_02.png
img_alt: android with camera
description: |
  A social media application for GenZ
tags:
  - Jetpack Compose
  - FastAPI, Supabase
---

##### Utter Application

Overview
Utter is a social media application designed to connect people through seamless interactions. With a user-friendly interface and robust features, Utter provides a platform for users to share their thoughts, media, and engage with a vibrant community.

---

Features

Core Features:
1. **User Authentication:**
   - Secure login and signup with Supabase integration.
   - Password hashing for enhanced security.

2. **User Profiles:**
   - Customizable profiles with profile pictures, bios, and username updates.
   - Follow and unfollow other users.

3. **Posts and Media Sharing:**
   - Create posts with text, images, or videos.
   - Cloudflare R2 for media storage and retrieval.

4. **Engagement Tools:**
   - Commenting and liking posts.
   - Notifications for activities such as likes, comments, and followers.

5. **Categorization:**
   - Simple content categorization to organize and discover posts.

6. **Responsive API:**
   - RESTful API endpoints for efficient interactions between the backend and clients.

---

Tech Stack

Backend:
- **Framework:** FastAPI
- **Database:** PostgreSQL (via Supabase)
- **Storage:** Cloudflare R2 for media assets
- **Authentication:** Supabase's authentication service

Frontend:
- **Android:** Jetpack Compose
- **iOS:** SwiftUI
- **API Calls:** Ktor for Android and iOS

---

Architecture

Backend:
- **Microservices:**
  - Separate services for feed, uploads, and other core functionalities.
- **Database Access:**
  - Direct integration with PostgreSQL for enhanced performance and flexibility.
  - Supabase used for authentication and user data.

Frontend:
- **Android and iOS:**
  - MVVM architecture for clean code and scalability.
- **File Structure:**
  - Feature-specific folders with `Data`, `Domain`, and `Presentation` layers.
  - Root-level files for navigation and main activities.

---

Key User Stories

1. **Account Management:**
   - Create an account, log in, update profile details, and manage followers.

2. **Post Creation:**
   - Upload photos or videos using the in-app camera module (CameraX) or gallery.
   - Add captions and edit media before posting.

3. **Engagement:**
   - Like and comment on posts to interact with others.
   - Receive notifications for interactions.

4. **Content Categorization:**
   - Easily organize and discover content using categories.

---

Deployment Plan

Backend:
- Hosted on cloud platforms like AWS, Azure, or GCP.
- Endpoints optimized for scalable and reliable performance.

Frontend:
- Deployed on Google Play Store (Android) and Apple App Store (iOS).
- Seamless integration with backend services for real-time interactions.

---

Future Enhancements

1. **AI Integration:**
   - Leverage AI to provide smart content recommendations and moderation.

2. **Advanced Notifications:**
   - Real-time push notifications for activities and trends.

3. **Analytics Dashboard:**
   - Insights for users on engagement metrics.

4. **Enhanced Community Features:**
   - Groups and forums for deeper interaction.

---

About the Developer
Utter is developed by Adarsh, a passionate app developer exploring both mobile application development and the AI space. Adarsh aims to create impactful technology that fosters connection and innovation.
