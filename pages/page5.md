# 2. バージョン管理システム

## 押さえておきたい用語 その2

**リビジョン**
- バージョンのこと
- 1から始まり、コミットの度に加算される
- trunk, branchで共通のリビジョンが使用される

**コミット**
- 変更内容をリポジトリに反映すること
- 同時にコメントを残すことができる
- コンフリクトが発生した場合、コミットは行えない

**マージ**
- 複数リビジョンの同一ファイルの変更内容を統合すること
- **マージはまず作業コピー内で行われる**
    - **全てのコンフリクトを解消しコミットすることでリポジトリに反映される**

**競合・衝突(コンフリクト)**
- マージやコミットをする際に、自身の変更したファイル(マージ時は所有しているファイル)  
のリビジョンが最新でなかった場合に発生する事象
- コンフリクトが発生した場合は、手動で正しい状態に修正する必要がある
    - テキストデータかつ変更箇所が重複していなければ、自動でマージしてくれることもある

---
#### <div style="text-align:left; float:right;">[押さえておきたい用語 その3 NEXT>](./page6.md)</div>[<PREV 押さえておきたい用語 その1](./page4.md)