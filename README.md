# shinylive_test

```
pip install shiny
pip install shinylive
```

```
shiny create myapp
```

```
shinylive export myapp docs
```
Preview:
```
python3 -m http.server --directory docs 8008
```
Commit the `./docs` folder to git. In the repo settings->Pages select "Deploy from branch" `main` branch and `./docs`folder and voila!

https://davesteps.github.io/shinylive_test/

