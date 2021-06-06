# バージョン
- gcc 6.4.0
- glibc 2.25
- linux kernel 4.9.186

# インストール先
- /opt/corss/aarch64

# 確認済みホスト
- Ubuntu 20.04.2.0 LTS

# 必要なツール
- gcc
- g++
- gawk
- texinfo
- make
- libarchve-tools

# ビルド手順
- ./download.sh
- sudo -E ./build.sh

# 使用手順
- export PATH=$PATH:/opt/cross/aarch64/bin
- aarch64-linux-gnu-gcc --version

