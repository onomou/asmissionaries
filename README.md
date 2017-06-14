# About

Personal website for communicating with our peeps.

## Structure

```
|--site                // Everything in here will be built with hugo
|  |--content          // Pages and collections - ask if you need extra pages
|  |--data             // YAML data files with any data for use in examples
|  |--layouts          // This is where all templates go
|  |  |--partials      // This is where includes live
|  |  |--index.html    // The index page
|  |--static           // Files in here ends up in the public folder
|--src                 // Files that will pass through the asset pipeline
|  |--css              // CSS files in the root of this folder will end up in /css/...
|  |--js               // app.js will be compiled to /js/app.js with babel
```

#### Credits
Built with [Hugo](http://gohugo.io/) on the [Victor-Hugo](https://github.com/netlify/victor-hugo) boilerplate, released under the [MIT License](https://github.com/netlify/victor-hugo/blob/master/LICENSE).
Deployed using [Netlify](https://www.netlify.com).
