# europe 💶

[![deploy](https://github.com/GrantBirki/europe/actions/workflows/deploy.yml/badge.svg)](https://github.com/GrantBirki/europe/actions/workflows/deploy.yml)

Europe 2017 - Journal, Stories, and Memories

The live site can be found at [europe.birki.io](https://europe.birki.io)

## Development 💻

First, ensure you have the `hugo` binary installed. Then, run the following commands:

```bash
hugo server -D
```

This will start a local development server with live reloads

### WSL Note 📓

If you are using WSL, you will need to run the following commands to ensure the server is accessible from your browser:

```bash
ifconfig # find the IP address of your WSL instance

hugo server --bind <ip> --baseURL=http://<ip> -D
```

## New Blog Post 📝

To create a new blog post, run the following command:

```bash
hugo new posts/my-first-post.md
```

## Theme 🎨

This site uses the [hugo-PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme

For more details on configuration, see the [features](https://github.com/adityatelange/hugo-PaperMod/wiki/Features) page on the theme's wiki

## Chronological Order 📅

Please note that the posts here are modified to be in chronological order. If you want to use this repo and reverse these changes to have blog posts in reverse chronological order, revert the following commits:

- [`beadd271`](https://github.com/GrantBirki/europe/commit/beadd2711e3882aa5fc6165b1b7cbabbafc2d99f)
- [`df257f53`](https://github.com/GrantBirki/europe/commit/df257f53da8cea818258877040d6b0e574efad3f)
- [`59c3c49e`](https://github.com/GrantBirki/europe/commit/59c3c49e2da2c40fe3d798e56b9943e02e738745)
