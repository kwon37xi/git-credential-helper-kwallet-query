# git-credential-kwalletcli

git credential helper for KWallet5 with `kwalletcli` command.

## Requirements
* [MirBSD: kwalletcli — CLI for the KDE Wallet](http://www.mirbsd.org/kwalletcli.htm)

```
# on ubuntu/debian
sudo apt install kwalletcli
```

## Installation
```
sudo wget -O /usr/local/bin/git-credential-kwalletcli \
    "https://raw.githubusercontent.com/kwon37xi/git-credential-kwalletcli/main/git-credential-kwalletcli" \
    && sudo chmod 0755 /usr/local/bin/git-credential-kwalletcli

# for your local user
git config --global credential.helper kwalletcli
```

## References
* [Git - Credential 저장소](https://git-scm.com/book/ko/v2/Git-%EB%8F%84%EA%B5%AC-Credential-%EC%A0%80%EC%9E%A5%EC%86%8C)
* [Templar-von-Midgard/git-credential-kwallet: Git credential helper for KWallet](https://github.com/Templar-von-Midgard/git-credential-kwallet)

## TODOs
* `erase` : `kwalletcli` does not support erase
