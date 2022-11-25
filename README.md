<p align="center"><img src="./app/assets/images/SealCircle.svg" width="150px" height="150px" alt="aventium softworks"></p>

<h1 align="center">TokiwaLauncher</h1>

<em><h5 align="center">(formerly Electron Launcher)</h5></em>

[<p align="center"><img src="https://img.shields.io/github/downloads/TokiwaHaruto/TokiwaLauncher/total.svg?style=for-the-badge" alt="downloads">](https://github.com/TokiwaHaruto/TokiwaLauncher/releases)</p>

| Platform | File |
| -------- | ---- |
| Windows x64 | `TokiwaLauncher-setup-VERSION.exe` |
| macOS with Intel CPU | `TokiwaLauncher-setup-VERSION.dmg` |
| macOS with AppleSilicon CPU | `TokiwaLauncher-applesilicon-setup-VERSION.dmg` |
| Linux x64 | `サポート対象外` |

## Console

エラーが発生した場合、コンソールを開くことで内容を確認できる場合があります

```console
ctrl + shift + i
```

![console example](https://i.imgur.com/T5e73jP.png)


## Development

### Getting Started

**System Requirements**

* Install Dependencies: Node.js v16.16.0
* Build Installers: Node.js v16.16.0

---

**Clone and Install Dependencies**

```console
> git clone https://github.com/TokiwaHaruto/TokiwaLauncher.git
> cd TokiwaLauncher
> npm install
```

---

**Launch Application**

```console
> npm start
```

---

**Build Installers**

プラットフォームごとにコマンドを下記実行

| Platform    | Command            |
| ----------- | ------------------ |
| Windows x64 | `npm run dist:win` |
| macOS       | `npm run dist:mac` |

!! mac OS用のインストーラはIntel,AppleSiliconそれぞれのプロセッサごとに実機でbuildが必要

---