# Digital Resume Static Website

This project is used for my personal website, it's a simple static website hosted in [GitHub Pages](https://pages.github.com/).

### Features
- Button to **download resume**
- Button to contact me via **email**
- Small icons for **key skills**
- Progress bar for **coding skills**
- Swiper to show **certificates**
- Small preview of **portfolio**, with links to the corresponding github repo
- Footer with links to my **github** and **linkedin**

### Deploy
This application is deployed in GitHub pages [here](https://calvinhus.github.io/resume/).

However, in order to develop it without having to push the changes to the repo every time, I created a docker-compose file to deploy locally in a simple web server (based on the **nginx:alpine** image).

To deploy make sure you have docker installed and just run the command:
```console
$ docker-compose up -d 
```
This should start the server in detached mode, locally at port 80 (*localhost:80*) allowing you to make changes to the code and see them in real time.

### TBD
- Add custom domain

> **Note:** This project is based on a free template by [Did Coding](https://github.com/bobby-didcoding/didcoding_resume_template)
