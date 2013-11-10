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

Fork this project, modify the `cookiecutter.json` (on your own branch)

## Usage

```bash
cookiecutter https://github.com/mahmoudimus/cookiecutter-slim-berkshelf-vagrant.git
```

This will clone `cookiecutter-slim-berkshelf-vagrant` in your `~/.cookiecutter` repository.

If you want to clone the repository again (to create a new cookbook), do:

```bash
cookiecutter ~/.cookiecutters/cookiecutter-slim-berkshelf-vagrant
```

### Aliasing berks

Put this in your `.bashrc` or `.zshrc`

```bash
alias sane-berks-cookbook='cookiecutter ~/.cookiecutters/cookiecutter-slim-berkshelf-vagrant'
```

Then from your prompt:

```bash
sane-berks-cookbook
```

and follow the prompts.

### Create a cookbook

```bash
cd ${DIRECTORY_YOU_WISH_TO_CREATE_THE_COOKBOOK_IN}
cookiecutter ~/.cookbooks/cookiecutter-slim-berkshelf-vagrant
```

**OR if you've aliased berks**

```bash
sane-berks-cookbook
```

Follow the prompts.

```bash
vagrant up
```

Will launch a new vagrant machine.

Remember, you can modify your `cookiecutter.json` file to not be
prompted by a bunch of stupid questions. Read the installation
instructions.

## Contribution

Contribute fixes to making streamlined cookbooks / vagrant files for the community!

## TODO

- Add a pre gen hook to install vagrant, if missing
- Add a post gen hook to install vagrant-berkshelf, if missing
- Add a post gen hook to install vagrant-aws, if missing
- Add a post gen hook to install vagrant-omnibus, if missing
- Add a post gen hook to install vagrant-butcher, if missing
