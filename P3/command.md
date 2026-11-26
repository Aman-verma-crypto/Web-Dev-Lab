# New feature branch create karo
git switch -c feature/portfolio-design

# Changes stage karo
git add .

# Feature branch par commit karo
git commit -m "P3: Add portfolio design"

# Main branch par wapas jao
git switch main

# Feature branch merge karo
git merge feature/portfolio-design

# Branches check karo
git branch