# vonbarbarosa.github.io

## Setup

1. Install **Ruby**

    ```
    sudo apt-get install ruby-full build-essential zlib1g-dev
    ```

1. Set the gem installation dir for your user account, running in the terminal:

    ```
    echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
    echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
    echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
    source ~/.bashrc
    ```

1. Install **Bundler**

    ```
    gem install bundler
    ```

## Run the site locally

Run the command in the root folder:

```
bundle exec jekyll serve
```