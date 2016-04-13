# [Assignment 1] Data Coolection and Persistence

## Data Format

#### JSON

##### Object
+ created_at : twitter發文時間
+ id         : 文章ID
+ id_str     : 
+ text       : 文章內容
+ source:資料來源
+ truncated:
+ in_reply_to_status_id:此Tweet資料是否為答覆，是，則顯示原始Tweet’s ID
+ in_reply_to_status_id_str:此Tweet資料是否為答覆，是，則顯示原始Tweet’s ID(字串格式)
+ in_reply_to_user_id:此Tweet資料是否為答覆，是，則顯示原始Tweet’s作者的ID
+ in_reply_to_user_id_str:此Tweet資料是否為答覆，是，則顯示原始Tweet’s作者的ID(字串格式)
+ in_reply_to_screen_name:此Tweet資料是否為答覆，是，則顯示原始Tweet’s作者的screen name

######user
+ geo:地理標記
+ coordinates:座標
+ place:地點
+ contributors:contributor mode

######retweeted_status
+ is_quote_status
+ retweet_count
+ favorite_count

######entities
######extended_entities
+ favorited
+ retweeted
+ possibly_sensitive
+ filter_level
+ lang:語言
+ timestamp_ms
+ @version
+ @timestamp




## Data Sources

* API Resource: Elasticsearch-Learn
* Topic: NBA美國職籃消息
* Search Key Words: nba



