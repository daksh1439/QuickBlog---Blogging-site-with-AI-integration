# QuickBlog---Blogging-site-with-AI-integration

QuickBlog is a full-stack MERN blogging platform that allows users to create, publish, and explore blog posts. It also integrates AI-powered content generation using the Groq API, helping users quickly generate blog content from a given topic or prompt.

## Features

- 🔐 User authentication and authorization
- ✍️ Create, edit, publish, and manage blog posts
- 🤖 AI-powered blog generation using the Groq API
- 📝 Rich-text blog editor using Quill
- 🖼️ Image upload and cloud storage using ImageKit
- 🔎 Browse and read published blogs
- 🛡️ Content moderation and admin management
- 📱 Responsive user interface

## Tech Stack

### Frontend
- React.js
- JavaScript
- Tailwind CSS
- React Router
- Quill Editor

### Backend
- Node.js
- Express.js
- MongoDB
- JWT Authentication

### APIs & Services
- Groq API – AI-powered blog generation
- ImageKit – Image storage and delivery

## AI Integration

QuickBlog uses the Groq API to generate blog content based on user-provided topics or prompts. The generated content can then be edited using the rich-text editor before being published.

```text
User Prompt
     ↓
React Frontend
     ↓
Node.js / Express Backend
     ↓
Groq API
     ↓
AI Generated Content
     ↓
Rich Text Editor
     ↓
Publish Blog
     ↓
MongoDB