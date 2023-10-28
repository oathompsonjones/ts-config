# @oathompsonjones/ts-config

This package provides my TypeScript configurations.

### How to use a configuration
- Step 1: Install this package
    Run `npm install @oathompsonjones/ts-config` to add this package to your project.

- Step 2: Create your tsconfig.json file
    Create a file in the root of your project called `tsconfig.json`.
    Paste the following code:
    ```json
    {
        "extends": "@oathompsonjones/ts-config"
    }
    ```
    You can also include extra options like this:
    ```json
    {
        "extends": "@oathompsonjones/ts-config",
        "include": [
            "src"
        ],
        "compilerOptions": {
            "outDir": "build"
        }
    }
    ```

- Step 3: You're done!