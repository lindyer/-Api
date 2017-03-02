# 一席 #

- [首页](#home)
	- [首页演讲](#home_lecture)
		- [演讲细节](#home_lecture_detail)
		- [演讲评论](#home_lecture_comments)
		- [演讲相关](#home_lecture_related)

<h2 id="home">首页</h2>

url：[`http://api.yixi.tv/api/v1/album`](http://api.yixi.tv/api/v1/album)

json 示例：

	{
      "res": 0,
      "data": [
        {
          "id": 179,
          "title": "张素玢「浊水溪三百年」",
          "desc": "“人定胜天”不是夸奖，相反地，我一直怀疑这句话",
          "webcontent": "<p>这是我一辈子都没看过的，所以当我看到这个景象的时候，我就觉得历史学者不能只待在书房了，我们应该用自己的方式来关心社会、关心我们的环境。<br/></p><p>我们过去所说的好山好水，现在放眼望去只剩下残山剩水。对于这一条浊水溪，母亲之河，它最大的悲哀是出口不是大海，而是石化工业的<span>498根烟囱。我想这也是我今天会在这里的原因，也是我为什么会花了十年写这一本《浊水溪三百年》的原因。</span></p><p></p><p>所有的河川、所有的森林，我都当成自己的母亲。我也希望所有的人在高速公路奔驰，在恣意地享用这些水资源的时候，想一想我们每一条河流到底遭遇了什么样的悲惨的境遇。</p><p></p><p></p>",
          "background": "http://static.yixi.tv/background/2017-02-28/a63d2a96986353ed9789f284431ad402.1536x1000.jpg",
          "purecontent": "这是我一辈子都没看过的，所以当我看到这个景象的时候，我就觉得历史学者不能只待在书房了，我们应该用自己的方式来关心社会、关心我们的环境。\r\n\r\n我们过去所说的好山好水，现在放眼望去只剩下残山剩水。对于这一条浊水溪，母亲之河，它最大的悲哀是出口不是大海，而是石化工业的498根烟囱。我想这也是我今天会在这里的原因，也是我为什么会花了十年写这一本《浊水溪三百年》的原因。\r\n\r\n所有的河川、所有的森林，我都当成自己的母亲。我也希望所有的人在高速公路奔驰，在恣意地享用这些水资源的时候，想一想我们每一条河流到底遭遇了什么样的悲惨的境遇。",
          "newpc": "这是我一辈子都没看过的，所以当我看到这个景象的时候，我就觉得历史学者不能只待在书房了，我们应该用自己的方式来关心社会、关心我们的环境。\r\n\r\n我们过去所说的好山好水，现在放眼望去只剩下残山剩水。对于这一条浊水溪，母亲之河，它最大的悲哀是出口不是大海，而是石化工业的498根烟囱。我想这也是我今天会在这里的原因，也是我为什么会花了十年写这一本《浊水溪三百年》的原因。\r\n\r\n所有的河川、所有的森林，我都当成自己的母亲。我也希望所有的人在高速公路奔驰，在恣意地享用这些水资源的时候，想一想我们每一条河流到底遭遇了什么样的悲惨的境遇。\r\n[lecid:416]",
          "published": 1,
          "sort": 179,
          "created_at": "2017-02-28 13:13",
          "lectures": [
            {
              "id": 416,
              "title": "浊水溪三百年",
              "desc": "浊水溪是台湾最长的河流，台湾历史学者张素玢，花费近20年进行田野调查与文献研究，写成《浊水溪三百年》，探讨人如何与环境相处、工业与农业怎样互动。",
              "lecturer_id": 115430,
              "viewnum": "960",
              "likenum": "3",
              "cmtnum": "2",
              "cover": "http://static.yixi.tv/background/2017-02-28/b5cb146ddf2091609816ec17310c64fa.640x360.jpg",
              "background": "http://static.yixi.tv/background/2017-02-28/53c4ee05ec05488980117731352ee768.1536x600.jpg",
              "video": "XMTg1MTYyOTk1Mg==",
              "cate_id": 5,
              "type": "lec",
              "published": 1,
              "site": "长沙",
              "time": "2016-09-17",
              "created_at": "2017-02-28 13:05:06",
              "lecturer": {
                "id": 115430,
                "nickname": "张素玢",
                "desc": "台湾历史学者",
                "pic": "http://static.yixi.tv/portrait/2017-02-28/46fa17bd5c0af9b6c3969fd404d3a616.160x160.jpg",
                "background": "http://static.yixi.tv/background/2017-02-28/d6bc01b99b55bdbaeac05327789feeef.995x500.jpg",
                "is_lecturer": 1,
                "cate_id": 5
              },
              "category": {
                "id": 5,
                "name": "观察",
                "sort": 2
              },
              "tags": [
                {
                  "id": 34,
                  "name": "历史"
                },
                {
                  "id": 315,
                  "name": "人文"
                },
                {
                  "id": 708,
                  "name": "观察"
                },
                {
                  "id": 742,
                  "name": "出版"
                },
                {
                  "id": 743,
                  "name": "研究"
                }
              ]
            }
          ]
        }
      ]
    }

解析：

- `res`：请求成功时为 `0`
- `data`
	- `id`：
	- `title`：标题
	- `desc`：简述
	- `webcontent`：web 内容
	- `purecontent`：内容
	- `newpc`：
	- `background`：背景图
	- `created_at`：创建时间
	- `lectures`：演讲信息
		- `id`：查看[演讲详细信息](#home_lecture)使用
		- `title`：演讲标题
		- `desc`：演讲简述
		- `lecturer_id`：
		- `viewnum`：多少人已经看过
		- `likenum`：喜欢数量
		- `background`：背景图
		- `cmtnum`：评论数量
		- `site`：演讲地点
		- `time`：演讲时间
		- `lecturer`：作者信息
			- `id`：作者 id
			- `nickname`：演讲者
			- `desc`：演讲者身份
			- `pic`：演讲者照片
		- `category`：演讲分类
			- `name`：分类
		- `tags`：演讲归类
			- `name`：归类

<h3 id="home_lecture">首页演讲</h3>

<h4 id="home_lecture_detail">演讲细节</h4>

url：http://api.yixi.tv/api/v1/lecture/detail/ + [首页](#home) 获取的 `lectures` 字段中的 `id` 字段

url示例：[`http://api.yixi.tv/api/v1/lecture/detail/416`](http://api.yixi.tv/api/v1/lecture/detail/416)

json 示例：

	{
      "res": 0,
      "data": {
        "id": 416,
        "title": "浊水溪三百年",
        "desc": "浊水溪是台湾最长的河流，台湾历史学者张素玢，花费近20年进行田野调查与文献研究，写成《浊水溪三百年》，探讨人如何与环境相处、工业与农业怎样互动。",
        "lecturer_id": 115430,
        "viewnum": "963",
        "likenum": "3",
        "cmtnum": "2",
        "purecontent": "大家好，我叫张素玢，是一个历史研究者，任教于台湾师范大学台湾省研究所。今天一席给我这三十分钟的时间，我希望带给大家浊水溪这条河流三百年的故事。\r\n\r\n本来我是一个传统的历史研究者，在自己的书斋看着过去的文献。但是我一直认为，历史真正的责任必须是要关怀现在的社会，而不是把自己的研究束诸高阁。\r\n\r\n2001年，台湾最大的一个集集拦河堰完成了，那上面写着四个字：人定胜天，在我看起来是格外的触目惊心。当时我就想，给我十年，我要自己用笔来写下这条浊水溪的变化。\r\n\r\n到了2005年，其实还不到十年，浊水溪的北岸有一个大型的石化工业区就蠢蠢欲动了。在它的南岸，本来已经有一个非常大型的石化工业，所有的问题已经一目了然，居然北岸还要建一个更大型的。\r\n\r\n当时我已经相当焦虑了，因此我的写作慢慢地跟现实靠拢，我觉得我要用历史的深度跟长度，把这样子一个环境破坏跟转变写在史书上。在2014年的时候，终于结集了这本书《浊水溪三百年》。其实我心里知道，我的焦虑应该是台湾群众普遍的焦虑，这个环境的问题已经让我们没办法逃离于天地之间。\r\n\r\n浊水溪到底是一条怎样的河流呢？它在台湾的中部，一向是台湾的界河。每到选举的时候，蓝绿双方就会喊出“决战浊水溪”。如果蓝的攻到南边去，他就赢了；绿的往北攻上去，那绿的也赢了，屡试不鲜。人们也常说，如果它有一天变清了，通常是预兆着大事情要发生了。所以说这条河流，它既有征兆又有政治上的一个意涵。\r\n\r\n可是对一般民众来讲，这条河有很丰富的有机质，所以它可以孕育出非常肥沃的土地。事实上，从这块土地里输送物产到大陆沿海省份，从清代就开始了。也因此，鹿港这个条件不太好的港口居然成为跟泉州对渡的一个正式的港口，把浊水溪的米运到大陆的沿海来。\r\n\r\n尽管我说它是台湾最长的河流，可浊水溪全长才186.6千米。湖南省东西横跨230千米，这个长度连我们一个省都无法贯穿。可是这么短的一条河流，却可以集全世界许多河川的灾难于一身。你只要研究浊水溪，大概整个长江从中游到下游的事情，都会在这么短的186.6千米中发生。\r\n\r\n浊水溪的发源地是在海拔3220千米的合欢山，这里的风景非常的漂亮。最高点的武岭有一间小小的厕所，厕所下面就是它的源头。有一天你如果去那里奉献一些些的水，它就迅速奔流下山，当你还在山上徘徊的时候，可能你贡献的这些水就快到台湾海峡了。台湾这种从高山到平原游速这么快的河流，跟大陆长江大河浩浩荡荡、连绵好几月日才到大海的情况是很不一样的。\r\n\r\n我们看到的长江的颜色是有点碧绿有点蓝的，可是浊水溪即使不用黑白，它就是这样灰灰黑黑的，带着非常多的土膏、沙石。\r\n\r\n有一篇文献统计了全世界发源于海拔3000千米的高山，输沙量最高的前二十条河流，浊水溪排名全世界第一，黄河排名十四。这样子排名第一当然不是好事。更可怕的是，十条世界输沙量最高的河川，台湾就占了八条之多。\r\n\r\n因为浊水溪的宽度相当大，我们常常看到有一些河川的工事在这里进行。这张照片其实时间并不久，是在1970年代。可是他们什么都没穿，因为河水太浊了，如果他们穿着自己的汗衫下去很难洗得干净，没洗几次大概也毁了。\r\n\r\n你也许会问我，为什么从刚刚到现在你说了那么多遍浊，因为后来我们可以看到，它是影响环境的非常重要的一个因素。\r\n\r\n浊水溪从上游开始，河流就下切得非常深。中间这个位置有一个人。\r\n\r\n它的岩石也很脆弱，并不是花岗岩。台湾前几年发生了“八八风灾”，淹没了好几个山地村落。事实上这个情形在历史上老早就出现了，所以它本身的水文就是这个样子。\r\n\r\n1895年日本开始统治台湾，他们认为应该好好整治这一条台湾最大的溪流，就开始把漫而无际的网状水系用堤防收束起来，让它集中在主流，南北两岸就产生了从清中叶以来台湾最大面积的浮腹地。\r\n\r\n可是在这个这么大的堤防工程完成以后，隔年、再隔几年还是发生非常严重的水灾，所以有识之士就说治水必先治山，山林、森林是河川之母，日本人就开始对这条河流一条边地来整治。\r\n\r\n在靠近海岸的地方，他们种了一道一道的防风林，枯了再种、种了又枯。就这样的四十余年，真的把海岸地区给屏障起来了。接着是加强稳固原来的堤防，然后再收束住从出山口到出海口的堤防。靠近山坡地的地方，也做好山坡地的保安林，防止土石的崩坡。上游的地方积极造林，然后进行防沙的工程。于是我们看这一条河流就这样子治山治水一条边地完成了。\r\n\r\n整治好浊水溪当然花了非常多的经费。殖民政府当然有它的打算，因为台湾要从农业慢慢地转型到工业了。电是工业之母，浊水溪的水源又非常丰沛，日本就打算在日月潭往上差不多半个钟头的地方建设好几个水电站。这些红色的都是拦沙坝、水坝。\r\n\r\n我刚刚说沙多是它的本性，因此这些水坝的宿命是没出几年就变成沙坝。假设我们把河川想成人的血脉奔流，这些拦了一大堆沙的水坝，其实就像我们的血管阻塞。所以整个河流常常出现堵塞，只要有水坝的地方，那里的河流生态就为之改变。\r\n\r\n今天大家到雾社，那也是一个很漂亮的风景区，整个水库我们看到的水不多，大部分都是沙。\r\n\r\n我就问水利单位为什么你们不清这些沙，结果他说你知道我们要把这些沙清除了要花多少趟卡车吗？要八十八万趟十吨重的卡车——沙没运完，道路都完了。所以它就变成盖一个淤一个、盖一个淤一个，可还是不断地盖。\r\n\r\n其实台湾在一九二零三零年代盖的水坝的一个结果，已经呈现在眼前了，但是如果以密度来讲，1930年代台湾水坝的密度比现在怒江跟金沙江盖的还要多。所以我们可以看到，到底浊水溪的资源怎么被剥削利用了。\r\n\r\n这是上游和中游，我们再来看一下下游。\r\n\r\n1960年代台湾引进了抽水马达，可以把地下的水层抽到农地，又迅速又省钱，而且浊水溪的地下水层很浅又很饱满，结果这些井就一根一根地像吸管一样吸到地下水层。后来散布在田间的很多的小型工厂也一样，为了逃避环保单位的稽查，它也可以把废水这样灌进去，顺着地下水层到处漫延。\r\n\r\n从1960年代到现在，抽了60年，我们看到北岸的彰化已经地层下陷到可以把一个人淹没了，南岸也到腰部以上了。\r\n\r\n本来这样子的一个问题，除了浊水溪两岸的人承受痛苦以外，住在台北的是不太管这些事情的。可是高速铁路完成了，从台北一直到高雄，两个半钟头就到了，但是一碰到中部的地层下陷的路段的时候，高达两三百公里的高速铁路就会像云霄飞车一样飞出去。所以全台湾的人都开始关注这个问题。但是这样地下水的超抽，它有时候是不可逆的，不是补注地下水就有办法把它挽救回来。\r\n\r\n除了水，这个地方的沙可是建筑业的最爱。台湾在一九七零八零年代经济发展的时候，房子、建筑业也跟着发展，很多人都指定要浊水溪的沙。可是它一本万利，所以就有很多的黑道都进来了，用非法掩盖合法。\r\n\r\n因为无度的开采，全世界输沙量最高的溪流，它下游的浊水溪大桥的桥墩居然像八爪章鱼全部都裸露。\r\n\r\n这样的照片一披露，大家都紧张了。警察就固守在旁边，可是道高一尺，魔高一丈，我们看到这些盗采沙石的车子就往中上游移动。\r\n\r\n我今天要到金字塔来的时候，看到湖南遍地高楼大厦，不禁赞叹整个长沙这十年的发展这么迅速。可是我心里想，这里的房子挖的是哪里的沙呀？因为你们的河流很长，挖的地方大概我们看不见，所以这么多的房子、这么高的大楼，到底会造成哪一条河流在哭泣呀？\r\n\r\n政府追求经济成长，工业的产值最能让经济的数据漂亮一点。果然在1997年，我们就看到民生、农业用水都还没有开始以前，就有一个专用的输送道送到工业区。\r\n\r\n水不够怎么办？农业休耕。所以我们看到了它一边拦住了非常丰沛的水，弹指之间，按照人的意志送到它认为该输送的地方；另外一边则是河床都裸露了。\r\n\r\n这是我一辈子都没看过的，所以当我看到这个景象的时候，我就觉得历史学者不能只待在书房了，我们应该用自己的方式来关心社会、关心我们的环境。\r\n\r\n台湾有一个最大的问题是到底是要农业还是要工业？大家都想要并行。浊水溪南岸、北岸是最好最精华的农业区，却即将要盖南北各一的超大型的石化工业，要用人民币1000个亿去建设它。\r\n\r\n这时候我们就看到，石化工业所在的云林县，2004年以后每年稳居癌症死亡率的最高位。所以又要有一个更可怕的石化工业出现的时候，大家就都站出来了，连最静默的高中生也都站出来了。\r\n\r\n我们过去所说的好山好水，现在放眼望去只剩下残山剩水。对于这一条浊水溪，母亲之河，它最大的悲哀是出口不是大海，而是石化工业的498根烟囱。我想这也是我今天会在这里的原因，也是我为什么会花了十年写这一本《浊水溪三百年》的原因。\r\n\r\n所有的河川、所有的森林，我都当成自己的母亲。我也希望所有的人在高速公路奔驰，在恣意地享用这些水资源的时候，想一想我们每一条河流到底遭遇了什么样的悲惨的境遇。\r\n\r\n好，我就讲到这里。谢谢。",
        "entitle": "",
        "ennickname": "",
        "enpurecontent": "",
        "cover": "http://static.yixi.tv/background/2017-02-28/b5cb146ddf2091609816ec17310c64fa.800x450.jpg",
        "background": "http://static.yixi.tv/background/2017-02-28/53c4ee05ec05488980117731352ee768.1536x600.jpg",
        "video": "XMTg1MTYyOTk1Mg==",
        "cate_id": 5,
        "type": "lec",
        "published": 1,
        "site": "长沙",
        "time": "2016-09-17",
        "created_at": "2017-02-28 13:05:06",
        "lecturer": {
          "id": 115430,
          "nickname": "张素玢",
          "desc": "台湾历史学者",
          "pic": "http://static.yixi.tv/portrait/2017-02-28/46fa17bd5c0af9b6c3969fd404d3a616.160x160.jpg",
          "background": "http://static.yixi.tv/background/2017-02-28/d6bc01b99b55bdbaeac05327789feeef.1536x600.jpg",
          "is_lecturer": 1,
          "cate_id": 5
        },
        "category": {
          "id": 5,
          "name": "观察",
          "sort": 2
        },
        "tags": [
          {
            "id": 34,
            "name": "历史"
          },
          {
            "id": 315,
            "name": "人文"
          },
          {
            "id": 708,
            "name": "观察"
          },
          {
            "id": 742,
            "name": "出版"
          },
          {
            "id": 743,
            "name": "研究"
          }
        ],
        "liked": 0,
        "bookmarked": 0
      }
    }

json 解析：

- `cover`：演讲图
- `background`：背景图
- `purecontent`：演讲内容

<h4 id="home_lecture_comments">演讲评论</h4>

url：[`http://api.yixi.tv/api/v1/lecture/comments/416/page/1`](http://api.yixi.tv/api/v1/lecture/comments/416/page/1)

json 示例：

	{
      "res": 0,
      "data": [
        {
          "id": 4799,
          "user_id": 115732,
          "to_id": 0,
          "content": "方向是环保，非常值得肯定。但是看这篇演讲真的很想打断她，随口的中国，台湾总统，不说台湾腔的事情，这些称谓从一个台湾学者口中说出不知道大家什么感受，反正我是打心底排斥她。",
          "lecture_id": 416,
          "created_at": "2017-03-01 20:50:50",
          "updated_at": "2017-03-01 20:50:50",
          "user": {
            "id": 115732,
            "nickname": "oooo0oooo0@vip.qq.com",
            "pic": "",
            "is_lecturer": 0
          },
          "touser": null,
          "lecture": {
            "id": 416,
            "title": "浊水溪三百年",
            "type": "lec"
          }
        },
        {
          "id": 4791,
          "user_id": 113153,
          "to_id": 0,
          "content": "人定胜天，残山残水，真的好悲哀！",
          "lecture_id": 416,
          "created_at": "2017-02-28 19:54:09",
          "updated_at": "2017-02-28 19:54:09",
          "user": {
            "id": 113153,
            "nickname": "一年级",
            "pic": "http://static.yixi.tv/portrait/2017-02-13/cea906a5d2a19946fb308f4e6355000a.160x160.jpg",
            "is_lecturer": 0
          },
          "touser": null,
          "lecture": {
            "id": 416,
            "title": "浊水溪三百年",
            "type": "lec"
          }
        }
      ]
    }

json 解析：

- `user_id`：用户 id
- `content`：用户评论内容
- `created_at`：发表时间
- `user`：用户信息
- `lecture`：演讲信息

<h4 id="home_lecture_related">演讲相关</h4>

url：[`http://api.yixi.tv/api/v1/lecture/416/related`](http://api.yixi.tv/api/v1/lecture/416/related)

json 示例：

	{
      "res": 0,
      "data": [
        {
          "id": 412,
          "title": "邻居",
          "lecturer_id": 109336,
          "viewnum": "5906",
          "likenum": "40",
          "cmtnum": "10",
          "cover": "http://static.yixi.tv/background/2017-01-06/f3f191047c6a7f5f2272c9b4aaf7bb2a.210x140.jpg",
          "background": "http://static.yixi.tv/background/2017-01-06/708e3ffa84da9e3f3889c8c8da8d96d6.1536x600.jpg",
          "video": "XMTg2MTAwNjIxNg==",
          "cate_id": 5,
          "type": "lec",
          "published": 1,
          "site": "上海",
          "time": "2016-08-21",
          "created_at": "2017-01-06 12:03:31",
          "lecturer": {
            "id": 109336,
            "nickname": "Rob Schmitz",
            "pic": "http://static.yixi.tv/portrait/2017-01-06/c2a50594245ad4c35f7906f6229787e7.160x160.jpg",
            "is_lecturer": 1,
            "cate_id": 5
          },
          "tags": [
            {
              "id": 96,
              "name": "文化"
            },
            {
              "id": 326,
              "name": "社会"
            },
            {
              "id": 708,
              "name": "观察"
            },
            {
              "id": 733,
              "name": "邻里"
            },
            {
              "id": 734,
              "name": "公共"
            }
          ]
        }
      ]
    }

- `title`：相关演讲标题
- `lecturer_id`：相关演讲 id
// 其他内容等同[首页](#home)中的 json
- ``：
- ``：
- ``：
- ``：
- ``：
- ``：
- ``：
- ``：
- ``：
- ``：
- ``：
- ``：
- ``：
- ``：