Here's a complete walkthrough for this exam, broken into the same four parts. Replace placeholders like `[Your Name]`, `[Your Program]`, etc. with your actual info.

## Part A — Project Setup and Initial Commit

**1. Create your folder and enter it**
```bash
mkdir lastname_firstname_midterm_git
cd lastname_firstname_midterm_git
```

**2. Create the three files**
```bash
touch index.html style.css README.md
```

**3. Fill in `index.html`**
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Student Profile</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <h1>[Your Full Name]</h1>
  <p>I am an IT student passionate about learning new technologies and building software that solves real-world problems. I enjoy exploring web development and improving my programming skills.</p>

  <section id="skills">
    <h2>Skills</h2>
    <ul>
      <li>HTML & CSS</li>
      <li>JavaScript</li>
      <li>Git & GitHub</li>
    </ul>
  </section>
</body>
</html>
```

**4. Fill in `style.css`**
```css
body {
  font-family: Arial, sans-serif;
  background-color: #f4f4f4;
  margin: 40px;
}

h1 {
  color: #2c3e50;
}

p {
  color: #333;
  line-height: 1.6;
}

#skills {
  background-color: #fff;
  padding: 15px;
  border-radius: 8px;
}
```

**5. Fill in `README.md`**
```markdown
# Student Profile Project

This is a simple student profile webpage created for the IT 332 midterm examination on Git and GitHub.

**Student:** [Your Full Name]
**Course & Section:** IT 332 - [Your Section]
```

**6. Initialize Git, stage, and commit**
```bash
git init
git add .
git commit -m "Initial project setup"
```

## Part B — Status, Log, and GitHub Push

**1. Check status and log**
```bash
git status
git log --oneline
```
📸 Screenshot both outputs.

**2. Create the GitHub repo**
Go to GitHub → New Repository → name it `lastname-firstname-midterm-git` → set to **Public** → don't initialize with README (you already have one) → Create.

**3. Connect local repo to GitHub**
```bash
git remote add origin https://github.com/yourusername/lastname-firstname-midterm-git.git
git branch -M main
```

**4. Push**
```bash
git push -u origin main
```
📸 Screenshot the successful push, and the GitHub page showing your uploaded files.

## Part C — Branching and Feature Update

**1. Create and switch to a new branch**
```bash
git checkout -b feature-profile-update
```
📸 Screenshot terminal showing the branch was created (run `git branch` to confirm).

**2. Add the "About Me" section to `index.html`** (before `</body>`)
```html
  <section id="about-me">
    <h2>About Me</h2>
    <p><strong>Year Level:</strong> [Your Year Level]</p>
    <p><strong>Program:</strong> [Your Program]</p>
    <p><strong>Tech Goal:</strong> I want to become proficient in full-stack development and contribute to open-source projects.</p>
  </section>
```
📸 Screenshot the updated file.

**3. Add styling in `style.css`**
```css
#about-me {
  margin-top: 20px;
  padding: 15px;
  background-color: #eaf6ff;
  border-left: 4px solid #2c3e50;
  border-radius: 6px;
}
```

**4. Stage and commit**
```bash
git add .
git commit -m "Add profile update section"
```

**5. Switch back to main and merge**
```bash
git checkout main
git merge feature-profile-update
```
📸 Screenshot the successful merge output.

**6. Push updated main**
```bash
git push origin main
```
📸 Screenshot the GitHub repo showing the final updated files.

## Part D — Final README Reflection

Add this to the bottom of `README.md`:

```markdown
## Midterm Examination Reflection

**1. What is Git used for?**
Git is a version control system used to track changes in code over time. It allows developers to save progress, revert to previous versions, and collaborate without overwriting each other's work.

**2. What is the difference between Git and GitHub?**
Git is the tool that manages version control locally on a computer. GitHub is an online platform that hosts Git repositories, making it easier to share code and collaborate with others.

**3. Why is branching useful?**
Branching lets developers work on new features or fixes without affecting the main codebase. It keeps the project stable while allowing experimentation and parallel development.

**4. What command did you use to upload your local commits to GitHub?**
I used `git push origin main` to upload my local commits to the GitHub repository.

**5. What did you learn from this activity?**
I learned how to set up a Git repository, connect it to GitHub, and manage changes through branching and merging. This activity helped me understand how real-world teams collaborate on code.
```

Commit and push:
```bash
git add README.md
git commit -m "Add midterm examination reflection"
git push origin main
```

## Final Checklist Before Submission
- [ ] Repo is public and named correctly
- [ ] `index.html`, `style.css`, `README.md` all present and updated
- [ ] All 4 required commits exist in history
- [ ] All screenshots gathered into one PDF
- [ ] GitHub repo link ready to submit

Want me to generate the actual PDF-ready screenshot template or double-check your commit messages match exactly what's required?
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Student Profile</title>
  <link rel="stylesheet" href="style.css">
</head>

<body>
  <header>
    <h1>Bien Paulo M. Hipolito</h1>
  </header>
  <div class="pharagraph">
    <p>I am a dedicated student pursuing a degree in Bachelor of Science in Information Technology.
      My goal is to become a skilled IT professional, specializing in software development and cybersecurity. I am passionate about learning new technologies and applying them to solve real-world problems.</p>
  </div>
  </body>

  <section id="skills">
    <h2>Skills</h2>
    <ul>
      <li>HTML & CSS</li>
      <li>JavaScript</li>
      <li>Git & GitHub</li>
      <li>Problem Solving</li>
    
    </ul>
  </section>
</body>
</html>
</html>

Hipolito_BienPaulo_midterm_git
Student:Bien Paulo M. Hipolito
Course & Section: IT 332 -3303
body {
  font-family: Arial, sans-serif;
  background-color: #f4f4f4;
  margin: 0px;
}

h1 {
  color: #2c3e50;
}

p {
  color: #333;
  line-height: 1.6;
}

#skills {
  background-color: #f5f5f5;
  padding: 15px;
  border-radius: 8px;
  text-align: center;
}
  .pharagraph {
    max-width: 2000px;
    margin: 0 auto;
    padding: 20px;
    align-items: center;
    background-color: rgb(243, 243, 243);
    color:rgb(0, 0, 0);
  }
  h1 {
    font-size: 48px;
    margin-bottom: 20px;
    text-align: center;
    background-color: black ;
    color: aliceblue;
    margin-top: auto;
    padding: 20px;
  }
  p {
    font-size: 34px;
    line-height: 1.5;
    margin-bottom: 10px;
  }
  .pharagraph {
    max-width: 2000px;
    margin: 0 auto;
    padding: 20px;
    align-items: center;
    background-color: rgb(243, 243, 243);
    color:rgb(0, 0, 0);
  }
  h1 {
    font-size: 48px;
    margin-bottom: 20px;
    text-align: center;
    background-color: black ;
    color: aliceblue;
    margin-top: auto;
    padding: 20px;
  }
  p {
    font-size: 34px;
    line-height: 1.5;
    margin-bottom: 10px;
  }
ul {
  font-size: 20px;
  margin-bottom: 5px;
  align-items: baseline;
}