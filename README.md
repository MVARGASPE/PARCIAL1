# PARCIAL1


Marcelo@DESKTOP-JRHQF6T MINGW64 ~/Desktop/WHIS
$ git init
Initialized empty Git repository in C:/Users/Marcelo/Desktop/WHIS/.git/

Marcelo@DESKTOP-JRHQF6T MINGW64 ~/Desktop/WHIS (master)
$ git remote add origin https://github.com/MVARGASPE/PARCIAL1.git

Marcelo@DESKTOP-JRHQF6T MINGW64 ~/Desktop/WHIS (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .DS_Store
        package-lock.json
        package.json
        public/
        src/
        webpack/

nothing added to commit but untracked files present (use "git add" to track)

Marcelo@DESKTOP-JRHQF6T MINGW64 ~/Desktop/WHIS (master)
$ git add *

Marcelo@DESKTOP-JRHQF6T MINGW64 ~/Desktop/WHIS (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   package-lock.json
        new file:   package.json
        new file:   public/.gitkeep
        new file:   src/img/wish.jpg
        new file:   src/index.html
        new file:   src/scripts/index.js
        new file:   src/styles/home.scss
        new file:   src/styles/index.css
        new file:   src/styles/index.scss
        new file:   webpack/webpack.common.js
        new file:   webpack/webpack.config.dev.js
        new file:   webpack/webpack.config.prod.js

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .DS_Store


Marcelo@DESKTOP-JRHQF6T MINGW64 ~/Desktop/WHIS (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   package-lock.json
        new file:   package.json
        new file:   public/.gitkeep
        new file:   src/img/wish.jpg
        new file:   src/index.html
        new file:   src/scripts/index.js
        new file:   src/styles/home.scss
        new file:   src/styles/index.css
        new file:   src/styles/index.scss
        new file:   webpack/webpack.common.js
        new file:   webpack/webpack.config.dev.js
        new file:   webpack/webpack.config.prod.js


Marcelo@DESKTOP-JRHQF6T MINGW64 ~/Desktop/WHIS (master)
$ git commit -m "Subiendo de nuevo"
[master (root-commit) 7c49aad] Subiendo de nuevo
 12 files changed, 11671 insertions(+)
 create mode 100644 package-lock.json
 create mode 100644 package.json
 create mode 100644 public/.gitkeep
 create mode 100644 src/img/wish.jpg
 create mode 100644 src/index.html
 create mode 100644 src/scripts/index.js
 create mode 100644 src/styles/home.scss
 create mode 100644 src/styles/index.css
 create mode 100644 src/styles/index.scss
 create mode 100644 webpack/webpack.common.js
 create mode 100644 webpack/webpack.config.dev.js
 create mode 100644 webpack/webpack.config.prod.js

Marcelo@DESKTOP-JRHQF6T MINGW64 ~/Desktop/WHIS (master)
To https://github.com/MVARGASPE/PARCIAL1.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/MVARGASPE/PARCIAL1.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

Marcelo@DESKTOP-JRHQF6T MINGW64 ~/Desktop/WHIS (master)
$ git push origin master
