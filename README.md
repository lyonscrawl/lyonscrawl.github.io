# A clean personal portfolio

Live : [lyonscrawl.github.io](https://lyonscrawl.github.io)

![lyonscrawl.github.io](/portfolio.png)

# 🚨 Forking this repo (please read!)

Many people have contacted me asking me if they can use this code for their own website, and the answer to that question is usually yes, with attribution.

I value keeping my site open source, but as you all know, plagiarism is bad. It's always disheartening whenever I find that someone has copied my website without giving me credit. I spent a non-trivial amount of effort building and designing this iteration of my website, and I am proud of it! All I ask of you all is to not claim this effort as your own.

# Sections

- About
- Background
- Experience
- Resume

# How To Use

- Clone this repository (or fork, then clone your fork :) )
- Run `npm i`
- Check it out using `npm start`

# How Do I Customize

- Replace `homepage` in package.json to your domain name or `https://<username>.github.io`
- In `src/portfolio.js` you can add your personal portfolio details.
- In `src/theme.js` you can change the theme colors. You can change between Light and Dark theme with the theme switch on the header.

# How to Deploy

- Once you are done with your setup and have successfully completed all steps above, you need to put your website online!
- I highly recommend using [Github Pages](https://create-react-app.dev/docs/deployment/#github-pages) to achieve this the EASIEST WAY.
- To deploy your website, you have two options. First you need to create a github repository with the name `<your-github-username>.github.io`. Please don't give it any other name.
- Now, you need to generate a production build and deploy the website.

**Option 1:**

- Run `npm run build` to generate the production build folder.
- Enter the build folder, `git init` and push the generated code to the `master` branch of your new repository. That's it. Done.
  You may need to `git init` and force push at every new build.

**Option 2 (will not work with [user pages](https://docs.github.com/en/github/working-with-github-pages/about-github-pages)):**

- Run `npm run deploy` to build and create a branch called `gh-pages`. It will push the `build` files to that branch.
- The last step in deploying is to enable `Github Pages` in settings of the repository and select `gh-pages` branch.

Now, your website is successfully deployed and you can visit it at `<your-github-username>.github.io`.  


# Technologies used 🛠️

- [React](https://reactjs.org/)
- [baseui](https://github.com/uber/baseweb)
- [react-reveal](https://www.react-reveal.com/)
- [styled-components](https://styled-components.com/)
- [graphql](https://graphql.org/)
- [apollo-boost](https://www.apollographql.com/docs/react/get-started/)

# References

Based on https://github.com/ashutosh1919/masterPortfolio/ and https://github.com/bchiang7/v4
