# Picture This: Automated Visual Regression Testing

For years people thrown around the idea of visual regression testing, however, it typically has been limited to only a single browser and for static web pages. Imagine a world where when you make a code change you are able to detect unexpected distortions in your web application across all supported environments with minimal effort! In this talk I will discuss how I built a framework to do Visual Regression Testing using Capybara, Compatriot and BrowserStack. I’ll discuss what I learned and how you can get started doing it today.

#### [View Slides](http://TheJefe.github.io/picture_this)

## Presentation Frameworks is [Reveal.js](https://github.com/hakimel/reveal.js)

### SETUP

Some reveal.js features, like external Markdown and speaker notes, require that presentations run from a local web server. The following instructions will set up such a server as well as all of the development tasks needed to make edits to the reveal.js source code.

1. Install [Node.js](http://nodejs.org/)

1. Clone the repository
   ```sh
   $ git clone https://github.com/TheJefe/picture_this.git
   ```

1. Navigate to the picture_this folder
   ```sh
   $ cd picture_this
   ```

1. Install dependencies
   ```sh
   $ npm install
   ```

1. Serve the presentation and monitor source files for changes
   ```sh
   $ npm start
   ```

1. Open <http://localhost:8000> to view your presentation

   You can change the port by using `npm start -- --port 8001`.
