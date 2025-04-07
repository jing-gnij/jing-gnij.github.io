# Assessment 2

Course: Create and style simple markup language documents

## Introduction

This repo contains the code for a demo website that can be opened directly in a local browser, served using a local web server, or deployed via a cloud service.

## Navigation

This demo website consists of four pages: Home (index.html), Contact Us (contact_us.html), About (about.html), and Book One (book_one.html).

The Home, Contact Us, and About pages can be accessed by clicking the respective links in the navigation area. The "Book One" page can be accessed by clicking either the first image or the text "Harry Potter and the Philosopher's Stone" on the Home page (index.html).

## Deployment

### Local Browser

Open index.html in a browser to view the website.

### Local Web Server

The repo can be served with a local web server, such as Caddy (refer to https://caddyserver.com/ for more information). To do this, navigate to the directory of the repo in the terminal and run the following command:

```
$ caddy file-server
```

Then, open localhost in a browser to view the website.

### Cloud Service

The code can also be deployed on a cloud service. For an example, check out the demo on GitHub Pages https://jing-gnij.github.io/.