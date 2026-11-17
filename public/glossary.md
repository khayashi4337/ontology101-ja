# 用語集（glossary）

この翻訳で使う訳語の一覧です。本文の訳語はこの表に合わせます。

- 「英語」の列は原文での形です。
- 「訳語」の列が、本文で使う日本語です。
- 本文では、各用語が**初めて出る箇所**で「訳語（English）」の形で英語を添えます。

例のオントロジーに出てくるクラス名・スロット名（`Wine`、`maker` など、原文で等幅字体のもの）は、名前そのものなので訳さずに英語のまま残します（原注 1 参照）。

## オントロジーの基本用語

| 英語 | 訳語 | 備考 |
|---|---|---|
| ontology | オントロジー | |
| class | クラス | 原文では concept（概念）とも呼ばれると説明される |
| concept | 概念 | |
| subclass | サブクラス | |
| superclass | スーパークラス | |
| slot | スロット | 原文では role、property とも呼ばれると説明される |
| role | ロール | |
| property | プロパティ | 原文はこの語をスロットの別名として一貫して使うので、全文で「プロパティ」と訳し、「性質」とは訳さない |
| facet | ファセット | |
| role restriction | ロール制約 | |
| instance | インスタンス | |
| individual | 個体 | individual instance は「個々のインスタンス」と訳す |
| knowledge base | 知識ベース | |
| class hierarchy | クラス階層 | |
| taxonomy | 分類体系 | taxonomic hierarchy は「分類階層」 |
| inherit | 継承する | |
| multiple inheritance | 多重継承 | |
| is-a relation | 「is-a」関係 | |
| kind-of relation | 「kind-of」関係 | 「〜の一種である」という関係 |
| transitive / transitivity | 推移的 / 推移性 | |
| direct subclass | 直接のサブクラス | |
| direct superclass | 直接のスーパークラス | |
| cycle | 循環 | |
| sibling | 兄弟（兄弟クラス） | |
| disjoint | 互いに素 | 共通のインスタンスを持てないこと |
| abstract class | 抽象クラス | |
| inverse slot | 逆スロット | |
| inverse relation | 逆関係 | |
| default value | デフォルト値 | |
| slot value | スロット値 | |
| cardinality | カーディナリティ | 値の個数の制約 |
| single cardinality | 単一カーディナリティ | |
| multiple cardinality | 複数カーディナリティ | |
| minimum cardinality | 最小カーディナリティ | |
| maximum cardinality | 最大カーディナリティ | |
| value type | 値の型 | |
| allowed class | 許容クラス | |
| allowed value | 許容値 | |
| domain (of a slot) | ドメイン | スロットの「ドメイン」。対象分野としての domain とは訳し分ける |
| range (of a slot) | レンジ | |
| domain (subject area) | ドメイン（対象分野） | 文脈上紛らわしい箇所では「対象分野」と補う |
| domain of discourse | 議論領域 | |
| domain expert | ドメインの専門家 | |
| competency question | コンピテンシー質問 | オントロジーが答えられるべき質問 |
| scope | 範囲 | |
| granularity | 粒度 | |
| terminological hierarchy | 用語階層 | |
| naming convention | 命名規則 | |
| name space | 名前空間 | |
| case-sensitive | 大文字と小文字を区別する | |
| delimiter | 区切り文字 | |
| prefix / suffix | 接頭辞 / 接尾辞 | |

## 値の型

| 英語 | 訳語 | 備考 |
|---|---|---|
| String | 文字列型（String） | |
| Number | 数値型（Number） | |
| Float / Integer | 浮動小数点型（Float） / 整数型（Integer） | |
| Boolean | ブール型（Boolean） | |
| Enumerated | 列挙型（Enumerated） | |
| Instance (value type) | インスタンス型（Instance） | |
| Symbol | シンボル型（Symbol） | Protégé-2000 での列挙型の呼び名 |

## 分野・手法の用語

| 英語 | 訳語 | 備考 |
|---|---|---|
| knowledge engineering | 知識工学 | |
| knowledge representation | 知識表現 | |
| knowledge-representation system | 知識表現システム | |
| knowledge acquisition | 知識獲得 | |
| frame | フレーム | |
| frame-based system | フレームベースのシステム | |
| description logics | 記述論理 | |
| declarative | 宣言的 | |
| problem-solving method | 問題解決手法 | |
| software agent | ソフトウェアエージェント | |
| object-oriented | オブジェクト指向 | |
| top-down | トップダウン | |
| bottom-up | ボトムアップ | |
| unary predicate | 単項述語 | |
| binary predicate | 二項述語 | |
| modeling | モデリング | |
| controlled vocabulary | 統制語彙 | |
| formalism | 形式体系 | |

## ふつうの言葉と重なる用語

次の語は、専門用語としての使い方のほかに、ふつうの言葉としても本文に何度も出てきます（例：「ワインと料理の組み合わせ」）。英語は、専門用語として初めて出る箇所（3 章ステップ 4）に手で添えています。

| 英語 | 訳語 | 備考 |
|---|---|---|
| combination (development process) | 組み合わせ（の開発プロセス） | トップダウン・ボトムアップと並ぶ、クラス階層の作り方の一つ |

## ワインと料理の用語（例題で使うもの）

この表の語は専門用語ではないので、初出で英語を添える対象にはしていません（クラス名などとして英語のまま出てくるものも多い）。

| 英語 | 訳語 | 備考 |
|---|---|---|
| winery | ワイナリー | |
| body | ボディ | ワインのこく・重さ |
| flavor | 風味 | |
| sugar / sugar content | 糖度 | |
| tannin level | タンニンの度合い | |
| vintage | ヴィンテージ | |
| grape | ブドウ | |
| varietal / variety | 品種 | |
| red wine / white wine / rosé wine | 赤ワイン / 白ワイン / ロゼワイン | |
| dessert wine | デザートワイン | |
| sparkling wine | スパークリングワイン | |
| Port | ポートワイン | |
| Bordeaux | ボルドー | |
| Burgundy | ブルゴーニュ | |
| Médoc | メドック | |
| Pauillac | ポイヤック | |
| Margaux | マルゴー | |
| Beaujolais | ボージョレ | |
| Côtes d'Or | コート・ドール | |
| Côtes Chalonnaise | コート・シャロネーズ | |
| Alsace | アルザス | |
| Zinfandel | ジンファンデル | |
| Chardonnay | シャルドネ | |
| Pinot Noir | ピノ・ノワール | |
| Merlot | メルロー | |
| Cabernet Sauvignon | カベルネ・ソーヴィニヨン | |
| Syrah | シラー | |
| Riesling | リースリング | |
| Gamay | ガメイ | |
| Napa | ナパ | |
| course (of a meal) | （料理の）コース | |
