# github-pkg-demo

This is my first Github package (yay!)

Follow these instructions to install and run this package:

## Installing GitHub Packages

1. Create a local `.npmrc` file in the project directory where the package will be installed and add the following code:

    ```sh
    @OWNER:registry=https://npm.pkg.github.com
    ```

    **Note**: Be sure to replace OWNER with your personal GitHub username.

2. Add the package name to the list of dependencies located in your `package.json` file.

    ```json
    "dependencies": {
        "@<YOUR_GITHUB_USERNAME>/github-pkg-demo": "1.0.0"
    },
    ```

3. Then, simply run `npm install` as you normally would.

    ```sh
    npm install
    ```
