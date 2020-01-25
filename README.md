
# case6-clasp-with-gas-clasp-starter-use-circle-ci
[howdy39/start-modern-gas-with-google-clasp: Google clasp ではじめるモダンな Google Apps Script 開発](https://github.com/howdy39/start-modern-gas-with-google-clasp)

上記プロジェクトの case4-clasp-with-gas-clasp-starter を CircleCI を使って PR マージ時にデプロイするようにしたバージョンです。

## CircleCI の環境変数の設定
```
$ cat ~/.clasprc.json
```

の結果を CircleCI の環境変数に入れて `scripts/deploy-ci.sh` でそのまま `~/.clasprc.json` に出力しています。

![image](https://user-images.githubusercontent.com/6329532/73117645-6030be80-3f8c-11ea-9656-966c8a19c74e.png)
