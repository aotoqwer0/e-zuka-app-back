# Battle'n'Chu Backend

## Overview
**Battle'n'Chu** is an innovative social networking application designed to address key challenges in modern online communication—such as cyberbullying, misinformation, and the rapid spread of fake news. This backend repository forms the core of the application, managing data, processing user interactions, and powering the unique "debate" feature where users can publicly challenge the veracity of posts. An AI-based evaluation system processes these debates (レスバトル) to adjust user ratings and promote credible information sharing.

## Features
- **Debate (Battle) Mechanism:**  
  Enables users to initiate and participate in public debates regarding the accuracy of posted content. An integrated AI system evaluates debate outcomes to adjust user ratings.

- **User Rating System:**  
  Dynamically adjusts user credibility based on debate performance, encouraging honest and factual interactions.

- **Comprehensive RESTful API:**  
  Provides endpoints for user management, post operations, debate handling, and notification services.

- **Data Management:**  
  Interfaces with a reliable database (e.g., MongoDB) to manage user data, posts, debates, and other critical records.

## Technology Stack
- **Server Environment:** Node.js ,python
- **Framework:** Express 
- **Database:** MongoDB
- **AI Integration:** Connected to an AI evaluation service for real-time content verification.
