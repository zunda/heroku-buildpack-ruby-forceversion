# heroku-buildpack-ruby-forceversion
A Heroku buildpack to force ruby version

With this buildpack installed, `ruby --version` is always `ruby 3.3.0preview3 (2023-11-12 master 60e19a0b5f) [x86_64-linux]`.

## Install
```
heroku buildpacks:add -i 1 https://github.com/zunda/heroku-buildpack-ruby-forceversion.git
heroku buildpacks:add -i 2 heroku/ruby
git push heroku master
```
