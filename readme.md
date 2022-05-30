# 起点
https://github.com/kajirikajiri/jamstack-tech-blog/discussions/84

# やること
https://github.com/kajirikajiri/jamstack-tech-blog/discussions/81#discussion-4104852

# task
- [ ] 取得したい内容は[これ](https://github.com/kajirikajiri/jamstack-tech-blog/discussions/81#discussion-4104852)っぽい
    - [ ] 別のブランチ(public)をclone
        - https://github.com/mui/material-ui
        - https://github.com/facebook/react
        - https://github.com/react-hook-form/react-hook-form
        - https://github.com/cypress-io/cypress
        - https://github.com/facebook/jest
        - https://github.com/nvh95/jest-preview
        - https://github.com/babel/babel
        - https://github.com/rome/tools
    - [ ] 取得したい内容を取得して、ファイルに書き込み
        - find . -type f -mindepth 10 | grep ".js" | grep -v "node_modules"
        - find . -type f -size +100k | grep ".js" | grep -v "node_modules"
    - [ ] [自動PR, 自動merge](https://zenn.dev/tatsurom/articles/actions-auto-merge)したい
- [x] [cronで月に１回実行](http://engineer-memo.goodhead.work/pages/71)したい
    - [x] testの時は[手動でtrigger](https://docs.github.com/ja/actions/managing-workflow-runs/manually-running-a-workflow)したい