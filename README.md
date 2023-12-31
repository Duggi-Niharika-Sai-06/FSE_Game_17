# Emojination: Memory Adventures
## Link to Website
- [Proemoji](https://proemoji.netlify.app/)

## Table of Contents
- [Game Objective and Rules](#game-objective-and-rules)
- [Technology Stack Used](#technology-stack-used)
- [Setup and Deployment Instructions](#setup-and-deployment-instructions)
- [Credits](#credits)
- [Reflection](#reflection)

## Game Objective and Rules

### Game Objective:
**Emojination**: Memory Adventures is an engaging memory and matching game with a twist. The goal is to click on emojis and achieve the highest score possible while managing a limited number of lives.

### Rules:
- Players start with a set number of lives, e.g., 5, at the beginning of each game session.
- Click an emoji to reveal it.
- If the clicked emoji is different from any previously clicked emoji, the player's score increases by 1.
- Keep revealing emojis and increasing your score by avoiding duplicates.
- Be mindful of your remaining lives, as each mistake will cost you a life.

### Win Condition:
- If you click on all emojis exactly once within the lives limit, you achieve victory!
- In this case, the game status will display your best score, which is equal to the top score.

### Losing Condition:
- If you click on an emoji that you've previously selected or run out of lives, you lose the game.
- In this situation, the game status shows your current score, and you have the option to play again.

### Lives System:
- Players start with a set number of lives, e.g., 5, at the beginning of each game session.
- The number of remaining lives is displayed on the game interface.
- When you make a mistake, such as clicking on a previously chosen emoji, you lose a life.
- The game visually indicates the loss of a life, for example, by removing a heart icon or displaying a decreasing life count.
- If you run out of lives, the game progresses to a "Game Over" condition.

## Sound Effects

- **Correct Selection Sound**: A sound effect is played when the player selects an emoji correctly.

- **Incorrect Selection Sound**: A different sound effect is played when the player makes an incorrect selection, such as clicking on a previously chosen emoji or running out of lives.

These sound effects enhance the gaming experience, providing audio feedback for the player's actions.

## Game Menu and Settings

**Game Modes**:

Emojination: Memory Adventures offers three distinct game modes to cater to players of varying skill levels, each with different grid sizes and emoji counts:

- **Easy Mode**:
    - Grid Size: 4x4
    - Emojis Shuffled Among: 20
    - Description: Easy mode is perfect for beginners, with a 4x4 grid and 20 shuffled emojis to keep the game approachable and enjoyable for new players.

- **Medium Mode**:
    - Grid Size: 6x4
    - Emojis Shuffled Among: 24
    - Description: Medium mode offers a balanced challenge, featuring a 6x4 grid with 24 shuffled emojis to test your memory and matching skills.

- **Hard Mode**:
    - Grid Size: 6x8
    - Emojis Shuffled Among: 48
    - Description: For the ultimate test of memory, hard mode boasts an 6x8 grid with 48 shuffled emojis, providing a high level of difficulty for the most dedicated players.

**Sound Settings**:

The game provides options to control sound effects:

- **Sound On**: By default, sound effects are enabled. You can enjoy the satisfying audio feedback when making correct or incorrect selections.

- **Sound Off**: If you prefer a quiet gaming experience, you can toggle off the sound effects.

The game menu and settings allow you to customize your gaming experience and choose the level of challenge that suits your preferences.


### Score Tracking:
- The game keeps track of your best score, representing your highest score achieved across different game sessions.
- If you achieve a score higher than your previous best score, the top score is updated accordingly.

## Technology Stack Used

- **Frontend Framework**: React.js
- **Styling**: Tailwind CSS
- **Backend Server**: Node.js
- **Version Control**: GitHub and Git
- **Deployment**: Netlify

## Setup and Deployment Instructions

### Setup

1. **Clone the Repository**: To get started, clone the game repository from GitHub.
    ```shell
    git clone https://github.com/Duggi-Niharika-Sai-06/FSE_Game_17.git
    ```

2. **Navigate to the Project Directory**: Change your working directory to the game's project folder.
    ```shell
    cd FSE_Game_17
    ```

3. **Install Project Dependencies**: Install the necessary project dependencies using npm.
    ```shell
    npm install
    ```
## Running the Development Server

To run the development server and test the game locally, follow these steps:

1. Open your terminal or command prompt.

2. Navigate to the project directory where you've cloned the game using the `cd` command. Replace `"path/to/FSE_Game_17"` with the actual path on your system.
   ```shell
   cd path/to/FSE_Game_17

The game will be accessible at http://localhost:3000 in your web browser.

### Deployment
We use Netlify for deployment. To deploy your game to Netlify:
1. Created a Netlify account.
2. Connected your GitHub repository to Netlify.
3. Set up build settings in the Netlify dashboard.
4. Netlify will automatically deploy game whenever changes has been pushed to connected GitHub repository.

## Credits

- React JS
- [GitHub](https://github.com/sobucki/emoji-memory-game)
- [Medium](https://aadaobi.medium.com/building-a-memory-matching-game-in-javascript-48e792c7b563)

## Reflection

### Design and Development Process
**Creating Emojination**: Memory Adventures was an exciting journey. We aimed to build a memory and matching game with a unique twist. Here are some key points from our design and development process:

**Conceptualization**:
- We started by conceptualizing the idea for the game, which was to create a memory and matching game with a unique twist involving emojis. The goal was to make the game engaging and enjoyable for players of all skill levels.

**User Experience Design**:
- We focused on designing an intuitive and user-friendly interface. This included creating the game menu, setting options, and sound controls to provide a seamless gaming experience.

**Game Logic Implementation**:
- Implementing the core game logic was a significant challenge. We had to carefully manage the state to track previously clicked emojis and update the score correctly. This involved defining the rules, win and lose conditions, and lives system.

**Technical Stack Selection**:
- We chose a technology stack that best suited our project. React.js was selected as the frontend framework for managing components and user interactions. Tailwind CSS was used for styling to achieve a clean and responsive design.

**Deployment Strategy**:
- We decided to deploy the game using Netlify. This choice simplified the deployment process, enabling automatic updates with each new commit, making the game accessible to players without complications.

**Iterative Development**:
- The development process involved regular playtesting and iterations to fine-tune the game's mechanics and difficulty levels. User feedback was invaluable in making necessary adjustments.

**Challenges and Solutions**:
- Challenges included complex card animations, initial lives balancing, and automated deployment with Netlify. These were addressed by shifting to CSS-based animations, focusing on core gameplay mechanics, and implementing a custom build configuration for Netlify.

**Documentation and Resources**:
- We relied on documentation and resources provided by the deployment platform (Netlify) when faced with deployment issues. This experience highlighted the importance of understanding the deployment platform and being prepared to adjust configurations as needed.

### Challenges Faced
- **Game Logic**: Implementing the game logic for tracking previously clicked emojis and updating the score correctly was challenging. It required careful management of state and user interactions.

### What Worked
- **React.js**: Using React made it easier to manage game components, states, and interactions. It allowed for a smooth user experience and helped in creating an organized codebase.
- **Tailwind CSS**: Tailwind CSS provided a practical way to style the game, enabling a clean and responsive user interface.
- **Netlify Deployment**: Deploying the game with Netlify simplified the deployment process. It automatically updates the game with every new commit, making it accessible to players without any hassle.

### What Didn't Work
- **Card Animations**: Initially, we attempted to implement card animations directly within the React components, using state changes and CSS-in-JS solutions. However, this approach proved to be complex and led to performance issues.

  **Solutions Implemented**: To resolve these issues, we decided to leverage CSS for card animations. We created a set of CSS classes in an index.css file.

- **Initial Lives Balancing**: Initially, we experimented with a different lives system, but it didn't align with the core mechanics of the game. We chose to focus on the core gameplay mechanics.
- **Automated Deployment with Netlify**: During the initial deployment attempts, we encountered challenges with the automated deployment process using Netlify. The platform didn't configure our project as expected, leading to deployment issues.

  **Issues with Netlify Deployment**: We faced difficulties with Netlify not automatically detecting and configuring our project correctly. The initial deployment resulted in unexpected errors.

  **Solutions Implemented**: To resolve these issues, we needed to set up a custom build configuration using a `netlify.toml` file. This allowed us to define the build commands and specify project-specific settings. Additionally, we had to manage environment variables more effectively for different deployment stages, which required a deeper understanding of Netlify's configuration.

  These adjustments were necessary to ensure a seamless deployment process and match our project requirements.

### Lessons Learned
- Focusing on core gameplay mechanics and simplicity can lead to a more enjoyable user experience.
- Regular playtesting and user feedback are essential for fine-tuning the game's mechanics and difficulty.
- Automated deployment tools like Netlify are powerful but may require specific configurations to align with your project's needs. It's important to have a good understanding of the deployment platform and be prepared to adjust configurations as required.
- Documentation and resources provided by the deployment platform can be invaluable. When we encountered deployment issues, we referred to Netlify's documentation and community forums for guidance.
