# Cookiecutter Slim Berkshelf Vagrant

At the time of writing this `README`,
[Berkshelf](https://github.com/riotgames/berkshelf) is taking their
sweet time with this issue
[Berkshelf#499](https://github.com/RiotGames/berkshelf/issues/499) and
it's driving me crazy.

Luckily for those of us that are impatient, there's [cookiecutter](https://github.com/audreyr/cookiecutter)!

## Install cookiecutter

- See [Installing Cookiecutter](http://cookiecutter.readthedocs.org/en/latest/installation.html).
- Read [Cookiecutter's features](https://github.com/audreyr/cookiecutter#features) because this uses them

## Prompts

Fork this project, modify the cookiecutter.json (on your own branch)

## Usage

```bash
cookiecutter https://github.com/mahmoudimus/cookiecutter-slim-berkshelf-vagrant.git
```

This will close `cookiecutter-slim-berkshelf-vagrant` in your `~/.cookiecutter` repository.

### Create a cookbook

```bash
cd ${DIRECTORY_YOU_WISH_TO_CREATE_THE_COOKBOOK_IN}
cookiecutter cookiecutter-slim-berkshelf-vagrant
```

Follow the prompts. Enjoy.

Remember, you can modify your `cookiecutter.json` file to not be
prompted by a bunch of stupid questions. Read the installation
instructions.

## Contribution

Contribute fixes to making streamlined cookbooks / vagrant files for the community!
