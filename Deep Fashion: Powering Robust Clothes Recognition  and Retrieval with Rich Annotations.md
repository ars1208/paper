# Deep Fashion: Powering Robust Clothes Recognition  and Retrieval with Rich Annotations  
## ポイント  
1. どんな論文か？  
   DeepFashion(巨大なfashion dataset)の提供．また，データセットの強みを確認するためのFashionNetの作成．
2. 先行研究と比べてどこがすごいか？
   既存のデータセットと比較すると，画像枚数・カテゴリ数・属性数が多い．
3. 技術や手法の要点は？
   データセットの総合性，規模，利便性の高さ．  
   カテゴリ分けや属性分類，ベンチマークの網羅性．
4. 検証方法は？
   VGG-16ベースのFashionNetを作成し，以下のモデルと比較した．
   * WTBI(Where To Buy It)
   * DARN(Dual Attribute-aware Ranking Network)
   * FashionNet+100
   * FashionNet+500
   * FasihonNet+Joints
   * FashionNet+Poselets
5. 議論はあるか？
   個人的な話だが，datasetの再現性は高いが，日本人ベースでないため研究に利用しにくい．
6. 次に読むべき論文は？  
   Deep domain adaptation for describing people based on fine-grained clothing attributes.
## 読み順  
アブスト→結論→実験結果→提案手法→イントロ→関連研究
