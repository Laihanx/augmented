# DLSJBC Campus Navigator (Static Site)

This repository now serves a static prototype of the DLSJBC Campus Navigator experience. All content lives in plain HTML, CSS, and a small amount of vanilla JavaScript—no build tools or frameworks required.

## Project Structure

- `index.html` – marketing landing page with hero, features, and CTA.
- `map.html` – static campus directory showcasing every supported destination.
- `ar-navigation.html` – interactive mock that lets you toggle camera/GPS and preview the AR flow.
- `404.html` – simple not-found page for unmatched routes.
- `assets/` – shared images (hero photo and feature icons).

## Local Preview

Open any of the HTML files directly in a browser or launch a lightweight web server, e.g.:

```powershell
cd C:\xampp\htdocs\augmented
python -m http.server 8000
```

The AR preview page requests camera and geolocation access. For those features to work, serve the site over HTTPS or from `http://localhost`.

## Customising

- Update copy or styles inline within each HTML file.
- Add new assets to `assets/` and reference them with `assets/<filename>` paths.
- If you introduce additional pages, remember to link them from the navigation menus for consistency.
