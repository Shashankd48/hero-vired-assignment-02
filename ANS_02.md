# Modify app.py

echo 'print("New Feature Added")' >> app.py

# Check changes

git status

# View differences

git diff

# Stage specific changes

git add -p

# Commit changes

git commit -m "feat(app): new feature added"

# Make another change

echo 'print("Another Update")' >> app.py

# Stage all changes

git add .

# Commit again

git commit -m "feat(app): another print line added"

# View full commit history

git log

# View one-line compact history

git log --oneline
