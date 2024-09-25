# ExploreEase - Comprehensive Trip Planner

ExploreEase is an innovative chatbot designed to revolutionize the travel planning experience by using **Kruskal's algorithm** to optimize travel routes between multiple destinations and offer personalized travel recommendations based on user preferences.

## Features

- **Optimized Travel Routes**: Uses Kruskal's algorithm to calculate the shortest and most efficient travel routes.
- **Personalized Recommendations**: Provides tailored suggestions for attractions, accommodations, and dining based on user interests.
- **Chatbot Interface**: User-friendly chatbot interface powered by **Ollama** for natural language processing.
- **Real-Time Data Integration**: Capable of integrating real-time data such as traffic and weather for future updates.
- **Responsive UI**: Built with HTML, CSS, and JavaScript, the platform is responsive and accessible on any device.

## Technology Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js
- **Algorithms**: Kruskal's algorithm for route optimization
- **Natural Language Processing**: Ollama
- **Database**: NoSQL for storing user data

## Getting Started

### Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/en/) 
- npm (Node package manager)

# Steps to Run

1. Clone the repository.
   ```
   git clone https://github.com/your-repo/ExploreEase.git
   ```

2. Ensure you have Node.js installed.
3. Change directory (cd) into the main folder.
```
cd ExploreEase
```
4. Run `npm install` to install dependencies.
5. Setup Ollama server:
   - Run the following commands in your terminal:
     ```
     curl -fsSL https://ollama.com/install.sh | sh
     ollama serve
     ```
   - In a new terminal, run:
     ```
     ollama pull gemma2
     ollama pull phi3:mini
     ollama create getcity -f ./Modelfile
     ```
6. Run `npm start` to start the application.

## Key Functionalities

- **Route Optimization**: Users can input multiple destinations, and the system will visualize and optimize the travel routes using Kruskal’s algorithm.
- **Interactive Chatbot**: Engage with the chatbot to receive personalized travel recommendations based on user interests.
- **Itinerary Management**: Manage, save, and share itineraries directly from the platform.

## Future Enhancements

- Real-time traffic and weather data integration.
- Mobile application development.
- Enhanced recommendation engine using machine learning for improved user preferences.
