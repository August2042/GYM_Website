# GYM_Website

A web-based project for managing and showcasing gym services, trainers, workout plans, and client information.

## Features

- **About the Gym**: Information about the gym, facilities, and mission.
- **Trainers**: Profiles and images of trainers.
- **Workout Plans**: Details of different workout boxes and routines.
- **Client Showcase**: Testimonials and client images.
- **Media Section**: Gallery with gym-related images.
- **Project Info**: Additional details in `PROJECT_ABOUT.html` and client information in `PROJECT_CLIENT.html`.

## File Overview

- `PROJECT_ABOUT.html`: About the project and gym.
- `PROJECT_CLIENT.html`: Client showcase and testimonials.
- Multiple image files (`.jpeg`, `.jpg`, `.png`, `.avif`): Used for trainers, clients, workouts, and media.
- `phtotoshop.html`: Possibly a gallery or related page.

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/August2042/GYM_Website.git
   ```
2. Open the HTML files in your browser to explore the content.

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License

This project is open source. See the repository for license details.

## Deploy to Netlify

You can deploy this static site to Netlify in two easy ways.

1) Deploy from your Git repository (recommended)

- Push this repository to GitHub (or GitLab/Bitbucket).
- In Netlify, choose "New site from Git" and connect your Git provider.
- Select the `August2042/GYM_Website` repository and the `main` branch.
- For build settings leave the build command empty and set the publish directory to `.` (the repository root).
- Click "Deploy site".

2) Direct deploy (quick drag-and-drop or Netlify CLI)

- Quick: Zip the repository files (or the HTML files) and drag-and-drop the folder on the Netlify Sites dashboard under "Sites -> Add new site -> Deploy manually".
- CLI: Install the Netlify CLI and run `netlify deploy --dir=.` from the project root. Use the `--prod` flag to publish a production deploy.

Notes
- This repo is a static site made of HTML and images; no build tools are required.
- The included `netlify.toml` sets the publish directory to the project root. Adjust it if you later add a build step or move files into a subfolder.

