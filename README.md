# creativecommons-logos
A collection of all logos of the various CC projects in SVG format.

## Usage
This project exposes a function `logo` which takes in the slug of the CC project you want to render the logo for. 

The various slugs are: 
- Creative Commons: `cc`
- CC Search: `search`
- CC Vocbulary: `vocabulary`
- CC Global Summit: `global-summit`
- CC Global Network: `global-network`
- CC State of the Commons: `state-of-the-commons`
- CC Certificate: `certificate`
- CC Chooser: `chooser`
- CC Legal Database: `legal-database`
- CC Open Source: `open-source`


Example: To display the logo for CC Vocabulary

```html

<!-- Div element to render the image -->
<div id="vocab-image"></div>

<!-- get the specific logo from the Logo() function -->
<script>
    const vocabularyLogo = logo(vocabulary)
    document.getElementById("vocab-image").innerHTML = vocabularyLogo;
</script>
```

## Testing Locally
- Run `npm run build`
- Serve the file `example.html`
