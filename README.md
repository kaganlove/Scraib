# Scraib
AI-Powered Note Taking App

Scraib: Full Development Brief for Web Developer
Project Overview
Scraib is an AI-powered educational platform that transforms note-taking from passive recording into active learning. Unlike simple transcription tools, Scraib analyzes student notes against comprehensive knowledge bases, identifies gaps in understanding, and guides students through Socratic questioning to achieve deeper comprehension. The platform serves both students and teachers with distinct but interconnected experiences.
Core Functionality & AI Intelligence
Student Experience - Active Learning Loop

Input Methods: Students can dictate notes verbally or upload materials (worksheets, textbook pages, handouts)
Real-time Analysis: AI compares notes against:

Pre-programmed knowledge bases for the subject
Teacher-uploaded materials and curricula
Identifies missed concepts, incomplete connections, and knowledge gaps


Socratic Intervention: When gaps are detected, the system prompts students with guiding questions (not answers) to help them discover missing information
Smart Organization: Notes are automatically structured into proven formats (Cornell notes, outlines, etc.)
Intelligent Review: The system remembers struggle points and generates targeted quizzes/flashcards that focus on previously missed concepts

Teacher Experience - Learning Visibility

Class Management: Create and manage student accounts, assign content
Material Upload: Teachers upload lesson plans, worksheets, and reference materials that become the knowledge base for gap detection
Learning Analytics: Dashboard shows where students are struggling, which concepts are frequently missed
Guided Support: Teachers can enable "Socratic guidance" that ensures AI asks questions rather than providing direct answers
Progress Tracking: Monitor how students are taking notes, using study tools, and improving over time

Visual Design & Branding
Brand Identity

Name: Scraib (evolved from NoteNavi)
Logo: Notebook with quill feather stylized as circuitry
Color Palette:

Mint Green: #4ac7a7 (primary accent, glows)
Dark Green: #153e35 (text, borders)
Cream: #fff7df (backgrounds)


Motto: "Transform your notes into learning"
Tagline: "AI-powered organization and review for students and teachers"

Design Aesthetic

Theme: Notebook paper meets modern technology
Background: Custom SVG featuring lined notebook paper with circuit board borders
Animation: 6 mint green glowing orbs that travel along circuit paths (avoid center lines and circular nodes)
Layout Style: Inspired by ChatGPT/Canva with sidebar navigation and central workspace

User Interface Requirements
Layout Structure

Sidebar Navigation: Dashboard, Notes, Uploads, Flashcards, Quizzes, Students/Teachers, Settings
Central Workspace: Clean editor panel with toolbar for note-taking and review
Right Sidebar: Quick Actions (Upload, Generate Flashcards, Assign Content) plus progress widgets

Key Pages Needed

Landing Page: Hero section with split view (For Students / For Teachers), feature highlights
About Page: Storytelling format explaining pain points and solutions
Pricing Page: Three tiers (Free, Teacher Pro $5/mo, Institution $2/user/mo)
Login/Signup: Clean forms with Scraib branding
Dashboard: Different views for students vs. teachers
Note Editor: Real-time Socratic questioning interface
Study Tools: Quiz and flashcard generation/review interface
Teacher Analytics: Student progress and gap analysis views

Technical Architecture Needs
Core AI Features to Build

Gap Detection Engine: Compare student notes against knowledge bases
Socratic Questioning System: Generate guiding questions (not answers) based on missing concepts
Memory System: Track and remember individual student struggle points
Adaptive Quiz Generation: Create targeted review based on previous gaps
Content Analysis: Process uploaded materials to build subject-specific knowledge bases

Database Structure

User management (students, teachers, institutions)
Note storage with metadata (gaps identified, questions asked, responses)
Knowledge bases (subject content, teacher materials)
Progress tracking (struggle points, improvement over time)
Study tools (generated quizzes, flashcards, results)

Integration Requirements

AI transcription services for voice-to-text
Image processing for uploaded materials (OCR)
Real-time collaboration between teachers and students
Analytics and progress tracking
Mobile responsiveness

Competitive Differentiation
Unlike existing note-taking apps that focus on transcription and organization, Scraib's unique value propositions are:

Active gap detection during note-taking process
Socratic methodology that promotes discovery learning
Teacher-student connection with learning visibility
Educational-first design rather than generic productivity
Memory of struggle points for personalized review

Development Priority

MVP Core: Basic note-taking with gap detection and Socratic questioning
Teacher Tools: Dashboard, student management, material uploads
Study Features: Quiz/flashcard generation based on gaps
Analytics: Progress tracking and learning insights
Advanced Features: Institutional management, advanced AI capabilities

Success Metrics

Student engagement with Socratic prompts
Improvement in concept mastery over time
Teacher adoption and active use of analytics
Retention rates for both user types
Quality of AI gap detection and questioning

This platform requires a sophisticated AI backend combined with an intuitive, educational-focused frontend that makes learning visible and actionable for both students and teachers.
