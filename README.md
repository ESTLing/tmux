# tmux
tmux configuration

# setup
1. install [tpm](https://github.com/tmux-plugins/tpm)
2. install [powershell](https://github.com/powerline/powerline)
3. use `prefix`+`i` to install plugins
4. use `prefix`+`r` to reload configures

# practices
Although tmux is powerful, it is not easy to find best practices for everyone. I record my practice here, hope it will helpful for some beginners.
1. I often map the level of `session`, `window`, and `panel` like this: `session`-a big workspace related to multiple projects; `window`- one project; `panel`- minimum working zone, i.e., coding panel, watching panel and so on.
2. Naming sessions with a priority number, it's helpful to find your workspace. Like 0-gitlab-runner; 1-xxx-project. The number prefix is a priority number, since the sessions are ordered by name in choose-tree view by default.
