# Create project folder

mkdir hero-vired-assignment-02
cd hero-vired-assignment-02

# Initialize Git repository

git init

# Create app.py

echo 'print("Hello, Git!")' > app.py

# Check status

git status

# Stage file

git add app.py

# Commit changes

git commit -m "chore(file): setting up project"

# Created remote repository on GitHub manually

hero-vired-assignment-02

# Add remote origin

git remote add origin https://github.com/Shashankd48/hero-vired-assignment-02.git

# Verify remote

git remote -v

# Push code

git push -u origin main
