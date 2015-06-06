### 実際のコード

https://github.com/ayemos/ayemos-sezemi-2015-readable-code/blob/master/src/recipe/RecipeLoader.java

```java

    private static Set<RecipeModel> loadRecipesFromLocalXML(String path)

```

### どうしてリーダブルだと思っているかの説明

メソッド名だけで、XMLからレシピ情報を読み出していることを明示している。
もしXMLがないメソッド名だと、データソースが追加された場合、既存のメソッドに手を入れる選択肢しかなくなるが、
データソースが追加・変更になった場合に、別のメソッドとして実装すべきことを暗黙的に定義している点が素晴らしい。

### この書き方の一言説明

データソース明示型命名


### 実際のコード
### どうしてリーダブルだと思っているかの説明
### この書き方の一言説明
