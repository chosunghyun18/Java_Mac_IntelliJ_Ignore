### Java Mac IntelliJ ####

HELP.md
.gradle
build/
!gradle/wrapper/gradle-wrapper.jar
!**/src/main/**
!**/src/test/**

### STS ###
.apt_generated
.classpath
.factorypath
.project
.settings
.springBeans
.sts4-cache

### IntelliJ IDEA ###
.idea
*.iws
*.iml
*.ipr
out/

### NetBeans ###
/nbproject/private/
/nbbuild/
/dist/
/nbdist/
/.nb-gradle/

### VS Code ###
.vscode/

# Compiled class file
*.class
*.log

### MAC OS ###
*.DS_Store
~/*.DS_Store



########## CMD
git rm -r --cached .
git add .
git commit -m "chore : apply .gitignore"
