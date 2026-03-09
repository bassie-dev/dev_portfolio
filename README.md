############################################################
# REPOSITORY: devportfolio 💼
############################################################

In this project, you are going to build your personal developer portfolio.

But this time, you will build it the correct developer way:
You will build it BRANCH BY BRANCH.

Each branch represents a specific task or feature.

You will NOT work directly on main.
You will always create a branch, complete the task, push it, and open a Pull Request.

############################################################
# STEP 1: FORK THE REPOSITORY
############################################################

1. Go to:
   https://github.com/Kgomotso196/devportfolio

2. Click "Fork"
3. Make sure it forks to:
   bassie-dev
4. Click "Create fork"

Now go to your fork:

   https://github.com/bassie-dev/devportfolio

############################################################
# STEP 2: CLONE YOUR FORK
############################################################

Open VSCode → Open Terminal

Move into your work folder:

   cd Desktop
   cd projects

Clone your fork:

   git clone https://github.com/bassie-dev/devportfolio.git

Go inside it:

   cd devportfolio

############################################################
# IMPORTANT RULE FOR THIS PROJECT
############################################################

For EVERY new task:

1. Create a new branch
2. Work inside that branch
3. git add .
4. git commit -m "message"
5. git push --set-upstream origin branch-name
6. Open Pull Request
7. Merge into main
8. Pull latest main before starting next branch

############################################################
# BRANCH 1: understanding-figma
############################################################

Create the branch:

   git checkout -b understanding-figma

What this branch is for:

- Go to https://figma.com
- Create a free account
- Search for "developer portfolio template"
- Choose a simple and clean design
- Study:
  - Layout
  - Colors
  - Font style
  - Sections
  - Spacing

Now create your project structure:

Inside VSCode, create:

   index.html

Add basic HTML structure:

   <!DOCTYPE html>
   <html>
     <head>
       <title>My Portfolio</title>
     </head>
     <body>
       <h1>My Name</h1>
     </body>
   </html>

Save.

Then:

   git add .
   git commit -m "understanding figma and basic structure"
   git push --set-upstream origin understanding-figma

Go to GitHub → Open Pull Request → Merge.

After merging, pull latest main:

   git checkout main
   git pull origin main

############################################################
# BRANCH 2: hero-section
############################################################

Create branch:

   git checkout -b hero-section

Now build the hero section based on your Figma design.

Hero section should include:

- Your full name
- A short description (example: Full Stack Developer)
- A button (example: Contact Me)

Edit index.html and add those elements.

Then:

   git add .
   git commit -m "added hero section"
   git push --set-upstream origin hero-section

Open Pull Request → Merge → Pull latest main.

############################################################
# BRANCH 3: about-me
############################################################

Create branch:

   git checkout -b about-me

Add:

- About me section
- Short paragraph about yourself
- Your skills (HTML, CSS, JavaScript, etc.)

Commit and push:

   git add .
   git commit -m "added about me section"
   git push --set-upstream origin about-me

Open Pull Request → Merge → Pull main.

############################################################
# BRANCH 4: projects-section
############################################################

Create branch:

   git checkout -b projects-section

Add:

- A section showing your projects
- Project name
- Short description
- Link (even if it's placeholder)

Commit and push:

   git add .
   git commit -m "added projects section"
   git push --set-upstream origin projects-section

Open Pull Request → Merge → Pull main.

############################################################
# BRANCH 5: contact-details
############################################################

Create branch:

   git checkout -b contact-details

Add:

- Email
- Phone number
- LinkedIn link
- GitHub link

Example:

   <h2>Contact Me</h2>
   <p>Email: example@email.com</p>

Commit and push:

   git add .
   git commit -m "added contact details"
   git push --set-upstream origin contact-details

Open Pull Request → Merge → Pull main.

############################################################
# BRANCH 6: styling-with-css
############################################################

Create branch:

   git checkout -b styling-with-css

Create a CSS file:

   touch style.css

Link it inside index.html:

   <link rel="stylesheet" href="style.css">

Add:

- Colors from Figma
- Font styles
- Layout spacing
- Section alignment

Commit and push:

   git add .
   git commit -m "added styling"
   git push --set-upstream origin styling-with-css

Open Pull Request → Merge → Pull main.

############################################################
# BRANCH 7: final-polish
############################################################

Create branch:

   git checkout -b final-polish

Improve:

- Spacing
- Responsive layout
- Fix mistakes
- Clean structure

Then:

   git add .
   git commit -m "final improvements"
   git push --set-upstream origin final-polish

Open Pull Request → Merge.

############################################################
# PROJECT COMPLETE 🎉
############################################################

You have now:

- Used Figma for planning
- Built your portfolio section by section
- Worked with branches properly
- Opened and merged multiple pull requests
- Followed real developer workflow

This is how real-world development works.

Well done 💼🚀
