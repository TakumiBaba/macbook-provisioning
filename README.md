TakumiBaba's Provisioning file
---

- version 2015/10/14
- clone from
  - [Github:twada/macbook-provisioning](https://github.com/twada/macbook-provisioning)
  - [Blog:Mac の開発環境構築を自動化する (2015 年初旬編)](http://t-wada.hatenablog.jp/entry/mac-provisioning-by-ansible))
-

# command

```
% HOMEBREW_CASK_OPTS="--appdir=/Applications" ansible-playbook -i hosts -vv localhost.yml
```
