This is a blog using the static site generator Jekyll.

## Prerequisites
Make sure you have the following installed on your system:

- Docker https://www.docker.com/ (Latest "Stable")
- Node.js / NPM https://nodejs.org/en/

## Workflow
`npm start` to start your jekyll container (the first time you run this, you will download the jekyll image from Docker Hub). Visit http://localhost:4000/blog/ to see your site.

`npm stop` when you are done for the day and want to stop and delete the container.

`npm run kill` if you want to delete the image and container from your system. No files are deleted from your system by doing this. Just run `npm start` again.
