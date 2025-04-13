# qwool's fav hugo template
![a screenshot](./screenshot.png)
## why?
- supports relly niche features like plaintext posts through the unformatted flag in frontmatter and has a nice shortcode for music
- it looks really nice and bold
- i would be really happy if you were to use it

## how 2 use
### as a template
1. clone it
2. put your own stuff into the `content` folder
3. run `hugo build` and take the files out of the `public` directory

if you're don't know anything about hugo but wanna learn it, watch [luke smith's video on it](https://www.youtube.com/watch?v=ZFL09qhKi5I)

### as a theme

1. go to your hugo site folder (or make a new one with `hugo new site my-site`)
2. inside the site folder, do:

   ```bash
   git submodule add https://github.com/qwool/april.hugo.git themes/april.hugo

in your config.toml, add:

    theme = april.hugo

move your content into the ```content/``` folder of your site

run it:

    hugo server -D

    # now go make something

## how to REALLY use it

im just getting started on this, so if you think something is missing, open an issue or a pull request

