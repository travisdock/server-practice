# server-practice
Practicing hosting multiple rails apps through nginx reverse proxy in docker

Create rails apps with:
```
docker run -it -v /Users/me/development:/development -w /development ruby:latest bash
gem install rails
rails new app_1 --skip-git --skip-jbuilder --skip-test --skip-system-test --database=postgresql
```
Be sure to copy .gitignore from another project into the rails project folders
