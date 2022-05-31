#bilibili
	1	先在浏览器登录 (先登录! 先登录! 先登录!)
	2	先把*.bilibili.com加到[MITM]
	3	再配置重写规则:
	◦	Surge: 把两条远程脚本放到[Script]
	◦	QuanX: 把bilibili.cookie.js和bilibili.js传到On My iPhone - Quantumult X - Scripts (传到 iCloud 相同目录也可, 注意要打开 quanx 的 iCloud 开关)
	4	打开浏览器访问: https://www.bilibili.com 或 https://live.bilibili.com
	5	系统提示: 获取Cookie: 成功
	6	最后就可以把第 1 条脚本注释掉了
第 1 条脚本是用来获取 cookie 的, 用浏览器访问一次获取 cookie 成功后就可以删掉或注释掉了, 但请确保在登录成功后再获取 cookie.
第 2 条脚本是签到脚本, 每天00:00:10执行一次.
#中国电信
先在登录成功后, 再打开获取 Cookie 的脚本
	1	先配置[MITM]
	◦	Surge: wapside.189.cn:9001
	◦	QuanX: wapside.189.cn
	2	再配置重写规则:
	◦	Surge: 把两条远程脚本放到[Script]
	◦	QuanX: 把10000.cookie.js和10000.js传到On My iPhone - Quantumult X - Scripts (传到 iCloud 相同目录也可, 注意要打开 quanx 的 iCloud 开关)
	3	打开 APP 手动签到一次: 访问下右下角 我 > 签到 (头像下面)
	4	系统提示: 获取Cookie: 成功
	5	最后就可以把第 1 条脚本注释掉了
第 1 条脚本是用来获取 cookie 的, 用浏览器访问一次获取 cookie 成功后就可以删掉或注释掉了, 但请确保在登录成功后再获取 cookie.
第 2 条脚本是签到脚本, 每天00:00:10执行一次.
#海底捞
	1	先把activity-1.m.duiba.com.cn加到[MITM]
	2	再配置重写规则:
	◦	Surge: 把两条远程脚本放到[Script]
	◦	QuanX: 把hdl.js传到On My iPhone - Quantumult X - Scripts (传到 iCloud 相同目录也可, 注意要打开 quanx 的 iCloud 开关)
	3	打开 APP海底捞 然后手动签到 1 次, 系统提示: 获取Cookie: 成功
	4	最后就可以把第 1 条脚本注释掉了
	5	运行一次脚本, 如果提示重复签到, 那就算成功了!
第 1 条脚本是用来获取 cookie 的, 用浏览器访问一次获取 cookie 成功后就可以删掉或注释掉了, 但请确保在登录成功后再获取 cookie.
第 2 条脚本是签到脚本, 每天00:00:10执行一次.
#IT之家
获取方式:app进入签到页面获取

#美团
	1	先把i.meituan.com加到[MITM]
	2	再配置重写规则:
	◦	Surge: 把两条远程脚本放到[Script]
	◦	QuanX: 把meituan.cookie.js和meituan.js传到On My iPhone - Quantumult X - Scripts (传到 iCloud 相同目录也可, 注意要打开 quanx 的 iCloud 开关)
	3	打开 APP , 然后手动签到 1 次, 系统提示: 获取Cookie: 成功 (首页 > 红包签到)
	4	把获取 Cookie 的脚本注释掉
	5	运行一次脚本, 如果提示重复签到, 那就算成功了!
第 1 条脚本是用来获取 cookie 的, 用浏览器访问一次获取 cookie 成功后就可以删掉或注释掉了, 但请确保在登录成功后再获取 cookie.
第 2 条脚本是签到脚本, 每天00:00:10执行一次.
#芒果TV
	1	先把credits.bz.mgtv.com加到[MITM]
	2	再配置重写规则:
	◦	Surge: 把两条远程脚本放到[Script]
	◦	QuanX: 把mgtv.cookie.js和mgtv.js传到On My iPhone - Quantumult X - Scripts (传到 iCloud 相同目录也可, 注意要打开 quanx 的 iCloud 开关)
	3	打开 APP 然后手动签到 1 次, 系统提示: 获取Cookie: 成功
	4	最后就可以把第 1 条脚本注释掉了
	5	运行一次脚本, 如果提示重复签到, 那就算成功了!
第 1 条脚本是用来获取 cookie 的, 用浏览器访问一次获取 cookie 成功后就可以删掉或注释掉了, 但请确保在登录成功后再获取 cookie.
第 2 条脚本是签到脚本, 每天00:00:10执行一次.
#网易云音乐
	1	先登录: https://music.163.com/m/login
	2	再访问: https://music.163.com/#/user/level
	3	提示: 获取会话: 成功!
