# Summary

Make your life easier and install Atom. Then install the following packages to help you work with CloudFormation, Python and NodeJS code:

## CloudFormation YML Support
* atom-cform-yaml
* language-yaml-cloudformation
* linter-js-cloudformation-yaml

## Python Support
* language-python
* autocomplete-python
* python-tools
* linter-flake8

## General
* sync-settings
* git-plus
* minimap
* atom-beautify
* file-icons
* goto-definition

## Chef
* language-ruby
* language-chef
* language-habitat
* language-rspec
* language-inspec
* linter-rubocop
* linter-foodcritic

# Atom Extension Association
Atom includes a feature called "custom file types" which you can use by adding some entries into your config.cson that look like this:

```yml
core:
  customFileTypes:
    'source.yaml.cf': ['yml']
```
This will for example associate 'source.yaml.cf' with files ending in '.yml'.

To get a list of all scope names registered in your Atom instance, open the Developer Tools Console and execute the following:

```javascript
Object.keys(atom.grammars.grammarsByScopeName).sort().join('\n')
```
