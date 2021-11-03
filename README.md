# Stack using

Jekyll Now

# Preparation

1. For installing ruby and gem

```
sudo apt-get install ruby-full build-essential zlib1g-dev
```

2. Modify `.bashrc` in Linux (develop in Linux)

```
echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc
```

3. Install Jekyll and Bundler

```
gem install jekyll bundler github-pages
```

## Run local

Serve the site and watch for markup/sass changes `jekyll serve`
