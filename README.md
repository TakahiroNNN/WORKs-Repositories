# WORKs-Repositories
創作物まとめ

# Gitコマンド
- [git addとcommit、pushの関係をわかりやすく解説する【Gitコマンド解説①】](https://zenn.dev/atsushi101011/articles/4e0e36d238a3b8)
- [git fetchとmerge、pullの関係をわかりやすく説明する【Gitコマンド解説②】](https://zenn.dev/atsushi101011/articles/f66617b53f71ea)

## git submodule
親リポジトリのトップディレクトリで、サブモジュール化するリポジトリを宣言
```
git submodule add http://github.com/~~~.git
```
git のステータスを確認、gitmodule の状態を確認
```
git status
cat .gitmodules
```
コミット、プッシュ
```
git commit -m "git add XXX repository"
git push
```
