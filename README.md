# landing-page

Static site landing page built with Hugo.

Use webserver(Nginx) to host `./public`. 

## Installation

1. Install `go` https://go.dev/doc/install.

2. Install extended version of `hugo` https://gohugo.io/getting-started/installing/.

## Usage

The following command will create the static site based on `config.yml` and files in subdirectories.

```bash
hugo
```

Upon updates, static sites must be newly built using the above command. It is recommended to erase the `./public` folder for a proper updated build.
