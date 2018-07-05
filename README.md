# study_parceljs
---
## Introduction 

- typescript [v]
- postcss  [v]
    - sass  []
-  es6 as babel [v]
- hmr []
---
## install

1. parceljs global install 
```bash
npm install -g parcel-bundler
```

---
## setting 
### babel 

1. install 
    ```bash
    npm i -D babel-preset-env
    ```
2. creation .babelrc

3. .babelrc contents
    ```json
    {
        "presets": [
            "env"
            , "es2015"
        ]
    }
    ```

### postcss
1. install 
    ```bash 
    npm i -D postcss-modules autoprefixer
    ```
2. creation .postcssrc

3. .postcssrc contents 
    ```json
    {
        "modules": true,
        "plugins": {
            "autoprefixer": {
                "grid": true
            }
        }
    }
    ```

---


