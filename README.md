# Git build hooks for microcommits

Build every commit in isolated Docker container. 

# Installation

## Maven

curl -fsSL https://raw.githubusercontent.com/mgryszko/git-build-hooks/master/maven-build > .git/hooks/post-commit && chmod +x .git/hooks/post-commit

## Gradle

curl -fsSL https://raw.githubusercontent.com/mgryszko/git-build-hooks/master/gradle-build > .git/hooks/post-commit && chmod +x .git/hooks/post-commit

