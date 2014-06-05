# hub repositories sub command

Add the `repositories` sub command to [hub](https://github.com/github/hub).

## Installation

```bash
sed 's|PREFIX=/usr/local|PREFIX=$HOME/local|' install.template | \
sed 's|PROFILE=/etc/profile|PROFILE=$HOME/.zshenv|' > install && \
chmod +x install
# or other commands as you like

./install
```

## Usage

```bash
hub repositories
#=> Output all repository names of your GitHub public repositories.
```

## License

[MIT](http://opensource.org/licenses/MIT)

Copyright (C) 2014 ka
