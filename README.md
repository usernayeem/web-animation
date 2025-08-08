# Web Animation
## Overview
Web Animation is a dependency-free HTML/CSS/JS project: a responsive city scene with CSS keyframe motion (road/background), Lottie vehicles, and a day/night toggle persisted via localStorage

**Live Preview:**  
[https://usernayeem.github.io/web-animation/](https://usernayeem.github.io/web-animation/)
---

## Table of Contents

- [Project Description](#project-description)
- [Features](#features)
- [Technology Used](#technology-used)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [Testing](#testing)
- [License](#license)
- [Contact / Support](#contact--support)

---

## Project Description

**Web Animation** is a responsive and visually engaging web project that showcases a dynamic city scene using pure HTML, CSS, and JavaScript. The animation features moving vehicles on a scrolling road against a cityscape background, with an interactive toggle for a day and night theme. The project serves as a demonstration of modern front-end techniques, including CSS keyframe animations, responsive design, and JavaScript-based user interaction.

---

## Features

- **Modern Responsive Design:** Fully responsive layout that adapts to various screen sizes, from mobile devices to desktops.
- **CSS Animations:** Smooth, continuous animations for vehicles, the road, and the background using CSS Keyframes.
- **LottieFiles Integration:** Utilizes high-quality, lightweight vector animations for the vehicles.
- **Interactive Theme Toggle:** A clickable sun/moon icon allows users to switch between a bright day theme and a dark night theme.
- **Persistent Theme:** The user's selected theme (light or dark) is saved in the browser's `localStorage` for a consistent experience across sessions.
- **Zero Dependencies:** Built with vanilla HTML, CSS, and JavaScript, requiring no external libraries or frameworks to be installed.

---

## Technology Used

- **HTML5** – For the structure and content of the web page.
- **CSS3** – For styling, layout, responsiveness (media queries), and all keyframe animations.
- **Vanilla JavaScript** – For handling user interactions, such as the theme-switching functionality.
- **LottieFiles** – For embedding scalable and lightweight vector animations.

---

## Installation

### Prerequisites

- [Git](https://git-scm.com/) (to clone the repository)
- A modern web browser (Chrome, Edge, Firefox, Safari, etc.)

### Steps

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/usernayeem/web-animation.git
    ```

2.  **Navigate to the project directory:**
    ```bash
    cd web-animation
    ```

3.  **Open the application:**
    Simply open the `index.html` file in your web browser to view the animation.

---

## Usage

- **Viewing the Animation:** Open the `index.html` file in a supported web browser to see the animation in action.
- **Switching Themes:** Click on the sun (in day mode) or the moon (in night mode) at the top of the screen to toggle between the two visual themes.
- **Responsive Viewing:** Resize your browser window to see how the layout and animations adapt to different screen sizes.

---

## Configuration

- **No configuration required.** This project is self-contained and does not require any API keys or environment variables to run.
- **Styling:** All styles and animations can be customized by modifying the `style.css` file.

---

## Contributing

Contributions are welcome! If you would like to contribute to this project, follow these steps:

1.  **Fork the Repository**:
    -   Navigate to the repository you want to contribute to.
    -   Click the **Fork** button in the upper right corner to create a personal copy of the project in your GitHub account.

2.  **Clone the Forked Repository**:
    -   Open your forked repository on GitHub.
    -   Click the "Code" button to get the HTTPS or SSH URL of your forked repository.
    -   Open your terminal or command prompt.
    -   Use the `git clone` command followed by the URL you copied to clone the repository to your local machine:
        ```bash
        git clone https://github.com/yourusername/web-animation.git
        ```
        Replace `yourusername` with your own Github username.
    -   Navigate into the cloned repository directory:
        ```bash
        cd web-animation
        ```

3.  **Create a New Branch**: Switch to a new branch where you'll make your changes. You can do this using the following command:
    ```bash
    git checkout -b my-branch
    ```
    Replace `my-branch` with a branch name that describes your work.

4.  **Make Your Changes**: Make the necessary changes to the codebase. You can add, modify, or delete files as needed.

5.  **Stage Your Changes**: You can use `git add <filename>` to stage specific files or `git add .` to stage all changes.
    ```bash
    git add .
    ```

6.  **Commit Your Changes**: Commit your staged changes with a descriptive message. Follow the imperative style for commit messages (e.g., “Fix bug” instead of “Fixed bug”). For example:
    ```bash
    git commit -m "my commit message"
    ```
    Replace `my commit message` with a meaningful message for your commit.

7.  **Push to Your Branch**: Push your changes to the branch you created:
    ```bash
    git push -u origin my-branch
    ```
    Replace `my-branch` with your branch name.

8.  **Submit a Pull Request**:
    -   Navigate to your forked repository on GitHub.
    -   Click the "Compare & pull request" button.
    -   Review the changes you're proposing and ensure they are accurate.
    -   Add a descriptive title and a detailed description of your contribution.
    -   Click the "Create pull request" button to submit your contribution for review.

---

## Testing

- This project does not include an automated test suite. Manual testing can be performed as follows:
    -   Open `index.html` in different web browsers (e.g., Chrome, Firefox, Safari) to ensure cross-browser compatibility.
    -   Test the day/night theme toggle to confirm it functions correctly and saves the state to `localStorage`.
    -   Check responsiveness by resizing the browser window or using browser developer tools to emulate different device sizes.

---

## License

This project is licensed under the [MIT](LICENSE) License.

---

## Contact / Support

-   **Author:** [Md Nayeem](https://www.github.com/usernayeem)
-   **Repository:** [github.com/usernayeem/web-animation](https://github.com/usernayeem/web-animation)
-   **Issues:** Please use the [GitHub Issues page](https://github.com/usernayeem/web-animation/issues) for bug reports or feature requests.
