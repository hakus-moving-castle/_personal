# PNPM

## Initialization

1.  Init repository

    ```bash
      pnpm init
    ```

2.  Setup node version and package manager in `package.json`

    > This is important for CI/CD and local development to ensure the same version of node and package manager is used.

    ```json
    {
      "packageManager": "pnpm@10.6.1",
      "engines": {
        "node": ">=22.0.0" // Recommend to set to latest LTS version
      }
    }
    ```
