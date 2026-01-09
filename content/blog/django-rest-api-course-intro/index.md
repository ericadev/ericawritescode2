---
title: Django REST API Course Intro
date: "2025-02-07T14:30:00.000Z"
description: "A little bit about the Django REST API course I've started"
---

Recently I started a course [Build a Backend REST API with Python & Django - Advanced](https://www.udemy.com/course/django-python-advanced/) which has been pretty detailed and focuses on test-driven Django development to build a REST API. There is detailed setup with Docker using linting and Github Actions. One thing I noticed early on is I'm having trouble with the shell script I used following directly with the course, but Visual Studio Code was rather helpful.

Whilst shell scripting there is a line in the Dockerfile that instructs the machine to pip install dev requirements only if it is currently running with the DEV argument set to true. The course suggested running the following

```
if [ $DEV = "true" ];
```

but I found this worked instead:

```
if [ ${DEV} = true ];
```

VS Code gave me a hint that the variable needed curly braces around it and I could use the true boolean instead of a string containing the word true. Prior to this change, I was getting an error that it couldn't find the then statement following and there was an invalid fi line (ie. closing the if statement without doing anything within it). I'll be interested to see if there are other small changes from the course to what I have to use to get it working. We are pinning versions of packages used so hopefully this won't be a big issue. The other thing is I need to run 'docker compose' instead of 'docker-compose', but I imagine this is because I'm using a newer Docker version than the course.

There's a separate course for deployment of Python projects, I might do that later.
