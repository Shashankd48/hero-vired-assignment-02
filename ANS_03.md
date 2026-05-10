# Create branch

git branch feature-update

# Switch to branch

git checkout feature-update

# OR

git switch feature-update

# Modify app.py

echo 'print("Feature branch code")' >> app.py

# Stage and commit

git add app.py
git commit -m "Added feature update"

# Switch back to main

git checkout main

# Merge branch

git merge feature-update

# Verify merged changes

cat app.py

# Delete branch safely

git branch -d feature-update

# Create dummy branch

git branch dummy-branch

# Force delete branch

git branch -D dummy-branch
