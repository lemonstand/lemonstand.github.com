# This is our community projects page.

Isn't it lovely?

## Update the repo JSON

The community site caches the repo JSON to prevent calling Github for every page load. To update:

```
$ ./bin/update-repos.sh
$ git push origin master
````

## Instructions

1. Install Jekyll (`sudo gem install jekyll`). This kinda assumes `gem` is installed too.
2. Run Jekyll (`jekyll serve`). This does all the Jekyll-ing, as well as serving up the site.
3. Edit. Test. Test. Edit. Push. You can preview the site locally (`http://127.0.0.1:4000/`), or follow the instructions in the Terminal.