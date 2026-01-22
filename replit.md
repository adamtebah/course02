# 수능특강 수학2 (Korean Math Study Materials)

## Overview
This is a static HTML/CSS website containing Korean math study materials for the "수능특강 수학2" (CSAT Math 2 Special Lecture) curriculum. It serves as a learning resource hub with various chapters covering mathematical concepts.

## Project Structure
- `index.html` - Main landing page with navigation to all chapters
- `css/` - Stylesheets
- `images/` - Graphic resources for math problems
- `materials/` - Individual HTML pages for each learning module

## Tech Stack
- Static HTML/CSS
- Tailwind CSS (loaded via CDN)
- Python HTTP server for local development

## Running the Project
The project runs on port 5000 using Python's built-in HTTP server:
```
python3 -m http.server 5000 --bind 0.0.0.0
```

## Deployment
Configured as a static site with the root directory as the public directory.
