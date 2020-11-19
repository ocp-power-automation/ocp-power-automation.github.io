# How to update the documentation

1. Clone git@github.com:ocp-power-automation/docs.git and make changes
2. Validate changes by creating a local server
    ```
    $ cd ocp-power-automation/docs
    $ mkdocs serve

    connect to http://127.0.0.1:8000 and validate the changes
    ```
2. Commit the changes to git@github.com:ocp-power-automation/docs.git
3. Run following command to create the github page
    ``` $ cd ocp-power-automation/docs
        $ mkdocs gh-deploy --config-file  ./mkdocs.yml
    ```
    This will update the `gh-pages` branch in git@github.com:ocp-power-automation/docs.git. Refer https://www.mkdocs.org/user-guide/ for mkdocs documentation.
