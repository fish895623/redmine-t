# trans_patch

Description goes here


## Generate Plugins

```bash
bundle exec rails generate redmine_plugin <plugin_name>
```


## Install Plugins
```bash
bundle exec rake redmine:plugins:migrate
bundle exec rails generate redmine_plugin_model polls poll question:string yes:integer no:integer
```

## Delete Plugins

```bash
bundle exec rake redmine:plugins:migrate NAME=plugin_name VERSION=0
```

