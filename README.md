# jd
有些库更新了,做个保存,做个搬运工
可能是最全的一个库
修改青龙 config.sh 文件中的GithubProxyUrl参数为： https://pd.zwc365.com/ 或 https://pd.zwc365.com/cfworker/

然后拉库命令填写下方代码：
```
ql repo https://github.com/KingRan/JDJB.git "jd_|jx_|jdCookie" "activity|backUp" "^jd[^_]|USER|utils|function|sign|sendNotify|ql|JDJR"
```
同时：
```
1.出现这种错误：

Cannot find module 'xxxx'

依赖不完整，解决方法：

docker exec -it qinglong(容器名称) bash

cd /ql/scripts/

pnpm install 'xxxx'

npm install 'xxxx'

这两个安装命令都可以用

2.出现这种错误：

Cannot find module './xxxx'

那就很有是拉库命令不完整，请检查或复制完整的拉库命令。

部分需要的依赖：自行安装

"npm install -g npm"

"pip3 install requests"

"pip3 install pytz"

"npm install -g download"

"pnpm install jsdom"

"apk add --no-cache build-base g++ cairo-dev pango-dev giflib-dev && cd scripts && npm install canvas png-js md5 date-fns axios crypto-js tslib ts-md5 @types/node --build-from-source"
```

首先是shufflewzc库
【青龙拉库命令】 
```
ql repo https://github.com.cnpmjs.org/shufflewzc/faker2.git "jd_|jx_|gua_|jddj_|getJDCookie" "activity|backUp" "^jd[^_]|USER|function|utils|sendNotify|ZooFaker_Necklace.js|JDJRValidator_|sign_graphics_validate|ql|JDSignValidator"
```
然后是he1pu库
```
ql repo https://github.com/he1pu/JDHelp.git "jd_|jx_|getJDCookie" "activity|backUp|jd_delCoupon" "^jd[^_]|USER|utils|sendNotify|ZooFaker_Necklace.js|JDJRValidator_|sign_graphics_validate"
```
同时要进入容器进行依赖更新
```
npm install -g png-js
npm install -g jsdom
```
然后是Aaron-lv
```
ql repo https://github.com/Aaron-lv/sync.git "jd_|jx_|getJDCookie" "activity|backUp|Coupon" "^jd[^_]|USER|utils" "jd_scripts"
```

JDHelloWorld
```
ql repo https://github.com/JDHelloWorld/jd_scripts.git "jd_|jx_|getJDCookie" "activity|backUp|Coupon|enen|update|test" "^jd[^_]|USER|^TS|utils|notify|env|package|ken.js"
```

passerby-b
```
ql repo https://github.com/passerby-b/JDDJ.git "jddj_" "scf_test_event|jddj_fruit_code.js|jddj_getck.js|jd_|jddj_cookie"
```

curtinlv
```
ql repo https://github.com/curtinlv/JD-Script.git "jd_"
```

smiek2221
```
ql repo https://github.com/smiek2121/scripts.git "jd_|gua_" "" "^MovementFaker|^JDJRValidator|^ZooFaker|^sign|^cleancart" 
```

Ariszy (Zhiyi-N)
```
ql repo https://github.com/Ariszy/Private-Script.git "JD"
```

jiulan
```
ql repo https://github.com/jiulan/platypus.git "jd_|jx_" "" "overdue" "main"
```

Tsukasa007,这个库有后续操作，感兴趣可以搞
```
ql repo https://github.com/Tsukasa007/my_script.git "" "jdCookie|USER_AGENTS|sendNotify|backup" "" "master"
```
京东多合一签到
```
ql repo https://github.com/NobyDa/Script.git "JD-DailyBonus" "" "JD_DailyBonus" "master"
```

