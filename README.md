##VSiteParser##

###This is a Chines native video website URL parser.###

With it,you can parse a video URL for some Chines native video website such as Youku,Tudou,56,etc.

**You just need to do a few like below:**

` var url = VideoParser("youku","http://v.youku.com/v_show/id_XMjc3ODU4OTMy.html"); `

**And now you can try to output the varible "url":**

` document.write(url) `

**All you will see is**

` http://player.youku.com/player.php/sid/XMjc3ODU4OTMy/v.swf `

VideoParser is a function that can return the .swf site.