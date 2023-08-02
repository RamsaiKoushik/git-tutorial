```
 1747  mkdir imt2021072
 1748  cd imt2021072/
 1749  git init
 1750  ls -l
 1751  ls -a
 1752  git status
 1753  touch readme.md
 1754  git add readme.md
 1755  git status
 1756  git log
 1757  git config --global user.name "RamsaiKoushik" 
 1758  git config --global user.email ram.polisetti@iiitb.ac.in
 1759  git config --list
 1760  git status
 1761  git commit -m "initial commit"
 1762  git status
 1763  git log
 1764  git remote add origin https://github.com/RamsaiKoushik/git-tutorial.git
 1765  git branch -M main
 1766  git branch
 1767  git push -u origin main
 1768  git checkout -b new-feature
 1769  git branch
 1770  touch new.txt
 1771  echo "hi" >new.txt
 1772  cat new.txt
 1773  git commit -m "new feature"
 1774  git add new.txt
 1775  git commit -m "new feature"
 1776  git status
 1777  git push -u origin new-feature
 1778  git checkout main
 1779  git branch
 1780  git status
 1781  git pull
 1782  history 
```
