# Evolution of Configuration: From Monolithic `.zshrc` to Modular Setup

For a long time, my zsh configuration was a reflection of my journey through the command line. 
I used to throw everything into the `.zshrc` file: It was a one-stop-shop for all my Zsh settings, from aliases to complex prompt configurations. 
While this approach worked initially, as my command-line needs evolve, so did the challenges associated with maintaining a monolithic `.zshrc` file.

As my expertise grew and my zsh customization needs became more intricate, I began to notice several pain points associated with my approach:

- **Readability and Maintenance**: the `.zshrc` file started to be a mess. Finding specific configurations or making sense of the overall structure became increasingly challenging

- **Sharing and porting**: sharing specific aliases or functions with others was not immediate. Furthermore, `.zshrc` porting was not straightforward

## Building a custom structure

Realizing the above mentioned limitations, I decided it was time for a paradigm shift. 

The breakthrough came when I discovered the power of Zsh modular configurations.

I started organizing my settings into separate files. Each file is a specific aspect of my Zsh setup, from aliases and functions to plugins and theme configurations. 

### Zsh custom folder

The custom folder provided by Zsh is represented by the following env. variable `ZSH_CUSTOM`. 

You can then see what's inside your custom folder by opening any terminal, and launching `echo $ZSH_CUSTOM`. 

```
> echo $ZSH_CUSTOM
/Users/anegrini/.oh-my-zsh/custom
```

Within this directory, you'll discover several sample settings that are optional for deletion. Conversely, you have the flexibility to arrange your aliases, functions, environment variables, secrets, and more according to your preferences.

It's worth noting to remind you to use the `.zsh` extension. 

This should allow to maintain a clear organization while keeping the clutter at bay.

## Clone my settings

I've recently begun enhancing the organization of my personal Zsh environment, and this repository is meant to house various elements such as aliases, functions, environment variables, and more.

This process will take some time, and I'll be gradually committing new files and settings. If you're interested in adopting my Zsh configurations, or a specific part of them, feel free to clone the repository and seamlessly integrate its contents into your custom folder. 
