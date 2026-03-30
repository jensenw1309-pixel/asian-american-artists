# Sonic Chinatown Podcast Website

A modern, responsive static landing page for an NYC-centered Asian-American music podcast.

## Local Development

Run a local server:

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Deploy (Static Hosting)

This project is static and ready for deployment on:

- **GitHub Pages** (root publish)
- **Netlify** (no build command, publish `.`)
- **Vercel** (Other framework, output `.`)

## Form Handling

The contact form is configured with Netlify form attributes:

- `data-netlify="true"`
- `netlify-honeypot="bot-field"`
- hidden `form-name` field

On Netlify, submissions will be captured automatically after deployment.
For Vercel/GitHub Pages, replace the form configuration with your preferred endpoint provider.

## Customization Checklist

- Replace placeholder platform links and social handles in `index.html`.
- Update the podcast email and event details.
- Tune colors, typography, and spacing in `styles.css`.
