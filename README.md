# 所信表明演説コーパス

This is the corpus of Japanese Text that general policy speech of prime minister of Japan
(from 1953 to 2022)

日本の首相による所信表明演説のコーパス（期間：1953-2022）

## 作成方法

Wikipediaの「所信表明演説(参考1)」で紹介されている82件の演説を、国会会議録検索システム(参考2)で検索して作成。

参考1:
http://ja.wikipedia.org/wiki/%E6%89%80%E4%BF%A1%E8%A1%A8%E6%98%8E%E6%BC%94%E8%AA%AC

参考2:
http://kokkai.ndl.go.jp/

##注意事項

127回国会では発言者によって１回中断し、データが分かれているが、続行分を加えて１つにして作成している。
この際（もとデータでは総理発言が「(発言者あり)」という形で途切れ、別項目で行頭が「内閣総理大臣(○○君)(続)」となって再開しているが、この行頭部分は削除した。）

174回国会では発言者によって２回中断し、データが分かれているが、それぞれ続行分を加えて１つにして作成している。
（処理方法は127回国会と同様）

178回国会では発言者によって２回中断し、データが分かれているが、それぞれ続行分を加えて１つにして作成している。
（処理方法は127回国会と同様）

総理大臣の名前の字体がWikipediaと国会会議録検索システムとで違うケースがあったが、全てそのままにしている。
(例, Wiki:宮沢喜一, 議録：宮澤喜一)

## forkによる更新 by @tetlabo

元のリポジトリでは第187回国会までのデータしかなかったため、同様の方法で、第192回国会以降に行われた演説も取得し、追加した。
