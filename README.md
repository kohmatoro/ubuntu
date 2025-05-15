source myenv/bin/activate

git status
git checkout master
git merge main --allow-unrelated-histories

rm -rf .git
git init

cd open
rm -rf .git
git init

git add *
git commit -m "ubuntu"

git remote add origin https://github.com/kohmatoro/ubuntu
git branch -m main
git push -f origin main

code

