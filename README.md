# My personal page

This repo hosts my personal website written with [`hugo`](https://gohugo.io/).

To check the rendered result, go to [https://fabgilson.github.io](https://fabgilson.github.io).

## To set up

1. Clone this repo
2. Import theme as submodule: `git submodule add git@github.com:fabgilson/hugo-anatole-fork.git`
3. Init and update submodule

```
git submodule init
git submodule update
```

4. Look in `config.toml` for more.

## Basic workflow to update website:

1. make changes and use `$ hugo server -D` (possible adding '-p PORT' if needed)
2. `$ hugo` (to build the `/public` folder containing the static website)
3. `$ cd public`
4. `$ git add .`
5. `$ git commit -m "my changes"`
6. `$ git push origin master` (public needs to be a submodule pointing to fabgilson.github.io magic repo)
7. `$ git add` the changes and push them

Make sure the public folder is in `.gitignore`.

## To push to the static website

If submodule (for public) not set up yet:
```
cd public
git init
git add .
git remote add origin https://github.com/fabgilson/fabgilson.github.io.git
```

# Credits

Thanks to:
- Yuanyuan Ge, https://levelup.gitconnected.com/build-a-personal-website-with-github-pages-and-hugo-6c68592204c7
- Go Hugo, https://gohugo.io/getting-started/quick-start/