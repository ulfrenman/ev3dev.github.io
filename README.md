ev3dev.github.io
================

This is the web page at <http://www.ev3dev.org> and also <http://ev3dev.github.io>.

Feel free to fork and make a pull request.

You can view your changes locally by installing [jekyll](https://help.github.com/articles/using-jekyll-with-pages).

Installing Jekyll in Ubuntu 14.04
---

    sudo apt-get install git ruby1.9.1 ruby1.9.1-dev nodejs
    sudo gem install bundler
    git clone git@github.com:<user>/ev3dev.github.io
    cd ev3dev.github.io
    bundle install
    bundle exec jekyll serve --watch &
    www-browser http://localhost:4000 &
    # work, work, work

Installing Jekyll in  Windows
---

- Follow the instructions in step 1 [here](http://jekyll-windows.juthilo.com/1-ruby-and-devkit/) (Installing Ruby and the Ruby DevKit).

Then run:

    gem install bundler
    git clone https://github.com/<user>/ev3dev.github.io
    cd ev3dev.github.io
    bundle install
    bundle exec jekyll serve --watch

Now you should be able to visit your page at: [http://localhost:4000](http://localhost:4000). It should auto-update when you change the source files, so all you have to do is refresh your browser.

Previewing Your Changes Online
---

When forking, you can create a new branch called `gh-pages`, then your
changes can be viewed as `http://<user>.github.io/ev3dev.github.io`. When you do this
though, GitHub will send you lots of email like this, which you should ignore.

    The page build completed successfully, but returned the following warning:
    
    CNAME already taken: www.ev3dev.org
    
    For information on troubleshooting Jekyll see:
    
      https://help.github.com/articles/using-jekyll-with-pages#troubleshooting
    
    If you have any questions please contact us at https://github.com/contact.
    
If it really gets on your nerves, you can rename the `CNAME` file. Just make sure to
change it back before you submit your pull request.


