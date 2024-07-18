<!-- @format -->

# Hamid Raza's Portfolio

Welcome to the repository for my personal portfolio website. This portfolio showcases my professional journey, projects, skills, and experiences as a tech lead and MERN stack engineer. Visit my portfolio at [hamid-raza.com](https://hamid-raza.com).

## Table of Contents

- [Hamid Raza's Portfolio](#hamid-razas-portfolio)
  - [Table of Contents](#table-of-contents)
  - [About](#about)
  - [Features](#features)
  - [Technologies Used](#technologies-used)
  - [Installation](#installation)
  - [To preview/edit locally with docker](#to-previewedit-locally-with-docker)
    - [Local machine](#local-machine)

## About

I'm Hamid Raza, a tech lead with over 8 years of experience in the MERN stack. My portfolio provides an overview of my work, including the various projects I have contributed to and led. It also highlights my technical skills, professional experience, and educational background.

## Features

- **Professional Overview**: Detailed information about my career and accomplishments.
- **Projects**: Showcases of my significant projects with descriptions and technologies used.
- **Skills**: A comprehensive list of my technical skills and proficiencies.
- **Contact Information**: Easy access to my contact details for potential opportunities and collaborations.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript, React
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Deployment**: GitHub Pages, Netlify
- **Other Tools**: Webpack, Babel, ESLint

## Installation

- [Fork](https://github.com/sharu725/online-cv/fork) the repository
- Go to settings and set master branch as Github Pages source.
- Your new site should be ready at `https://<username>.github.io/online-cv/`
- Printable version of the site can be found at `https://<username>.github.io/online-cv/print`. Use a third party link https://pdflayer.com/, https://www.web2pdfconvert.com/ etc to get the printable PDF.

Change all the details from one place: `_data/data.yml`

## To preview/edit locally with docker

```sh
docker-compose up
```

_docker-compose.yml_ file is used to create a container that is reachable under http://localhost:4000.
Changes _\_data/data.yml_ will be visible after a while.

### Local machine

- Get the repo into your machine

```bash
git clone https://github.com/sharu725/online-cv.git
```

- Install required ruby gems

```bash
bundle install
```

- Serve the site locally

```bash
bundle exec jekyll serve
```

- Navigate to `http://localhost:4000`
