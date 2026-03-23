# StockStack CLI

日本株ファンダメンタル分析ツール [StockStack](https://stockstack.app) の CLI クライアント。

## Install

### macOS (Homebrew)

```sh
brew install stockstack-app/stockstack/stockstack
```

### Shell (macOS / Linux)

```sh
curl --proto '=https' --tlsv1.2 -LsSf https://github.com/stockstack-app/stockstack-cli/releases/latest/download/stockstack-installer.sh | sh
```

### PowerShell (Windows)

```powershell
powershell -ExecutionPolicy Bypass -c "irm https://github.com/stockstack-app/stockstack-cli/releases/latest/download/stockstack-installer.ps1 | iex"
```

## Update

```sh
stockstack update
```

## Usage

```sh
stockstack --help
```
