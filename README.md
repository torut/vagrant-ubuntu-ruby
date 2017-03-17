# vagrant-ubuntu-ruby

## Vagrant で Ruby 開発環境を構築するための一式.

ansible の部分がサブモジュールになっているので clone したあとに `git submodube update --init` が必要となるので注意.

---

## 使い方

`vagrant up` したあとに `vagrant ssh` して `ansible-playbook` をする.

詳しくは vagrant up した時の最後に表示されるメッセージを確認.