第 1 条脚本是用来获取 cookie 的, 用浏览器访问一次获取 cookie 成功后就可以删掉或注释掉了, 但请确保在登录成功后再获取 cookie.
第 2 条脚本是签到脚本, 每天00:00:10执行一次.
#百果园
 * 百果园 - 小程序

 *

 * > 进入小程序直接签到
#7猫
	1	先把xiaoshuo.qm989.com加到[MITM]
	2	再配置重写规则:
	◦	Surge: 把两条远程脚本放到[Script]
	◦	QuanX: 把qmnovel.js传到On My iPhone - Quantumult X - Scripts (传到 iCloud 相同目录也可, 注意要打开 quanx 的 iCloud 开关)
	3	暂时关闭QX或Surge中的广告屏蔽, 否则无法获取小视频奖励cookie和url
	4	打开 APP七猫小说 然后到APP内福利界面手动日常签到(观看小视频领取奖励),新手领福利签到,视频签到以及幸运大转盘 1 次, 系统提示: 首次写入xxxUrl成功🎉,首次写入xxxCookie成功🎉
	5	最后就可以把第 1 条脚本注释掉了
	6	运行一次脚本, 如果提示重复签到, 那就算成功了!
第 1 条脚本是用来获取 cookie 的, 用浏览器访问一次获取 cookie 成功后就可以删掉或注释掉了, 但请确保在登录成功后再获取 cookie.
第 2 条脚本是签到脚本, 每天00:00:10执行一次.
#顺丰
	1	配置重写
	2	APP 我的顺丰 > 任务中心 > 去签到
	3	提示 获取会话: 成功
	4	注释重写
#美团外卖
	1	先把promotion.waimai.meituan.com加到[MITM]
	2	再配置重写规则:
	◦	Surge: 把两条远程脚本放到[Script]
	◦	QuanX: 把wmmeituan.cookie.js和wmmeituan.js传到On My iPhone - Quantumult X - Scripts (传到 iCloud 相同目录也可, 注意要打开 quanx 的 iCloud 开关)
	3	打开 APP , 进入签到页面, 系统提示: 获取刷新链接: 成功
	4	然后手动签到 1 次, 系统提示: 获取Cookie: 成功
	5	把获取 Cookie 的脚本注释掉
	6	运行一次脚本, 如果提示重复签到, 那就算成功了!
第 1 条脚本是用来获取 cookie 的, 用浏览器访问一次获取 cookie 成功后就可以删掉或注释掉了, 但请确保在登录成功后再获取 cookie.
第 2 条脚本是签到脚本, 每天00:00:10执行一次.
#WPS
	1	配置[MITM]
	◦	Surge: zt.wps.cn
	◦	QuanX: 110.43.90.61, zt.wps.cn
	2	再配置重写规则:
	◦	Surge: 把两条远程脚本放到[Script]
	◦	QuanX: 把wps.cookie.js和wps.js传到On My iPhone - Quantumult X - Scripts (传到 iCloud 相同目录也可, 注意要打开 quanx 的 iCloud 开关)
	3	打开 APP , 进入签到页面, 系统提示: 获取会话: 成功 (签到) (不用手动签到)
	4	最后就可以把两条获取 Cookie 的脚本注释掉了
	5	运行一次脚本, 如果提示重复签到, 那就算成功了!
第 1 条脚本是用来获取 cookie 的, 用浏览器访问一次获取 cookie 成功后就可以删掉或注释掉了, 但请确保在登录成功后再获取 cookie.
第 2 条脚本是签到脚本, 每天00:00:10执行一次.
#智行火车票
	1	先把m.ctrip.com加到[MITM]
	2	再配置重写规则:
	◦	Surge: 把两条远程脚本放到[Script]
	◦	QuanX: 把zxhc.cookie.js和zxhc.js传到On My iPhone - Quantumult X - Scripts (传到 iCloud 相同目录也可, 注意要打开 quanx 的 iCloud 开关)
	3	打开 APP 手动签到一次: 访问下右下角 个人中心 > 签到
	4	系统提示: 获取Cookie: 成功
	5	把获取 Cookie 的脚本注释掉
	6	运行一次脚本, 如果提示重复签到, 那就算成功了!
第 1 条脚本是用来获取 cookie 的, 用浏览器访问一次获取 cookie 成功后就可以删掉或注释掉了, 但请确保在登录成功后再获取 cookie.
第 2 条脚本是签到脚本, 每天00:00:10执行一次.
