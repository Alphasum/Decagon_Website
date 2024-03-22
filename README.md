# Decagon_Website

This repository contains two folders for the same website.
1. The Decagon_Tailwind folder has the website home page built with Tailwindcss only. To run the /build/index.html file,
tailwind must be configured in the host machine by running npx tailwindcss -i ./src/input.css -o ./build/css/style.css --watch on the terminal and hosting the page on a liveserver.


2. The Decagon_handlebars folder has the same website home page built with Tailwindcss and Handlebars templates. The components, layouts and pages are separated into diffrent subfolders in the partials folder and are reusable for multiple pages. To host the Decagon.html page, configure both handlebars and tailwind css on host machine.
