+++
title = 'Building A Personal Website with GitHub Pages, Domain, and Hugo'
date = 2024-07-31
draft = false
type = 'blog'
+++

Building a personal website can be a rewarding project, providing a platform to showcase your work, 
share your thoughts, and create an online presence. In this blog post, 
I'll walk you through my journey of building a personal website using GitHub Pages, 
purchasing a domain from Alibaba, and utilizing the Hugo framework.

#### Step 1: Setting Up GitHub Pages

GitHub Pages is a fantastic service for hosting websites directly from a GitHub repository. Here’s how I set up my site:

1. **Create a GitHub Repository**: I started by creating a new repository on GitHub named `personalWebsite`.
2. **Initialize with README**: I initialized the repository with a README file to give a brief description of the project.
3. **Enable GitHub Pages**: In the repository settings, I navigated to the 'Pages' section and selected the main branch as the source. GitHub then provided a URL where the website would be hosted.
#### Step 2: Purchasing a Domain from Alibaba

To give my website a professional touch, I decided to purchase a custom domain. Alibaba Cloud offers reliable domain registration services:

1. **Select a Domain**: On Alibaba Cloud's domain registration page, I searched for and selected an available domain name, `walkerwang.com`.
2. **Complete Registration**: I completed the registration process, providing necessary details and making the payment.
3. **Configure DNS Settings**: In the Alibaba Cloud console, I updated the DNS settings to point to GitHub Pages. I added a `CNAME` record pointing to my GitHub Pages URL.

#### Step 3: Using Hugo for Static Site Generation

Hugo is a fast and flexible static site generator written in Go. It’s perfect for creating static websites with ease. Here’s how I used Hugo:

1. **Install Hugo**: I installed Hugo on my local machine by following the instructions on the [Hugo website](https://gohugo.io/getting-started/installing/).
2. **Create a New Site**: Using the command `hugo new site my-site`, I created a new Hugo site.
3. **Select a Theme**: I chose a theme from the [Hugo themes repository](https://themes.gohugo.io/) and installed it by cloning the theme’s repository into the `themes` directory of my site.
4. **Add Content**: I started adding content by creating new markdown files in the `content` directory. Hugo uses markdown, making it easy to format text and create pages.
5. **Customize Configuration**: I customized the `hugo.toml` file to set site parameters, theme configuration, and other settings.
6. **Build the Site**: Using the command `hugo`, I generated the static files for my site. These files were placed in the `public` directory.

#### Step 4: Deploying the Site

With everything set up locally, the final step was to deploy the site to GitHub Pages:

1. **Push to GitHub**: I committed all my Hugo site files to my GitHub repository.
2. **Deploy**: I pushed the changes to the main branch, deploy according to  [Host on Github Pages](https://gohugo.io/hosting-and-deployment/hosting-on-github/).

By following these steps, I successfully built and deployed my personal website using GitHub Pages, a custom domain from Alibaba, and the Hugo framework. This setup not only provides a professional look but also offers a seamless workflow for updating and managing the site. If you're considering building your own website, I highly recommend this approach.