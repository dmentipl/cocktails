# Recipes

Recipes written in markdown and generated with Hugo.

## Requirements

Get hugo. If you're using nix, try the following.

```bash
nix-shell -p hugo --run fish
```

## Usage

Start the server, make changes, then view the build.

```bash
hugo server &
```

View the build at <http://localhost:1313/>.

## Deploy

A GitHub Actions workflow is used to deploy website. Any changes pushed to the main branch will automatically rebuild the website. See [deploy.yml](.github/workflows/deploy.yml) for details.

## Credit

This website is built using Jan Raasch's [Hugo ʕ•ᴥ•ʔ Bear Blog](https://github.com/janraasch/hugo-bearblog/) theme which in turn is derived from Herman Martinus's [Bear Blog](https://github.com/HermanMartinus/bearblog/) application.
