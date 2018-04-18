# VuePress Demo

A simple VuePress demo site to demonstrate continuous deployment to github pages.

For Travis CI see [.travis.yml](.travis.yml) and for AppVeyor see [appveyor.yml](appveyor.yml).

For AppVeyor, you'll also need to install `push-dir` node module, and add a `deploy` script line to your [package.json](package.json).

See docs on [NuxtJs Build Server Deployment](https://nuxtjs.org/faq/github-pages#build-server-deployment) for detailed screenshots and step by step instructions, the only difference is the change of the dist folder path from `dist` to `.vuepress/dist`. Everything else should be the same.