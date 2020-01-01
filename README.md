# kubernetes
Kubernetes の勉強

# IDE のインストール
1. Visual Studio Code　をインストール
https://code.visualstudio.com

2. 拡張機能をインストール
ショートカットキー：[Ctrl] + [Shift] + [X]

 1 Docker Support for Visual Studio Code
 2 Visual Studio Code Kubernetes Tools
 3 Japanese Language Pack for Visual Studio Code

# Azure CLI のインストール
1. MSI をダウンロード
https://aka.ms/installazurecliwindows

2. Azure CLI インストール手順
https://docs.microsoft.com/ja-jp/cli/azure/install-azure-cli

3. Azure CLI で Azure にログイン
$ az login

# kubectl コマンドのインストール
1. インストール手順
https://kubernetes.io/ja/docs/tasks/tools/install-kubectl/#windows%E3%81%B8kubectl%E3%82%92%E3%82%A4%E3%83%B3%E3%82%B9%E3%83%88%E3%83%BC%E3%83%AB%E3%81%99%E3%82%8B

2. v1.17.0 のバイナリ
https://storage.googleapis.com/kubernetes-release/release/v1.17.0/bin/windows/amd64/kubectl.exe

3. C:\WIndows にkubectl.exe を配置

4. バージョン確認
kubectl version

# PSGallery から Powershell でインストールする方法
Install-Script -Name install-kubectl -Scope CurrentUser -Force
install-kubectl.ps1

# Azure CLI からインストール
az aks install-cli

# Azure Cloud Shell の利用
https://shell.azure.com/

Cloud Shell は様々なツールがインストールされている
| 種類 | ツール |
| --- | --- |
| Linux ツール | Bash, zsh, sh, tmux, dig|



