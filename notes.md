    1  git clone https://github.com/mattpe/git-intro.git
    2  cd git-intro
    3  git remote -v
    4  git remote set-url origin https://github.com/oliverhazley/git-intro-oliverhazley
    5  git remote remove origin
    6  git remote add origin https://github.com/oliverhazley/git-intro-oliverhazley
    7  git push -u origin main
    9  history | grep git
    10 git add notes.md
    11 git commit -m "Update notes.md with more Git commands"
    12 git push
