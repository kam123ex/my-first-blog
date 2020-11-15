python manage.py runserver
OR
python manage.py runserver 0.0.0.0:8080

…or create a new repository on the command line
echo "# my-first-blog" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/kam123ex/my-first-blog.git
git push -u origin main

…or push an existing repository from the command line
git remote add origin https://github.com/kam123ex/my-first-blog.git
git branch -M main
git push -u origin main
…or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.

(myvenv) PS C:\Users\85261\djangogirls> git add --all .

(myvenv) PS C:\Users\85261\djangogirls> git commit -m "readme commit"

(myvenv) PS C:\Users\85261\djangogirls> git push -u origin main
