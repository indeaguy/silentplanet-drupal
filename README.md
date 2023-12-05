# This will be the README

WIP/NOTES TO SELF:

ddev drush site:install -y
ddev launch

https://bookish-engine-r7gwg4wwv92w5vv.github.dev/
https://bookish-engine-r7gwg4wwv92w5vv-8080.app.github.dev/user/login


Needed to add this to repo for code spaces

https://ddev.readthedocs.io/en/latest/users/install/ddev-installation/

add this to the repo in .devcontainer/devcontainer.json:

{
  "image": "mcr.microsoft.com/devcontainers/universal:2",
  "features": {
    "ghcr.io/ddev/ddev/install-ddev:latest": {}
  },
}


Then:

https://www.drupal.org/docs/official_docs/local-development-guide

At onepoint needed to REMOVE .devcontainer/devcontainer.json and then RE-ADD it after completing setup

ISSUE WITH CONFIG/ROUTES AFTER LOGGING IN FORWARDING TO :8080