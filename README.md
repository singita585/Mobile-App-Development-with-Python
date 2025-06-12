# Category-Based Quiz Game App

This is a mobile quiz application built using **Python**, **Kivy**, and **KivyMD**, with data stored in a **SQLite** database. The app allows users to add word pairs into categories and then test their memory by guessing answers in a game mode.

## Features

- 🧠 **Quiz Game**: Play a simple quiz by guessing answers based on stored questions.
- 🗂️ **Category-Based Storage**: Organize your question-answer pairs into categories.
- ✍️ **Edit and Delete Words**: Manage your saved words easily.
- 💾 **Local Storage with SQLite**: Data is saved on your device using a local SQLite database.
- 📱 **Multi-Screen Navigation**: Smooth transitions between home, game, and editing screens using KivyMD.

## How It Works

1. **Add Words**: Select a category and add your question/answer pairs.
2. **Play Game**: Pick a category to test your memory by guessing the answers.
3. **Manage Words**: View, edit, or delete any previously added entries.

## Installation

Make sure you have Python installed, then install Kivy and KivyMD:

```bash
pip install kivy kivymd

Run the app:
python main.py
