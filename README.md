# hub repositories sub command

```bash
sed 's|PREFIX=/usr/local|PREFIX=$HOME/local|' install.template | \
sed 's|PROFILE=/etc/profile|PROFILE=$HOME/.zshenv|' > install && \
chmod +x install
# or other commands as you like

./install
```

## License

[MIT](http://opensource.org/licenses/MIT)

Copyright &copy; 2014 ka
