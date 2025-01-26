## 本データセットの概要
- 本データセットは，決算短信に出現する文の間でアラインメントをする2つのタスクのためのものです．
- 1つ目のタスクは，見通し文どうしのアラインメント，2つ目のタスクは，見通し文と結果文をアラインメントするタスクです．
- 私が電子情報通信学会　NLC研究会21回 テキストアナリティクス・シンポジウムで発表した以下の論文，および修論で用いたデータセットです．
```
決算短信における業績予測文のブートストラップを用いた抽出と極性付与
```

## データセットの概要
- 本データセットは，決算短信から文を抽出して作成しています．
- 各データセットは企業ごとの文の集合から構成されます．
- 文は文id, 見通し文フラグ，アラインメント先，文本体の4つから構成されます．
  -　文idは企業ごとの文のidであり，1-indexedです．
  -　見通し文フラグは， 0が非見通し文，1が予測文，2が事業計画文です．
  -　アラインメント先は，アラインメントすべき文の文idです．
