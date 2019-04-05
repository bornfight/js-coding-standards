# TSLint

Some of the guidelines for usage of TSLint

## PHPStorm Code Style

- _degordian-code-style.xml_
    - import this code style under _TypeScript_ section in _Preferences -> Code Style_
    - it has all rules for matching TSLint from this repository
    - additional links to setup _PHPStorm_ to match TSLint:
        - Remove trailing whitespaces [(link)](http://www.craftitonline.com/2011/06/set-phpstorm-to-remove-trailing-spaces-on-lines/)
        - End in new line [(link)](https://stackoverflow.com/questions/16761227/how-to-make-intellij-idea-insert-a-new-line-at-every-end-of-file)
    - Standard way of using it:
        - use _Reformat code_ action
        - just let it save
        - if you are using _git_ through _PHPStorm_, turn on flags for _Reformat code_, _Rearrange code_ and _Optimize imports_
