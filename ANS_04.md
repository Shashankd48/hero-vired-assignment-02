# Make changes without committing

echo 'print("Temporary change")' >> app.py

# Stash including untracked files

git stash -u

# Check stash list

git stash list

# Apply stash

git stash apply

# Commit changes

git add .
git commit -m "temp(app): applied stashed changes"

# Add incorrect code

echo 'print("Wrong code")' >> app.py

# Commit incorrect code

git add .
git commit -m "Added incorrect code"

# Undo last commit using reset

git reset --soft f0226673d10934dcde6dfac6168c68fc1d512eaf

# OR completely remove commit and changes

git reset --hard f0226673d10934dcde6dfac6168c68fc1d512eaf

echo 'print("Correct code")' >> app.py
git add .
git commit -m "feat(app): added correct code"

# Revert commit

git revert HEAD

# Verify history

git log --oneline
