# My personal page

This repo hosts my personal website written with [`hugo`](https://gohugo.io/).

To check the rendered result, go to [https://fabgilson.github.io](https://fabgilson.github.io).

## To set up

1. Clone this repo
2. Import theme as submodule: `git submodule add https://github.com/lxndrblz/anatole.git themes/anatole`
3. Init and update submodule

```
git submodule init
git submodule update
```

4. Look in `config.toml` for more.

## Basic workflow to update website:

1. make changes and use `$ hugo server -D` (possible adding '-p PORT' if needed)
2. `$ hugo` (to build the `/public` folder containing the static website)

## To push to the static website

```
cd public
git init
git add .
git remote add origin https://github.com/fabgilson/fabgilson.github.io.git
git add -A
git commit -m "your message"
git push --set-upstream origin master --force
```

# Credits

Thanks to:
- Yuanyuan Ge, https://levelup.gitconnected.com/build-a-personal-website-with-github-pages-and-hugo-6c68592204c7
- Go Hugo, https://gohugo.io/getting-started/quick-start/