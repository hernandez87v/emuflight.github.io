# emuflight.github.io

## Install Ruby and other [prerequisites](https://jekyllrb.com/docs/installation/#requirements):

```shell
sudo apt-get install ruby-full build-essential zlib1g-dev

echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc

gem install jekyll bundler

git clone git@github.com:emuflight/emuflight.github.io.git

cd emuflight.github.io
bundle install
bundle exec jekyll serve
```
Once changes are ready to go live to the IO site run: 

```
bundle update github-pages
```