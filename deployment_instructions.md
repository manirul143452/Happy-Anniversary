# Deployment Instructions for Anniversary Website

## Option 1: Deploy to Netlify (Recommended)

1. Create a free account on [Netlify](https://www.netlify.com/) if you don't have one already.
2. Once logged in, go to the Netlify dashboard.
3. Drag and drop the `anniversary_website.zip` file directly onto the Netlify dashboard where it says "Drag and drop your site folder here".
4. Netlify will automatically unzip and deploy your website.
5. Once deployed, Netlify will provide you with a URL (e.g., https://random-name.netlify.app).
6. You can customize this URL by going to Site settings > Domain management > Custom domains.

## Option 2: Deploy to GitHub Pages

1. Create a GitHub account if you don't have one already.
2. Create a new repository (e.g., "anniversary-website").
3. Unzip the `anniversary_website.zip` file on your computer.
4. Upload all the files to your GitHub repository.
5. Go to repository Settings > Pages.
6. Under "Source", select "main" branch and click Save.
7. Your website will be published at https://yourusername.github.io/anniversary-website/.

## Option 3: Use a Web Hosting Service

1. Sign up for a web hosting service (e.g., Bluehost, HostGator, etc.).
2. Access your hosting control panel (usually cPanel).
3. Use the File Manager to upload the contents of the `anniversary_website.zip` file.
4. Make sure to upload the files to the public_html directory or the appropriate web root folder.
5. Your website will be accessible at your domain name.

## Local Testing

To test the website locally before deploying:

1. Unzip the `anniversary_website.zip` file on your computer.
2. Open the `index.html` file in a web browser.
3. Note that some features like the Future Memories system work best when accessed via a web server rather than directly opening the HTML file.

## Important Notes

- The website is designed to be responsive and work on both desktop and mobile devices.
- All images are stored in the `images` folder and are referenced relatively in the HTML.
- The website uses CDN-loaded libraries (React, GSAP, Particles.js) so an internet connection is required for proper functioning.
- The Future Memories system uses local storage to save memories, which means they are stored in the browser and will persist between sessions on the same device.

## Customization

If you want to make changes to the website:

1. Edit the `index.html` file using a text editor.
2. The website is structured as React components, each handling a different section.
3. CSS styles are included in the `<style>` section in the head of the document.
4. To change images, replace files in the `images` folder and update references in the `photo_metadata.json` file.

Enjoy your anniversary website! 💖
