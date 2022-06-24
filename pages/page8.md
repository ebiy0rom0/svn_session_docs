# 3. 図で理解する バージョン管理

## プロジェクトの説明

**シチュエーション**
ボブとアリスはとあるプロジェクトを立ち上げることにしました。

**登場人物**
- ボブ (Leader)
- アリス (Member)

**運用ルール**
- 開発は branch を作成して行う
    - リリース時期が異なる開発については、別 branch を作成して並行開発を行う
- branch -> trunk のマージ後は、軽微な修正であれば trunk 内で行う(hotfix branch 等の発行はしない)
- branch の発行・各 trunk - branch 間のマージは、リーダーであるボブが行う
- 開発用 branch のマージ後に不具合等が検知されなければ、tag を作成しリリースを行う

---
#### <div style="text-align:left; float:right;">[各項 解説① NEXT>](./page9.md)</div>[<PREV 各用語 図解](./page7.md)