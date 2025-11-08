# AI STL Generator

A free web application that generates 3D printable STL files from text descriptions using AI.

## Features
- Generate STL files from natural language descriptions
- Adjustable detail levels (Low, Medium, High)
- Handles complex prompts for organic shapes, mechanical parts, and decorative objects
- Instant download of printable STL files
- No installation required - runs entirely in your browser

## Deployment on Netlify

### Option 1: Drag and Drop (Easiest)
1. Go to [https://app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag the entire `stl-generator-netlify` folder onto the page
3. Your site will be live instantly with a free `.netlify.app` domain!

### Option 2: Connect to Git
1. Create a new repository on GitHub
2. Upload these files to the repository
3. Go to [Netlify](https://app.netlify.com)
4. Click "Add new site" → "Import an existing project"
5. Connect your GitHub repository
6. Deploy!

## Free Hosting
- Netlify provides 100GB bandwidth/month for free
- Free `.netlify.app` subdomain (e.g., `mystlgenerator.netlify.app`)
- Automatic HTTPS
- No credit card required

## How to Use
1. Enter a description of the 3D object you want
2. Select the detail level
3. Click "Generate STL File"
4. Download and import into your 3D printing software

## Examples
- "A decorative vase with spiral patterns, 80mm tall"
- "A gear with 20 teeth, 40mm diameter"
- "A dragon figurine in an attacking pose"
- "A smartphone stand with 45 degree angle"

## Tech Stack
- React 18
- Tailwind CSS
- Claude Sonnet 4 API
- Pure HTML/CSS/JavaScript (no build step needed)

## License
Free to use and modify!