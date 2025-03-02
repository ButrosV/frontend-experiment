# Frontend Mentor - Blog Preview Card Solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [Installation](#installation)
- [Usage](#usage)
- [My process](#my-process)
  - [Built with](#built-with)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview
### The challenge
Users should be able to:

See hover and focus states for all interactive elements on the page.

### Description
This project involves building a blog preview card that closely follows the design provided in the challenge. The card displays an article's title, description, publication date, and author's avatar. The design includes interactive elements, such as a hover effect on the button and focus states on clickable elements.

The goal is to practice basic HTML and CSS concepts like semantic markup, layout techniques, and hover/focus interactions.

The design provided in the challenge includes both mobile and desktop views, and the layout needs to be responsive, with the card adjusting itself based on screen size. The card also includes an image, a button, and a footer with the author's avatar and name.

This project is deployed automatically using GitHub Actions to Vercel. The deployment process triggers whenever changes are pushed to the main branch of the repository. The GitHub Actions workflow installs the necessary dependencies, builds the project, and deploys it to Vercel, making it accessible online.

#### Project structure:

```bash
.
├── .github
│   └── workflows
├── assets
│   ├── fonts
│   │   └── static
│   └── images
```

### Links

- Live Site URL: [Blog Preview Card Live](https://frontend-experiment-rosy.vercel.app/). Live site link may expire as vercel app access token to my GitHub project is limited.

## Installation

To use this project, you can either clone the repository or download the zip files.

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/blog-preview-card.git
   ```

2. Navigate into the project directory:
   ```bash
   cd blog-preview-card
   ```

3. Install the necessary dependencies:
   ```bash
   npm install
   ```

## Usage

To view the project locally, run the following command to start the development server:

```bash
npm start
```

Then, open your browser and go to `http://localhost:3000` to see the project running!

**IMPORTANT:** Ensure that you have Node.js and npm installed. If you run into any issues while setting up, feel free to reach out for support.

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- [Styled Components](https://styled-components.com/) - For styles
- [GitHub Actions](https://docs.github.com/en/actions) - For automating deployment to Vercel
- [Vercel](https://vercel.com/) - For deploying the project

### What I learned

Through this project, I learned to implement hover states, manage responsive design, and effectively use Flexbox and CSS Grid to lay out elements. 

### Continued development

I plan to improve the interactivity of the blog card by adding animations and further enhancing accessibility.

### Useful resources

- [Frontend Mentor Community](https://www.frontendmentor.io/community) - For helpful discussions and feedback.

## Author

- [Butros](https://peterisv.wordpress.com/) - Coded this project.

## Acknowledgments

A big thanks to Frontend Mentor for the challenge and all the resources they provided.
