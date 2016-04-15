# [Assignment 1] Data Coolection and Persistence

## Data Format

#### JSON

##### Object
+ created_at : Twitter發文時間
+ id         : 文章ID
+ id_str     : 貢獻此Tweet的使用者的ID
+ text       : 文章內容
+ source:資料來源
+ truncated:是否有被截短
+ in_reply_to_status_id:此Tweet資料是否為答覆，是，則顯示原始Tweet’s ID
+ in_reply_to_status_id_str:此Tweet資料是否為答覆，是，則顯示原始Tweet’s ID(字串格式)
+ in_reply_to_user_id:此Tweet資料是否為答覆，是，則顯示原始Tweet’s作者的ID
+ in_reply_to_user_id_str:此Tweet資料是否為答覆，是，則顯示原始Tweet’s作者的ID(字串格式)
+ in_reply_to_screen_name:此Tweet資料是否為答覆，是，則顯示原始Tweet’s作者的screen name

######user(使用者資訊)

+ geo:地理標記
+ coordinates:座標
+ place:地點
+ contributors:contributor mode

######retweeted_status(轉發狀態)

+ is_quote_status:是否被引用
+ retweet_count:此Tweet文章被轉發次數
+ favorite_count:在Twitter使用者中有多少人喜歡此Tweet文章

######entities(Entities provide metadata and additional contextual information about content posted on Twitter.)

######extended_entities(影音型態資料)

+ favorited:收藏
+ retweeted:轉發
+ possibly_sensitive:該Tweet文章是否有包含一些內容或認定為敏感內容的影音的URL
+ filter_level:過濾等級
+ lang:語言
+ timestamp_ms:該Tweet文章被創建的時間(以字串表示)
+ @version:Twitter版本
+ @timestamp:該Tweet文章被創建的時間




## Data Sources

* API Resource: Elasticsearch-Learn
* Topic: NBA美國職籃消息
* Search Key Words: nba



