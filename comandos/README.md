python -m venv venv
. venv/bin/activate
pip install django
pip freeze
django-admin startproject project .
python manage.py startapp contact

git config --global user.name 'Seu nome'
git config --global user.email 'seu_email@gmail.com'
git config --global init.defaultBranch main

# Configure o .gitignore
git init
git add .
git commit -m 'Mensagem'
git log --oneline
git remote add origin URL_DO_GIT ou git remote set-url origin URL_DO_GIT
git push origin main -u