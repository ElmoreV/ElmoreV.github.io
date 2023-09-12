<b>Hi, welcome to the code of my [site](ElmoreV.github.io), which is hosted on [GitHub](https://github.com/ElmoreV/ElmoreV.github.io)

To set-up, go to: https://jekyllrb.com/docs/

With Windows installation, I had to do:
https://jekyllrb.com/docs/installation/windows/

Now, the command 'bundle exec jekyll serve' in the 'Elmore.github.io'-repository folder should work.
However, it didn't, so I needed to do the following things:
1. Change the Gemfile to uncomment the github-pages comment\
2. And comment the jekyll version statement
3. Delete/rename the Gemfile.lock to e.g. Gemfile_old.lock 
4. Run 'bundle install'
5. Run 'bundle add webrick' 

Now we can run [hello](www.goggle.com)

bundle exec jekyll serve
