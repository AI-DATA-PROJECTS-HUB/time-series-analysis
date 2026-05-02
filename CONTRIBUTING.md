# Contributing a Project

Thank you for sharing your work! Follow the steps below to submit your project.

---

## Before You Begin

Make sure your project:
- [ ] Is your own original work (or clearly credits collaborators)
- [ ] Has a clear, working `README.md`
- [ ] Includes a `requirements.txt` or `environment.yml`
- [ ] Does NOT include datasets over 50MB (link instead)
- [ ] Has clean, commented code

---

## Step-by-Step Submission

### 1. Fork this repository
Click the **Fork** button at the top-right of this page.

### 2. Clone your fork
```bash
git clone https://github.com/YOUR-USERNAME/REPO-NAME.git
cd REPO-NAME
```

### 3. Create your project folder
```bash
mkdir projects/your-project-name
```
Use **lowercase-with-hyphens**. Example: `iris-flower-classifier`

### 4. Required folder structure
```
projects/your-project-name/
├── README.md              ← required
├── notebook.ipynb         ← or main.py / app.py
├── requirements.txt       ← required
├── data/                  ← optional (small samples <5MB only)
└── images/                ← optional screenshots / charts
```

### 5. Project README.md template
```markdown
# Project Title

## Overview
What does this project do? (2-3 sentences)

## Dataset
- Source: [link to dataset]
- Size: X rows × Y columns

## Methods
What techniques or models did you use?

## Results
Metrics, findings, or key takeaways.

## How to Run
\`\`\`bash
pip install -r requirements.txt
jupyter notebook notebook.ipynb
\`\`\`

## Author
Your Name — [GitHub](https://github.com/username)

## References
- Sources, papers, or tutorials used
```

### 6. Commit and push
```bash
git add .
git commit -m "Add project: Your Project Name"
git push origin main
```

### 7. Open a Pull Request
- Go to your fork on GitHub
- Click **Compare & pull request**
- Title: `[Project] Your Project Name`
- Fill in the PR template

---

## Review Process
1. A maintainer reviews your PR within a few days
2. They may request changes
3. Once approved → merged and live 🎉

---

## Questions?
Open an **Issue** with the label `question`.
