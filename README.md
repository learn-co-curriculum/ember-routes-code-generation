# Ember Routes - Code Generation
Ember has a feature that is really great, and you've been using it all along.

**Code generation**
![Nope](http://media3.giphy.com/media/bVkKlS6SbnQmA/200.gif)

Whoa! Slow down. This kind of code generation won't leave your directories cluttered with files. In fact, it will let you delete files if all they don't do anything. I'll give you an example.

When you visit the home page, all that gets rendered is the Application template. What if you wanted to customize the home page? You don't want to modify the layout since that would persist.
If you look at an Ember app in the [Ember Inspector](https://chrome.google.com/webstore/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi?hl=en) and click on the routes tab, you'll see that there's actually a route there named `index`.
![](https://readme-pics.s3.amazonaws.com/ember-console-index-route.png)

If you search for a template named `index.hbs` you won't find anything. Ember creates a route and a template on the fly since you're not using it.

Want to customize the home page?

Run `ember g route index` then edit the newly created `index.hbs` and...
![Voila](http://i.imgur.com/TsHPsht.gif)

## Other kinds of Code Generation
You'll see Ember create all kinds of objects for you from Controllers, to View objects. Like everything else in Ember, if the default is enough, leave it alone, but you can always generate your own to customize the app.

<a href='https://learn.co/lessons/ember-routes-code-generation' data-visibility='hidden'>View this lesson on Learn.co</a>
