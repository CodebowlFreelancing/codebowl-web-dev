# Codebowl web site development tools

Build and development tools for codebowl-web

## Usage

Clone website to publish into dist directory and copy its contents into src directory. Dev
in src directory and use following scripts to update dist and thus the website to publish.

| Script        | Description                                                               |
| ------------- | ------------------------------------------------------------------------- |
| build         | Build new publishable codebowl-web to dist directory from src directory   |
| build:postcss | Builds compstyle.css that is browserslists supported version of style.css |
| start         | Runs start:postcss                                                        |
| start:postcss | Runs build:postcss in watch mode                                          |
