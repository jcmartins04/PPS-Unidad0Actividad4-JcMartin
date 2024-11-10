  154  echo "# PPS-Unidad0Actividad4-JcMArtin" >> README.md
  155  git init
  156  git add README.md
  157  git commit -m "first commit Activity 4"
  158  git branch -M main
  159  git remote add origing git@github.com:jcmartins04/PPS-Unidad0Actividad4-JcMartin.git
  160  git push -u origin main
  161  git remote add origin git@github.com:jcmartins04/PPS-Unidad0Actividad4-JcMartin.git
  162  tree -a
  165  git status
  166  git diff
  167  clear
  168  git push
  170  nano README.md
  172  clear
  173  tree -a
  174  git status -s
  177  git reset --hard origin/PPSUnidad0Actividad3_JcMartin.git
  178  clear
  180  git fetch
  181  cd PPSUnidad0Actividad3_JcMartin
  183  git fetch
  184  git log origin
  185  git reset --hard origin/PPSUnidad0Actividad3_JcMartin
  186  git status -s
  190  git status -s
  191  git fetch
  192  git reset --hard origin/PPSUnidad0Actividad3_JcMartin 
  196  nano README.md
  202  mkdir PPS-Unidad0Actividad4-JcMartin\n
  205  mv README.md PPS-Unidad0Actividad4-JcMartin
  207  cd PPS-Unidad0Actividad4-JcMartin/
  209  nano README.md
  211  git add .
  213  git reset origin
  215  git init
  216  git add .
  217  git commit -m "Primer commit"\n
  218  git@gihub.com:jcmartins04/PPS-Unidad0Actividad4-JcMartin.git
  219  git status -s
  220  git push
  221  git remote add origin git@github.com:jcmartins04/PPS-Unidad0Actividad4-JcMartin.git\ngit branch -M main\ngit push -u origin main
  222  git status -s
  223  ls
  224  mkdir imagenes
  226  git status -s
  227  git add .
  228  git commit -m "images directory created"
  229  git branch -M main
  230  git push -u origin main
  233  tree -a
  234  clear
  235  tree
  236  mkdir excluded
  238  tree
  239  cd excluded
  241  nano excluidos.txt
  245  tree
  246  touch .gitignore
  247  tree
  251  nano .gitignore
  252  git rm --cached *.txt
  253  git rm --cached -r excluded
  254  git add .gitignore\ngit commit -m "Actualizing .gitignore to ignore files .txt and directory excluded"\n
  255  nano .gitignore
  262  touch index.html
  266  nano index.html
  268  git status -s
  269  git add . 
  270  commit -am "adding a simply HTML page"
  271  commit -m "adding a simply HTML page"
  272  git commit -am "adding a simply HTML page"
  273  git status -s
  275  git push -u origin main
  276  nano index.html
  277  git add index.html
  278  git commit -am "adding a content into HTML page"
  279  git push -u origin main
  283  nano index.html
  285  git status -s
  286  git diff
  288  git restore index.html
  290  nano index.html.save
  291  mv index.html /home/sparky/Documents/index.html.save
  292  mv index.html.save index.html
  294  git status -s
  295  git add .
  296  git commit -am "modify content into HTML page"
  297  git push -u origin main
  300  git pull
  301  git checkout -b Vers1
  302  git branch
  309  mv -i index.html.save /home/sparky/Documents/git/PPS-Unidad0Actividad4-JcMartin/
  312  git branch
  313  mv index.html.save index.html
  314  git push origin Vers1
  323  git add .
  324  git commit -am "adding images to my practice"
  326  git push origin Vers1
  327  git status -s
  328  git branch
  329  git checkout main
  333  git checkout Vers1
