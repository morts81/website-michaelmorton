# Legacy Squarespace redirects for GitHub Pages

Add these folders beside your site's main index.html in the GitHub Pages publishing folder:

- about/index.html redirects to https://www.michaelmorton.com.au/#about
- services/index.html redirects to https://www.michaelmorton.com.au/#approach
- contact/index.html redirects to https://www.michaelmorton.com.au/#contact

These are immediate HTML meta-refresh redirects. They are NOT HTTP 301 redirects, because GitHub Pages does not offer custom server-side path redirects. Google generally interprets immediate meta-refresh as a permanent redirect.

Keep your existing main index.html and all other site files unchanged.
