# 🧠 Kitchen Buddy — Smart AI Recipe Generator (MERN Stack)

**Kitchen Buddy** is a smart web application built with the **MERN stack** (MongoDB, Express.js, React.js, Node.js) that helps users manage their pantry, reduce food waste, and get AI-generated recipe suggestions based on available ingredients. This project integrates external APIs like Spoonacular or Gemini for intelligent recipe generation and aims to make home cooking smarter and more sustainable.

## 🚀 Features

- ✅ User Authentication (JWT-based)
- 🗃️ Pantry Tracking System
- 🤖 AI-Generated Recipe Suggestions (using available ingredients)
- 📦 Ingredient Substitution & Grocery Recommendations
- 📅 Meal Planning
- 📊 MongoDB Database Models for Users, Pantry Items, and Recipes
- 🌐 RESTful API with secure routes and modular structure
- 🔒 Protected routes with middleware (e.g., for user-only pantry access)

## 🛠️ Tech Stack

- **Frontend**: React.js
- **Backend**: Node.js + Express.js
- **Database**: MongoDB (Mongoose ODM)
- **Authentication**: JWT, bcryptjs
- **External APIs**: Spoonacular API or Gemini AI for recipe generation
- **Hosting**: (to be added e.g. Render, Vercel, or Heroku)

## 🧑‍💻 How It Works

1. Users sign up and log in securely.
2. They enter available pantry items.
3. The app fetches recipes using those ingredients via AI/recipe APIs.
4. Users get recipe suggestions with missing ingredient alerts and healthy substitutes.
5. Optionally plan meals or save favorite recipes.

## 📂 Project Structure (Simplified Backend)
