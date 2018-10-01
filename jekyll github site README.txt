bundle exec jekyll build
cd _site
git add -u
git commit -m “removed research talk pdf”
git push -u origin master



git remote add origin https://github.com/kevinmdorn/kevinmdorn.github.io

git commit -m “removed some PDF links” 
git remote add origin https://github.com/kevinmdorn/kevinmdorn.github.io.git

git push -u origin master