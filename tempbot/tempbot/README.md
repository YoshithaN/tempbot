# tempbot# Buddy Bot - Mood-Based Chatbot

## Overview

Buddy Bot is an interactive chatbot with dynamic personality changes based on selected "temperature" moods. Users can adjust the bot's mood from freezing/grumpy to scorching/angry, with each state affecting both the visual interface and the bot's responses.

## Features

- **6 Mood States**:
  - 🥶 Freezing (Grumpy)
  - 😰 Cold (Uncomfortable)
  - 😊 Comfortable (Happy - Default)
  - 😅 Warm (Restless)
  - 😤 Hot (Irritable)
  - 😡 Scorching (Angry)

- **Dynamic Visual Effects**:
  - Unique background animations for each mood (snow, rain, hearts, steam, fire, etc.)
  - Themed color schemes that change with mood
  - Animated particle effects

- **Personality Responses**:
  - Bot responses adapt to current mood
  - Different vocabulary and punctuation styles
  - Context-aware replies

- **Interactive UI**:
  - Clean chat interface with message bubbles
  - Typing indicators
  - Responsive design

## How to Use

1. Open the HTML file in any modern web browser
2. Use the emoji selector to change the bot's mood
3. Type messages in the input field and press Enter or click the send button
4. Observe how the bot's responses change based on selected mood

## Technical Details

- **Frontend**: Pure HTML, CSS, and JavaScript (no frameworks)
- **Animations**: CSS animations and JavaScript-generated particles
- **Responsive Design**: Works on desktop and mobile devices
- **No Backend**: All processing happens client-side

## Code Structure

- **HTML**: Contains the chat interface structure
- **CSS**: Styling for all components and animations
- **JavaScript**: Chatbot logic, response generation, and animation control

Key JavaScript components:
- `Chatbot` class handles all functionality
- Temperature mood system with different response patterns
- Background animation system for each mood
- Response generation based on message content and current mood

## Customization

You can easily customize:
- Colors in the CSS
- Responses in the JavaScript `responses` object
- Animations by modifying the particle generation functions
- Personality traits by editing the `temperatureMoods` object

## Browser Support

Tested on:
- Chrome (latest)
- Firefox (latest)
- Edge (latest)
- Safari (latest)

## License

This project is open-source and available under the MIT License.

## Future Improvements

Potential enhancements:
- Add more mood options
- Implement local storage for conversation history
- Add more sophisticated NLP for better responses
- Create a backend for persistent conversations
- Add user authentication for personalized experiences

