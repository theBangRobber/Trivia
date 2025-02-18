# Trivia Game

A fun and interactive trivia game built using **React Native with Expo**. The game tests your knowledge in software engineering (from various tech stacks like HTML, CSS, React, Javascript, Java and React Native) and reacts to device movements using the **accelerometer**.

## Features
- Randomly selected trivia questions
- Interactive answering using device tilt (left/right)
- Score tracking and feedback system
- Limited lives to increase challenge
- Clean and engaging UI

## Game Mechanics
1. The game presents multiple-choice questions.
2. The player answers by tilting the device:
   - Tilt **left** to select option **A**
   - Tilt **right** to select option **B**
3. Correct answers increase the **score**.
4. Incorrect answers reduce the **lives**.
5. The game ends when all lives are lost.
6. A feedback message appears after each answer.
7. Questions are randomly shuffled each time the game starts.

## Dependencies
The game requires the following dependencies to run:

### expo-sensor
- npx expo install expo-sensors

### react-native-svg
- npm install react-native-svg

### react-native-svg-transformer
- npm install react-native-svg-transformer


## Notes
- The accelerometer sensitivity can be adjusted in the `useEffect` hook inside the game logic.
- More questions can be added to the questions.js easily.

## Future Enhancements
- Add a timer for each question.
- Introduce different difficulty levels.
- Implement multiplayer mode.

---
Enjoy the game! 🚀

