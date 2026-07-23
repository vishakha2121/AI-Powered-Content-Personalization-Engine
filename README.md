# 🤖 AI-Powered Content Personalization Engine

## 🎯 Project Overview

The **AI-Powered Content Personalization Engine** is an intelligent content generation platform that leverages Google's Gemini AI to create highly personalized marketing content at scale. This innovative solution transforms how businesses communicate with their audience by generating tailor-made emails, advertisements, product descriptions, blog posts, and marketing campaigns that resonate with individual user preferences.

## ✨ Key Features

### 📧 Content Generation Types
- **Personalized Emails**: Custom email templates with dynamic content based on user preferences
- **Advertisement Copy**: Compelling advertisements optimized for different platforms
- **Product Descriptions**: Unique, SEO-friendly product descriptions
- **Blog Content**: Full-length blog posts with engaging narratives
- **Marketing Campaigns**: Complete campaign strategies with multi-channel content

### 🎯 Smart Features
- **Personalization Engine**: User preference analysis and dynamic content adaptation
- **Recommendation System**: Smart content suggestions based on user history
- **User Dashboard**: Track all generated content and analytics
- **Content History**: Complete history of all generated content
- **JWT Authentication**: Secure user authentication and authorization

## 🛠️ Technology Stack

### Frontend
- ⚛️ **React.js** - UI Framework
- 🎨 **Tailwind CSS** - Styling
- 🔄 **Axios** - API Calls
- 🛣️ **React Router** - Navigation
- 📊 **Chart.js** - Analytics

### Backend
- 🐍 **Python 3.8+** - Programming Language
- 🌶️ **Flask** - Web Framework
- 🗄️ **SQLite** - Database
- 🔐 **JWT** - Authentication
- 🤖 **Gemini AI** - Content Generation
- 🔗 **Flask-CORS** - Cross-Origin Resource Sharing

### Development Tools
- 📝 **VS Code** - Code Editor
- 🐙 **Git** - Version Control
- 📦 **pip** - Python Package Manager
- 📦 **npm** - Node Package Manager

## 📁 Project Structure

## 🚀 Quick Start Guide

### Prerequisites
- Node.js (v14 or higher)
- Python (3.8 or higher)
- Git
- Gemini API Key

### 1. Clone the Repository
```bash
git clone https://github.com/vishakha2121/AI-Powered-Content-Personalization-Engine.git
cd AI-Powered-Content-Personalization-Engine

# Navigate to backend directory
cd backend

# Create virtual environment
python -m venv venv

# Activate virtual environment
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Create .env file and add your Gemini API key
echo "GEMINI_API_KEY=your_api_key_here" > .env
echo "JWT_SECRET_KEY=your_jwt_secret_here" >> .env

# Run the backend server
python run.py

# Navigate to frontend directory
cd frontend

# Install dependencies
npm install

# Create .env file for frontend
echo "REACT_APP_API_URL=http://localhost:5000" > .env

# Start the development server
npm start