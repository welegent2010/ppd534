# Modules

This course is composed of weekly learning modules. Many of these modules include a Jupyter notebook lecture.

## How to launch a Jupyter notebook lecture

You have two options. The first (Docker) is preferred. If you have trouble with the first option, you can fallback on the second option, which is easier but has significant limitations.

### Option 1: Docker

First, make sure you've completed the initial [software setup](../software/readme.md) instructions. Then, when you come into class each day, before the lecture begins, do the following steps (takes <1 minute):

  - Open a terminal window, change directories to the `ppd534` folder on your desktop
  - Run `git pull` to bring your local version of the course files up to date with the server
  - Launch JupyterLab via Docker:
     - On *Windows*, run `docker run --rm -it -p 8888:8888 -v "%cd%":/home/jovyan/work gboeing/ppd534:latest`
     - On *Mac*, run `docker run --rm -it -p 8888:8888 -v "$PWD":/home/jovyan/work gboeing/ppd534:latest`
  - In your web browser, visit http://localhost:8888

Important! When you're all done using Jupyter at the end of the class session: to stop the running container, go to your terminal window where docker is running and hit `ctrl + c` then wait until everything shuts down and your terminal's cursor reappears. Do not just close your terminal window without stopping Docker first! If you do, you'll have to restart your computer before you can run docker again.

### Option 2: Binder

This option has 3 significant limitations. First, all the notebooks are read-only, meaning that you cannot save any changes you make, notes you take, or new files you create. Second, they time-out after approximately 10 minutes of inactivity. Third, you are limited to approximately 1 GB of memory on the server.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/gboeing/ppd534/master?urlpath=lab)