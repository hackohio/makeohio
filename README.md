# MakeOHI/O Website
![Deployment Status](https://github.com/hackohio/makeohio/workflows/Make-site%20S3%20Deployment/badge.svg)  
Welcome to the official website for MakeOHI/O, an annual makeathon hosted by OHI/O at the Ohio State University.

# How to contribute to the homepage
- You may want to run a local testing server if you're working with absolute paths or page builders.

**Folder Structure**:  
20**: Contains the HTML pages and asset folders for each individual event.  
assets: Contains commonly used assets (such as minified js) that may be reused across events.
index.html: The redirect page for the hack.osu.edu/make page to the most recent event page.

**Deployment**:  
The website is deployed using a simple GitHub actions workflow using AWS's S3 CLI.
- The script is setup to deploy the repo into the /make directory