# Hugo Journal

## _Keep it simple, but not simpler_

**Journal** is a Hugo theme designed for VEX Robotics teams to use when publishing a digital engineering journal. Based upon [hugo-xmin](https://github.com/yihui/hugo-xmin), originally written by [Yihui Xie](https://yihui.name), the theme's goal is to be clean, small, and have only as many features as is strictly necessary.



## Try it out!

If you're not already using Hugo, follow the [Quick Start Guide](https://gohugo.io/getting-started/quick-start/) to set it up. Then, within your Hugo project, run these commands to install the Journal theme:

```bash
git submodule add https://github.com/9623-Warp-Drive/hugo-journal.git

echo 'theme = "hugo-journal"' >> config.toml
```



## Make it yours!

If you'd like to customize the theme for your own use, you can make some changes in your `config.toml` file. Here is an example:

```toml
[[menu.main]]
    name = "Home"
    url = "/"
    weight = 1
[[menu.main]]
    name = "Notebook Entries"
    url = "/posts/"
    weight = 2

[params]
    description = "9623Z's notebook for the 2020-2021 season of VEX Robotics Competition - Change Up."
    license = "This site is licensed under the [CC BY-NC-SA 4.0](http://creativecommons.org/licenses/by-nc-sa/4.0/) license."
    contact = ""
```



## Open source!

Journal is available under the MIT license. That means you're free to do basically whatever you want with it - so go ahead and tweak it! If you think your contributions could be helpful to others, submit a [pull request](https://github.com/9623-Warp-Drive/hugo-journal/pulls) to add them to this repository.