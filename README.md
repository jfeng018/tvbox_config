## 已完成 android、ios、macos、windows全平台的类TVbox软件，使用flutter + nodejs 架构实现，播放器mpv；
	- 支持 TVbox格式配置的T4(type=4)、cms-json(type=1)源、旧版猫影视js源(type=3)
	- 支持 猫爪nodejs源配置
	- 支持嗅探播放，配置同TVbox(parse=1)

## 待实现功能(空闲时间看心情开发 (#^.^#))
	✅ 播放历史记录
	✅ 新增播放器切换
	✅ 音乐
	- 磁力播发
	- 整合漫画、小说功能

## 下载链接地址：<a href="https://github.com/LuckySe7ens/tvbox_config/releases">releases</a>
### t1 & t4配置 [https://d.kstore.dev/download/8943/nodejs/api.json](https://d.kstore.dev/download/8943/nodejs/api.json)
```
{
	"sites": [{
			"key": "hmr",
			"name": "黑木耳",
			"type": 4,
			"api": "http://zhangqun66.com/225.php"
		},
		{
			"key": "wwdj",
			"name": "旺旺短剧",
			"type": 1,
			"api": "http://zhangqun1818.serv00.net:5052"
		}, {
			"key": "maotai",
			"name": "茅台(json)",
			"type": 1,
			"api": "https://caiji.maotaizy.cc/api.php/provide/vod/from/mtm3u8/at/josn/"
		}, {
			"key": "电影天堂",
			"name": "电影天堂",
			"type": 1,
			"api": "http://caiji.dyttzyapi.com/api.php/provide/vod",
			"ext": {
				"categories": ["国产剧", "爱情片", "喜剧片"]
			}
		}, {
			"key": "天涯采集",
			"name": "天涯采集",
			"type": 1,
			"api": "http://tyyszy.com/api.php/provide/vod"
		}
	]
}
```

### nodejs配置地址：
[https://14256.kstore.space/index.js.md5](https://14256.kstore.space/index.js.md5)

## 相关截图

<img src="img/config.png" height="520px"><img src="img/main.png" height="520px"><img src="img/search.png" height="520px">
<img src="img/push.png" height="520px"><img src="img/play.png" height="520px">
