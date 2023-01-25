# plantuml-wasm
PlantUML Web Assembly with using CheerpJ

`npx http-server`

# Compiling steps (if you want to re-compile)

```shell
wget https://d3415aa6bfa4.leaningtech.com/cheerpj_linux_2.3.tar.gz -O - | tar -xz
# download plantuml
wget https://github.com/plantuml/plantuml/releases/download/v1.2023.0/plantuml-1.2023.0.jar
# compile it
./cheerpj_2.3/cheerpjfy.py plantuml-1.2023.0.jar
```
