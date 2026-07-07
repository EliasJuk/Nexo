# Nexo

#### Aplicação desktop desenvolvida com Flutter.
---

## Requisitos

- Flutter SDK
- Visual Studio 2022 com Desktop development with C++

## Primeira execução
## Execute:

```bash
# Utilize a opção **1** para instalar/configurar o Flutter.
> run-dev.bat
```


## Executar

```bash
# Utilize a opção **4** para executar o projeto.
> run-dev.bat
```



## Gerar build

```bash
# Utilize a opção **6** para gerar a versão Release.
> run-dev.bat
```

---
---
---
---

## Executar (manualmente)

```powershell
# Clone o repositório:
git clone https://github.com/#/Nexo.git

# Adiciona temporariamente o Flutter ao PATH desta sessão do PowerShell.
# Não altera o PATH do Windows permanentemente.
$env:Path = "C:\flutter\bin;$env:Path"

# Verifica se o Flutter está instalado e exibe sua versão.
flutter --version

# Baixe as dependências:
> flutter pub get

# Execute a aplicação:
> flutter run -d windows
```

## Gerar build

```bash
# Gere a versão Release:
> flutter build windows
```
