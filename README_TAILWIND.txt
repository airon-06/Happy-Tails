# Tailwind CSS Production Setup

1. Install Tailwind CSS and its dependencies:
   npm install -D tailwindcss postcss autoprefixer

2. Build your CSS:
   npx tailwindcss -i ./input.css -o ./output.css --minify

3. Link output.css in your HTML:
   <link rel="stylesheet" href="output.css">

4. Remove the CDN <script> from your HTML head.

See https://tailwindcss.com/docs/installation for details.
