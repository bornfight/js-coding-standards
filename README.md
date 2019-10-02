# js-coding-standards
Degordian js coding standard



# Contributing

Procedure for adding new rules to the repository after code reviewing:
1.  Check if the error is recurring or critical (important for everybody)
2.  Create a pull request
    1.  Write a rule to correct the mistake
    2.  Write a short code snippet (https://help.github.com/articles/creating-and-highlighting-code-blocks/)
        1.  Keep it generic
        2.  Minimal code possible
        2.  Avoid copy/pasting from private projects
3.  Create a pull request
4.  If the rule can be automated, write a rule for ESlint   
  
  
  
## Prettier setup
Using the config in your project:
https://prettier.io/docs/en/configuration.html#sharing-configurations

1. add prettier as a project dependency (yarn add prettier | npm install prettier)
2. add prettier config key to package.json, e.g.:
    ```
    {
        "name": "my-awesome-project",
        "version": "0.1.0",
        "prettier": "@degordian/standards/standards/prettier/.prettierrc.json"
    }
    ```
3. [Configure your IDE for formatting](https://prettier.io/docs/en/editors.html)
4. If you want to format the whole codebase recursively, run this command (or add it to npm scripts)
    * *you may need to change the source directory and extensions based on your criteria 
    ```
    prettier --write \"{src,test}/**/*.{ts,tsx,js,jsx,scss}\"
    ```
5. Success, you may now enjoy meaningful code reviews that focus on logic and features, and not the formatting. 🎉  
  
