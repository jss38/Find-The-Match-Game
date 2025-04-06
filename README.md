# Find The Match Game

An Android memory card matching game where players need to find matching images or words across cards in the fastest time possible.

## Features

- Multiple difficulty levels (Easy, Medium, Hard)
- Various game modes including images and words
- High score tracking
- Customizable card options
- Flickr image integration for custom card images
- Upload and manage your own images
- Sound effects for game interactions

## Getting Started

### Prerequisites

- Android Studio 4.0+
- Android SDK 21+
- Java 8+

### Installation

1. Clone the repository
   ```
   git clone https://github.com/jss38/Find-The-Match-Game.git
   ```
2. Open the project in Android Studio
3. Build and run the application on an emulator or physical device

## How to Play

1. From the main menu, select "Play Game"
2. Choose your preferred game options (difficulty, card set, etc.)
3. The game displays two cards: one from the draw pile and one from the discard pile
4. Find matching images/words between the two cards and tap on them
5. Match all cards as quickly as possible to achieve a high score
6. Your score is based on completion time

## Game Modes

- **Images Only**: Match identical images across cards
- **Words/Images**: Match words with their corresponding images
- **Custom Images**: Use your own uploaded images or Flickr images

## Development

The application follows the MVC (Model-View-Controller) architecture:

- **Model**: Contains game logic, data structures, and state management
- **View**: UI components and layouts
- **Controller**: Activity classes that handle user interactions

## Acknowledgments

- CMPT 276 course at Simon Fraser University
- Flickr API for image integration
