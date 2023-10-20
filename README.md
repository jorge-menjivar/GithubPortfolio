# 📓 GitHub Portfolio

GitHub Portfolio lets you create your own portfolio + blogging website
in 1 minute. GitHub Portfolio uses your GitHub repos to create a
personalized website for you.

## How does it work?

GitHub Portfolio uses the following to generate your portfolio website:

- Your GitHub profile `README.md`

- A repo with a folder named `posts` in the main directory, which will
  be used to store your blog posts

- It uses Vercel to deploy a client app that will fetch the information
  from your GitHub account.

So everything on your portfolio comes directly from your GitHub account
activity. The more you use GitHub, the richer your portfolio becomes!

## Why use it?

GitHub Portfolio provides a simple way to create a portfolio that
showcases your work on GitHub. Here are some of the benefits:

- Easy setup - It takes less than 60 seconds to create your portfolio

- Always in sync - Your portfolio updates automatically as your GitHub
  profile updates. No need to rebuild every time

- Hackable - It's completely open source and can be easily customized or
  extended

- Free hosting - Your site gets deployed on Vercel and you get a free
  domain. No server maintenance needed!

- Write blog posts - Write blog posts in an instant, by making a new
  markdown file inside a repo

- Automatic SEO - Your site is optimized for search engines

- Social links - Add links to your social profiles

- Automatic Site Map - Your site map is automatically generated and
  updated

- RSS Feed Support - Your RSS files are automatically generated and
  updated

In short, GitHub Portfolio lets you focus on your projects while it
handles the portfolio generation and hosting. The perfect solution for
developers and makers!

## Getting Started

1.  Click this button to deploy to Vercel.

2.  Create a new GitHub token. The token only needs access to your
    public repositories. You can create one
    here: [https://github.com/settings/tokens](https://github.com/settings/tokens)

3.  Configure the environment variables inside Vercel. Below is a list
    of all supported variables. You can also use the
    [`.env.example`](./.env.example) file as a reference.

## Environment Variables

### Required

| Environment Variable          | Description                                |
| ----------------------------- | ------------------------------------------ |
| GITHUB_TOKEN                  | The GitHub token to use for fetching repos |
| NEXT_PUBLIC_GITHUB_USERNAME   | Your GitHub username                       |
| NEXT_PUBLIC_GITHUB_POSTS_REPO | The name of the repo to use for blog posts |

### Site configuration

| Environment Variable         | Description                                 |
| ---------------------------- | ------------------------------------------- |
| GITHUB_EXCLUDE_LIST          | A comma-separated list of repos to exclude  |
| NEXT_PUBLIC_SITE_TITLE       | The title of your site (Tab title)          |
| NEXT_PUBLIC_SITE_DESCRIPTION | The description of your site                |
| NEXT_PUBLIC_FOOTER           | The footer to use at the bottom of the site |

### Social links

| Environment Variable         | Description               |
| ---------------------------- | ------------------------- |
| NEXT_PUBLIC_EMAIL            | Your email address        |
| NEXT_PUBLIC_GITHUB_PROFILE   | Your GitHub profile URL   |
| NEXT_PUBLIC_LINKEDIN_PROFILE | Your LinkedIn profile URL |
| NEXT_PUBLIC_THREADS_PROFILE  | Your Threads profile URL  |
| NEXT_PUBLIC_X_PROFILE        | Your X profile URL        |
