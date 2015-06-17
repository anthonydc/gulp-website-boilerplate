For all of this magic to work, your computer needs a few extra files to get Gulp up and running in your project.

You'll need to make sure you have both [Node](http://nodejs.org) and [Gulp](http://gulpjs.com) installed before moving forward. If you already have both, keep on going, and if not, you'll only need to install them once.

Navigate to your project directory using the command line and run the following command:

    npm install

Then run gulp

That's it! You're ready to start using Gulp.

Using Gulp

==========

Default Task

------------

    gulp

Running the default task automatically watches your project folders for any changes and runs the accompanying task. For example, anytime you change a JavaScript file gulp will automatically run those tasks, including a browser refresh if you've included BrowserSync.

CSS

---

    gulp styles

Running the gulp styles task will run your selected CSS tasks once.

JavaScript

----------

    gulp scripts

Running the gulp scripts task will run your selected JavaScript tasks once.

Images

------

    gulp images

Running the gulp images task will run your selected image tasks once.