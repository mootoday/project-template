# project-template

This template is the foundation for my projects. It leverages the following tools:

* [Devbox](https://github.com/jetify-com/devbox)
* [tmux](https://github.com/tmux/tmux)
* [tmuxp](https://github.com/tmux-python/tmuxp)
* [gh](https://github.com/cli/cli) and [gh-dash](https://github.com/dlvhdr/gh-dash)

Devbox installs and configures all necessary dependencies.

`tmuxp` configures a `tmux` session with panes. This provides a consistent terminal layout for every project.

`gh` is GitHub's CLI and `gh-dash` a `gh` extension to work with GitHub pull requests and issues right from within the terminal.

## Usage

Install Devbox on your system:

```sh
curl -fsSL https://get.jetify.com/devbox | bash
```

Run the following command to start `tmux` and set up the layout with the various apps:

```sh
devbox run tmux
```

## Configuration

The configuration files for the tools can be found in the `./.config` directory. Refer to the official documentation for details on the available features.

