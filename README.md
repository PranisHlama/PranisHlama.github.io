# Hugo Agency Web

**Hugo Agency Web** is a clean and professional [Hugo](https://gohugo.io/) theme for digital agencies, startups, and modern product landing pages.

# Getting Started

## Prerequisites

Before you begin, make sure you have the following installed:

* [Hugo](https://gohugo.io/getting-started/installing/)
* [Go](https://go.dev/doc/install)
* [Node.js](https://nodejs.org/)
* npm (comes with Node.js)

## Installation

1. Clone the repository using the `main` branch:

```bash
git clone --depth 1 --branch main https://github.com/PranisHlama/hugo-axon-web.git 
cd hugo-axon-web
```

2. Install the dependencies:

```bash
npm install
```

3. Start the development server:

```bash
hugo server
```

Your site will be running at `http://localhost:1313`. Any changes you make will be hot-reloaded in the browser.

## Editing Content

* All content is stored in the `content/` and `data/` directories.
* To update configuration settings, **modify only the files inside the `config/` folder**, which uses Hugo’s [configuration directory](https://gohugo.io/getting-started/configuration/#configuration-directory) structure.
* YAML files inside `data/` are used for structured sections like the hero, features, and pricing.

### Designing components for the home page
All the components for the home page are stored inside 
`themes/hugo-agency-web/layouts/_partial_blocks/home` \

If you need a new component inside homepage create a html file in that directory and then navigate to `data/home.yml` and add the content there 

### Adding extra content
For adding extra page/content you need to run this command
```
hugo new posts/post.md
```
## 
### Deployment

To deploy your site, build the static files:

```bash
hugo
```

This will generate the `public/` directory, which contains the complete static site. Upload its contents to your hosting provider or connect with a platform like [Netlify](https://www.netlify.com/) or [Vercel](https://vercel.com/).

## Built With

* [Hugo](https://gohugo.io/) – A fast and flexible static site generator.
* [Tailwind CSS](https://tailwindcss.com/) – A utility-first CSS framework for rapid UI development.
* [Agency Web by Sanoj Dilshan](https://www.figma.com/community/file/1058767686059595687) – The design inspiration behind the theme.

## License

This project is licensed under the MIT License – see the [LICENSE](https://github.com/writeonlycode/hugo-agency-web/blob/main/LICENSE) file for details.
