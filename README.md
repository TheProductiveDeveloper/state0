# state0 Linux - opinionated postinstall script

*Note: For non-opinionated a template, go to [state0_template](https://github.com/TheProductiveDeveloper/state0_template).*

state0 is a stable, modern, easy to configure and opinionated Linux (configuration as code postinstall script). It is conceptually similar to [Omarchy](https://omarchy.org/), but production-stable and easier to make your own. This setup script will help you to quickly init new machines for your personal & professional use with all your packages, configuration and settings installed in 10-30mins. It also includes CI via GitHub Actions so you can be always certain that the configuration you are applying is not broken.

### Similar concepts & tech:
- What a Dockerfile is to Docker image, state0 is to your Desktop/CLI Linux,
- state0 is like Ansible/Chef/Puppet, but much easier to use & understand (even a 12 year old child should be able use & modify it) and with no dependencies other than Bash,
- state0 is like NixOS, but with much steep learning curve - in NixOS it is much easier to revert changes, but at the cost of complexity. Even though state0 is less deterministic and reverting changes is more tricky in state0, in 95% of practical issues, the state0 way is sufficient enough,
- state0 also a bit like a .deb metapackage with some extra configuration...

### Keeping your Linux configuration as code is useful when:
- reinstalling your desktop Linux - reinstallation & configuration takes minutes instead of days,
- you want to be sure that your config change is not buggy, before you apply it to your machine (this repo includes CI script and easy integration test via GithubActions),
- for keeping configuration on numerous machines you use (including Android Termux) in sync,
- when you want to share/review/modularize your Linux config,
- having your configuration as code helps you with troubleshooting if sth breaks,
- you want to create an easy configure script for your new coleagues, so that they don't need to follow outdated internal setup guides,
- you want to make more informed choices about your configuration & feel less fear when experimenting with configuration changes on your Linux machine (if you break sth. you can allways revert your commit and rebuild your machine),
- you want to manage your dotfiles the same way as any other Git repo (bare Git repo dotfile manager included)...





