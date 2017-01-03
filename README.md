# InstantYoutube App

InstantYoutube is a simple Youtube search app built with ReactJS. Search results are loaded instantaneously.

###Getting Started###

Clone this repo, install dependencies, then start the gulp process with the following:

```
  > git clone git@github.com:zavier-sanders/instant-youtube.git
  > cd instant-youtube
  > npm install
  > npm start
```

In order to deploy this to SharePoint, make sure you edit the package.json file. Change the homepage setting to reflect the path to your application.

```
  > "homepage": "/sites/developer/SiteAssets/instant-youtube"
```

Then build a copy to deploy to SharePoint:
```
  > npm run build
```

Once the build completes, then copy the files in the build folder to the SharePoint Site Assets library. Place a Content Editor Web Part onto a page and reference the index.html file.
