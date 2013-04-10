
<a href="https://travis-ci.org/startupsupper/startupsupper.github.com" target="_blank"><img src="https://api.travis-ci.org/startupsupper/startupsupper.github.com.png" alt="" /></a></sup>
# StartupSupper

Recipes for Bootstrappers & Hungry Hackers

Curated by [Nick][1], [Teng][2], and [Jacob][3]

[1]: http://niftylettuce.com
[2]: http://www.strikingly.com
[3]: http://lepahc.com


## Support

Join us on [IRC WebChat](http://webchat.freenode.net/?channels=startupsupper) or with a client in `#startupsupper` on `irc.freenode.net`.

You can also email <startupsupper@gmail.com> or file an [Issue](https://github.com/startupsupper/startupsupper.github.com/issues/new).


## Contribute Recipes

Easily submit your recipe following these instructions:

1. Fork this repository and clone it locally.

    > Checkout the "source" branch, not "master".

2. Copy/rename the recipe template folder.

    > (e.g. `./contents/recipes/template/` &rarr; `./contents/recipes/chicken-noodle-soup/`)

3. Edit the `index.md` file inside your copied recipe template folder.

    > Include a relevant title, list of ingredients, photos (optional), and instructions.

4. (optional) Copy/rename the author template and update `index.md` respectively.

    > (e.g. `./contents/authors/template.json` &rarr; `./contents/authors/your-name.json`)

    ```diff
    -author: Your Name
    +author: your-name
    ```

5. (optional) Preview your recipe at <http://localhost:8080> (requires [node](http://nodejs.org))

    ```bash
    cd ~/startupsupper.github.com/
    npm install
    ./preview
    ```

6. Submit a new pull request, we'll merge it, and your recipe will be automatically published.

    ```bash
    git push origin source
    ```

    > Then visit your fork of the repo on Github and submit a pull request for us.

    > (e.g. <http://startupsupper.com/recipes/pepper-steak-stir-fry>)


## Lazyweb Requests

- [ ] Add <http://blueimp.github.com/Bootstrap-Image-Gallery/>
- [ ] Add easy UI or some type of modal slideshow for launching "Cooking Mode", where spacebar or arrow keys drive user through steps array
- [ ] CLI helper tool to create recipe, add instructions, and submit github pull request using github apiv3
- [ ] Integrate <https://github.com/christophercliff/wintersmith-kelvin>
- [ ] add kicksend or component email check (e.g. autocorrect gmail address)
- [ ] verify pinterest page
- [ ] add photo and thumbnails for template recipe
