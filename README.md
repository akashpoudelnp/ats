# ATS

An artisan command runner for your laravel projects.

## Features

- Configurable php version for your laravel project
- Run artisan commands with a specific php version
- Add/View/Delete custom aliases for artisan commands
- More in the future :)

## Installation

```bash
wget https://raw.githubusercontent.com/akashpoudelnp/ats/master/ats && chmod +x ats && sudo mv ats /usr/local/bin
```

## Usage

```bash
ats [command]
```

## Commands

```bash
ats --about          Show about message
ats --help           Show this help message
ats --php            Shows the configured php version for the project
ats --php-set        Sets the configured php version for the project
ats --update         Update the ats to latest version
ats --aliases        List all aliases
ats --aliases-add    Add new alias
ats --aliases-remove Remove alias
ats --reset          Reset the ats to default
ats --config-show    Show the config file
```

## Examples

```bash
ats migrate
```
