# AI STL Generator with Web Search

A free web application that generates 3D printable STL files from text descriptions using AI **with web search capabilities** for enhanced accuracy.

## 🆕 New Features
- **Web Search Integration**: AI can now search the internet for real-world dimensions, proportions, and technical specifications
- **Improved Accuracy**: Real-world objects are modeled with correct dimensions from online sources
- **Enhanced Detail**: Better understanding of complex objects through web research
- **Toggle Option**: Enable/disable web search based on your needs

## Features
- Generate STL files from natural language descriptions
- **Web-enhanced AI** searches for reference information automatically
- Adjustable detail levels (Low, Medium, High)
- Handles complex prompts for organic shapes, mechanical parts, and decorative objects
- Instant download of printable STL files
- No installation required - runs entirely in your browser

## Perfect For
- **Real-world objects**: The AI searches for actual dimensions (Eiffel Tower, cars, buildings)
- **Historical artifacts**: Accurate proportions based on research
- **Animals & anatomy**: Scientifically accurate models
- **Mechanical parts**: Standard sizes and specifications
- **Architectural landmarks**: Historically accurate details

## Deployment on Netlify

### Option 1: Drag and Drop (Easiest)
1. Go to [https://app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag the entire `stl-generator-netlify` folder onto the page
3. Your site will be live instantly with a free `.netlify.app` domain!

### Option 2: Connect to Git
1. Create a new repository on GitHub (or use existing `ai-stl` repository)
2. Upload/push these files to the repository
3. Go to [Netlify](https://app.netlify.com)
4. Click "Add new site" → "Import an existing project"
5. Connect your GitHub repository
6. Deploy!

**No build command needed!** This is a static HTML site.

## Free Hosting
- Netlify provides 100GB bandwidth/month for free
- Free `.netlify.app` subdomain (e.g., `mystlgenerator.netlify.app`)
- Automatic HTTPS
- No credit card required

## How to Use
1. Enter a description of the 3D object you want
2. Check "Enable Web Search" for real-world objects (recommended)
3. Select the detail level
4. Click "Generate STL File"
5. AI searches the web for accurate information
6. Download and import into your 3D printing software

## Web Search Examples
- "Eiffel Tower replica" - AI finds real height and proportions
- "Tesla Model 3 miniature" - AI researches car dimensions
- "Human skull anatomically accurate" - AI searches medical references
- "Boeing 747 airplane model" - AI finds aircraft specifications
- "Roman Colosseum with accurate details" - AI researches architecture

## Traditional Examples (Without Web Search)
- "A decorative vase with spiral patterns, 80mm tall"
- "A gear with 20 teeth, 40mm diameter"
- "A smartphone stand with 45 degree angle"
- "Celtic knot pendant, 30mm diameter"

## Tech Stack
- React 18
- Tailwind CSS
- Claude Sonnet 4 API with Web Search Tool
- Pure HTML/CSS/JavaScript (no build step needed)

## How Web Search Works
When enabled, the AI:
1. Searches the internet for reference information about your object
2. Finds real-world dimensions, proportions, and technical specs
3. Uses this information to create a more accurate 3D model
4. Generates STL with proper scale and details

## License
Free to use and modify!

---

## Push to Your GitHub Repository

To update your `ai-stl` repository:

```bash
cd C:\Users\liamb\Downloads\stl-generator-netlify

# Initialize git if needed
git init

# Add your repository as remote
git remote add origin https://github.com/YOUR_USERNAME/ai-stl.git

# Add all files
git add .

# Commit changes
git commit -m "Add web search capabilities for enhanced accuracy"

# Push to GitHub
git push -u origin main
```

Replace `YOUR_USERNAME` with your actual GitHub username!