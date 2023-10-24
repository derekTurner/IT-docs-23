## React to github page

This  object here is to add a couple of markdown files to a React app, navigate between views of the two files and deploy as a github page.

The markdown files will be the svelte presentation and markdown descriptions, but the pages are being displayed in a react app.

### Setup

This app will use the [react router version 6](https://reactrouter.com/en/main) to navigate between views of different components so to setup return the the ReactTS23 folder and add the router so that it will be available for all react pages on the platform.

> npm install react-router-dom

Now add markdown handling, just for this particular project.

> cd react23
 
> npm install react-markdown --save

> 