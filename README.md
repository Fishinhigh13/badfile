# echo "# badfile" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Fishinhigh13/badfile.git
git push -u origin main
