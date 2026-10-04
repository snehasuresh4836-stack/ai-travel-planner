# 🧳 AI Travel Planner for Students

An AI-powered travel planning application designed to help students create personalized and budget-friendly travel itineraries.

The application uses Python, Gradio, and the Hugging Face Llama 3.1 model to generate travel plans based on the user's destination, budget, travel dates, and interests.

## 📌 Project Overview

Planning a trip can be difficult for students because of limited budgets, time constraints, and the need to find suitable places to visit.

This project provides an AI-based solution that generates a customized travel itinerary according to the student's requirements.

The system provides:

- Day-by-day travel plans
- Morning, afternoon, and evening activities
- Estimated daily expenses
- Local transportation tips
- Safety suggestions
- Free and low-cost options
- Must-see places
- Google Maps links

## 🎯 Main Objective

The main objective of this project is to create a simple AI travel assistant that helps students plan trips according to their budget, interests, and available travel dates.

## ✨ Features

### 👨‍🎓 Student-Focused Planning
Creates travel plans with a student-friendly and budget-conscious approach.

### 💰 Budget-Based Planning
Users can enter their travel budget in INR, and the AI generates a suitable itinerary.

### 📅 Date-Based Itinerary
Users provide a start date and end date, and the application generates a plan for the complete trip duration.

### 🎯 Interest-Based Recommendations
Users can enter interests such as:

- History
- Street food
- Local markets
- Culture
- Sightseeing

### 🤖 AI-Powered Itinerary Generation
The application uses the Hugging Face Llama 3.1 8B Instruct model to generate personalized travel plans.

### 🗺️ Google Maps Integration
The application provides Google Maps search links for places mentioned in the itinerary.

### 🛡️ Safety Suggestions
The generated itinerary includes basic travel safety notes.

### 🆓 Free and Low-Cost Options
The AI suggests affordable activities suitable for students.

## 🛠️ Technologies Used

- Python
- Gradio
- Hugging Face
- Llama 3.1 8B Instruct
- Requests
- Google Maps
- Google Colab

## 🔄 How It Works

1. The user enters the destination.
2. The user enters the travel budget in INR.
3. The user provides the start and end dates.
4. The user enters their interests.
5. The application calculates the trip duration.
6. A customized prompt is created from the user's requirements.
7. The prompt is sent to the Hugging Face model.
8. The AI generates the travel itinerary.
9. Places are identified from the generated itinerary.
10. Google Maps links are created for the identified places.
11. The final itinerary is displayed through the Gradio interface.

## 🖥️ User Inputs

The application accepts:

- Destination
- Budget (INR)
- Start Date
- End Date
- Interests

## 📋 Example

### Input

**Destination:** Delhi  
**Budget:** ₹15,000  
**Travel Dates:** 16 January 2026 – 18 January 2026  
**Interest:** History

### Output

The application generates:

- Must-see places
- Day-by-day itinerary
- Estimated daily cost
- Local transport tips
- Safety notes
- Free or low-cost activities
- Google Maps links

