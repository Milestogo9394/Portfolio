# Long Way Round Portfolio

Static website: `index.html` holds the page, the game and all your content; `img/` holds the backgrounds and the rider; `uploads/` receives images you add from the editor.

- **Visit:** open the site address.
- **Edit:** open `your-site-address/#edit`, then press **Publish**. The first time, open the **Publishing** tab and connect your GitHub repository with a fine-grained access token (Contents: Read and write, this repository only).
- **Hosting:** GitHub stores the files; Netlify serves them and redeploys about a minute after each Publish. `netlify.toml` tells Netlify there is no build step.

Do not commit your access token anywhere; it lives only in the browser you connected.
