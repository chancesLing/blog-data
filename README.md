# blog-data
这个文件是我的个人博客 keeplazy.com的几个主要页面的数据。
whisper/home.json是微语日记页面的数据
index/home.json是首页文章页面的数据
pastEvents/home.json是往事页面首页的数据
loeacots/home.json是留言板块的数据

创建这几个文件的原因是因为我的服务器比较垃圾，访问数据库的话服务器经常会卡，
所以我决定将数据库的数据先写道一个json文件中，然后用户加载html页面到本地后，
本地机器通过ajax异步访问，获取存储在github上的文件，这样的话，不用直接访问我那很垃圾的服务器，
这样就能保证用户的访问速度。

缺点：数据没法及时更新，需要我进行手动更新
