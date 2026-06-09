
# LearnX — LMS Mobile App

## Project Vision
LearnX is a Flutter-based mobile Learning Management System (LMS) built as part of the Excelerate Mobile Development Programme. The goal is to provide learners and administrators with a clean, intuitive mobile platform that makes programme discovery, enrolment, and progress tracking effortless on any Android or iOS device.

## Objectives
- Build a role-aware authentication flow that routes Learners and Admins to their respective dashboards
- Implement 4 core screens in Week 1 (Login, Home, Programme Listing, Programme Details) and expand to a fully functional app by Week 4
- Follow Flutter best practices including widget composition, state management, and named routing
- Design a user-friendly UI that works seamlessly for both learners tracking their progress and admins managing programmes


## Navigation Flow

Login
  ├── [Learner] → Home / Dashboard
  │                   ├── Programme Listing
  │                   │       └── Programme Details → Enrol Now
  │                   └── Profile
  │
  └── [Admin]  → Admin Dashboard
                      ├── New Programme Form → Publish
                      └── Announcement Composer → Send to All Learners
