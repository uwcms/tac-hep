# tac-hep website

For local build Ruby needs to be installed. Instructions can be found [here](https://jekyllrb.com/docs/installation/)

## Run locally
The site is built with Jekyll, and is easy to run locally if you have Ruby. To set up a “bundle” (local virtual environment in Python terms):
```
bundle install
```

## Build and deploy website

**To check website on localhost:**
```bundle exec jekyll serve```


**To build website:**
```bundle exec jekyll build```


**To deploy static site :**
* Build website from ```main``` branch
* Check that everything looks fine on localhost
* Switch to the ```gh-pages``` branch
* Copy the contents of the ```_site``` directory from ```main``` to ```gh-pages``` 



Instructions to do so:

```
git clone 
git checkout main 
```

Perform all needed editing. Then run :

```
bundle exec jekyll serve
```

If all look fine on localhost :
```
git add .
git commit -m "comment on changes"
git push
bundle exec jekyll build
mv _site ../.
git checkout gh-pages
mv ../_site .
scp -r _site/* .
git add .
git commit -m "comment on changes"
git push origin gh-pages
```
