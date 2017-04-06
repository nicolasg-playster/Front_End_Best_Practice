<!-- TITLE: Signup -->
<!-- SUBTITLE:  -->

# Generator
Generator is the project that handles the front-end of the project; by front-end we mean rendering the EJS templates, storing the images and generating the CSS/JS. 
It does very little server processing apart from that. The only thing it might do is calling middleman through http requests, or get the user Geolocation information from the user IP address.

## Tech / Standards Used
- **Platform:** Node.js LTS
- **Language:** ES6
- **Code Style:** [StandardJS](/dev/js#standard-js)
- **Build/Dev Framework:** [FuseBox](/dev/js#fuse-box)
- **Testing Framework:** [JEST](/dev/js#jest)
- **Documentation:** [jsDoc](/dev/js#js-doc)

# Middleman
Middleman is like the name says, the middle service between the APIs & Generator or the client. It will also do a bunch of regular checks and validations on the requests. The most used request to middleman is probably the sonar request.

## Flow Diagram
![Signup Flow](/uploads/diagrams/signup-flow.jpg "Signup Flow")

## Sonar
*todo*

## Tech / Standards Used
- **Platform:** Node.js LTS
- **Language:** ES6
- **Code Style:** [StandardJS](/dev/js#standard-js)
- **Build/Dev Framework:** [FuseBox](/dev/js#fuse-box)
- **Testing Framework:** [JEST](/dev/js#jest)
- **Documentation:** [jsDoc](/dev/js#js-doc)