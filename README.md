# Sanity Blogging Content Studio

Congratulations, you have now installed the Sanity Content Studio, an open source real-time content editing environment connected to the Sanity backend.

Now you can do the following things:

- [Read “getting started” in the docs](https://www.sanity.io/docs/introduction/getting-started?utm_source=readme)
- Check out the example frontend: [React/Next.js](https://github.com/sanity-io/tutorial-sanity-blog-react-next)
- [Read the blog post about this template](https://www.sanity.io/blog/build-your-own-blog-with-sanity-and-next-js?utm_source=readme)
- [Join the community Slack](https://slack.sanity.io/?utm_source=readme)
- [Extend and build plugins](https://www.sanity.io/docs/content-studio/extending?utm_source=readme)

sanity start - to run Sanity Studio

Other helpful commands
sanity docs - to open the documentation in a browser
sanity manage - to open the project settings in a browser
sanity help - to explore the CLI manual

add vercel.json
in package.json add
"scripts": {
"start": "sanity start",
"test": "sanity check",
"build": "sanity build public -y"
},
install : npm i -D @sanity/cli

npm install -g @sanity/cli && sanity init --template get-started --project 45nqog8k --dataset production --provider github
