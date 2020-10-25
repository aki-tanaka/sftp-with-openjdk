# sftp-with-openjdk

## 背景
開発環境の制約によりホスト側のディレクトリをマウントすることができないため、SFTPによるファイル編集を行うようにする必要がある。  
OpenJDK8がインストールされている必要があるため、[atmoz/sftp](https://github.com/atmoz/sftp "atmoz/sftp")のベースイメージをopenjdk8に変更する。  
