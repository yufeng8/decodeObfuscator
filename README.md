# decodeObfuscator代码
免安装一键还原Obfuscator混淆过的代码

- 本文章中所有内容仅供学习交流，不可用于任何商业用途和非法用途，否则后果自负，如有侵权，请联系作者立即删除！

# 大神视频教程地址
【【16期】加速乐（上）加密解剖--"某信息化平台"爬虫js逆向·实战教程】
```javascript
https://www.bilibili.com/video/BV1mY4y1Q7pF
```

【【16期】加速乐（下）加密解剖--"某信息化平台"爬虫js逆向·实战教程】
```javascript
https://www.bilibili.com/video/BV1n54y1T7oY
```

- 项目地址
```javascript
https://github.com/yufeng8/decodeObfuscator
```

## 一.环境安装

在nodejs官网下载最新稳定版并安装:  
![](https://files.mdnice.com/user/44292/3504ffea-a341-4dcb-b223-4453f71a836d.png)
下载地址:  
  

```javascript
https://nodejs.org/en/
```

  
安装成功后，在命令行模式输入 node，如果有版本号显示，则表示安装成功。  
  

![](https://files.mdnice.com/user/44292/0271c7c6-2d5e-4b35-9988-60a57c1fdbec.png)


## 二.下载项目

项目地址:

```javascript
https://github.com/Tsaiboss/decodeObfuscator
```

  
目录结构如下:  
  

![](https://files.mdnice.com/user/44292/f0f72686-c5a0-4cd7-96fa-19c3b3bda966.png)


- input文件夹，   存放ob混淆代码;  

- output文件夹，存放还原后的代码;  

- tools,存放打包的babel库以及部分还原的AST插件;  

- main.js   运行主文件;  

  

## 三.运行看结果

下载后解压，切换到 decodeObfuscator-main 目录，命令行模式下运行:  

```nginx
node main.js
```

  
运行时，会打印一些日志，结果文件在output文件夹，打开后是这样的:  
  

![](https://files.mdnice.com/user/44292/c31c1b7d-4d13-4d9e-ab25-dcc1010699b8.png)
  

## 四.其它混淆代码

打开 obfuscator 官网：  

```javascript
https://obfuscator.io/
```

  
如图选择 **Medium** 级别，再点击上面的 Obfuscate 按钮，生成混淆代码:
![](https://files.mdnice.com/user/44292/7c2f3418-c09c-441c-b6c4-4353c2696a9e.png)

  
我这里生成的混淆代码是这样的:  

```javascript
function _0x5c42(){var _0x1b97d7=['z0TrBgG','vMD0v3m','mJCWsKjWBu9Y','yxv1q2q','CKnbAfy','CeLvD0K','C3bSAxq','thH3Bee','BgvUz3rO','zeL3AfG','rfjAsha','Afjcrxq','BvjOB28','ve9eBxe','CMz4Dgy','zMfAu3m','vfnUAxe','y1jYA3a','vfjiwwu','s2DUtgG','y29UC29Szq','zKH4rgK','t1DsyNu','txbrt0O','x19WCM90B19F','C2vHCMnO','q0jNwNu','DvP3Cgu','v2fLywK','mtG2otm1nfzZCK9pwq','nfH4ANztDG','DxbNtfy','sLLPreG','m3WXFdb8nhW1Fa','q2vlqwm','y29UC3rYDwn0BW','CMv0DxjUicHMDq','otaWmJrtuvfuAxu','nJK3oda1wLrkyxnJ','qw5Xrgq','Aw5MBW','y3rVCIGICMv0Dq','A0vevvm','ndm5otKYAhjjAg1R','rLrfCfG','E30Uy29UC3rYDq','DgfIBgu','DhHlrwi','EMDuuuW','zxHJzxb0Aw9U','EMnhtw0','tgPpsKu','Dg9tDhjPBMC','nZmXmJu5C0P0BKHs','q3H3Bwy','CM4GDgHPCYiPka','AKz5C1e','wMjHuNG','yxbWBhK','BhHcv3K','Bg9N','kcGOlISPkYKRkq','v3Lcuui','sNPvuuO','yvvIyw0','ChjVDg90ExbL','s2XOEgq','mtKZmtG0nLrbwMPOrq','zvfPuKO','mJuZmtG3D1HyreLu','zxjYB3i','rNfRAw0','C2nJyLm','yMLUza','t29ovMe','CM9ewLG'];_0x5c42=function(){return _0x1b97d7;};return _0x5c42();}(function(_0x26e067,_0x284538){function _0x317395(_0x3c95a5,_0x24c765,_0x213473,_0x2b8a07){return _0x4b74(_0x3c95a5-0x35a,_0x2b8a07);}var _0x44b76b=_0x26e067();function _0x36c359(_0x16d2da,_0x56ddbc,_0x115efc,_0x20db00){return _0x4b74(_0x115efc- -0x13c,_0x16d2da);}while(!![]){try{var _0x3e1f6b=-parseInt(_0x317395(0x4aa,0x4b5,0x495,0x4be))/(-0x16d9+-0x161d+0x2cf7)+-parseInt(_0x317395(0x4dc,0x4e4,0x4ba,0x4f4))/(0x2d2*-0x8+-0x172d*-0x1+-0x9b)+parseInt(_0x317395(0x49a,0x47f,0x49a,0x4ba))/(-0x2537+0x1723+0xe17)+parseInt(_0x317395(0x4cf,0x4c3,0x4c8,0x4c4))/(0x1875+0xb65*-0x1+0x686*-0x2)*(parseInt(_0x317395(0x4d7,0x4ce,0x4db,0x4bc))/(-0xa7b*-0x1+0x593*0x3+-0x1*0x1b2f))+parseInt(_0x36c359(0x1c,0x40,0x38,0x2c))/(0x799*0x5+0x2380+0x1*-0x4977)+parseInt(_0x36c359(0xc,0x2f,0x12,0x2c))/(-0x1852+-0x12ec+0x2b45)+parseInt(_0x36c359(0x4c,0x3c,0x40,0x39))/(0x7*-0x1c3+0x1e0f+0x97*-0x1e)*(-parseInt(_0x317395(0x4b3,0x495,0x4b4,0x4b9))/(-0x50*-0x17+0x4f*-0x3a+0x15*0x83));if(_0x3e1f6b===_0x284538)break;else _0x44b76b['push'](_0x44b76b['shift']());}catch(_0xd0a0f1){_0x44b76b['push'](_0x44b76b['shift']());}}}(_0x5c42,-0x4b4cd+-0xf316*-0x2+0x53fef));function hi(){var _0x5b511a={'CBgZu':function(_0x304c6a,_0xbf538d){return _0x304c6a===_0xbf538d;},'Klhxd':'sFXQe','hRBEt':_0xe0fc9a(0x14f,0x15b,0x15a,0x154),'rfxtf':_0xe0fc9a(0x15c,0x154,0x147,0x177),'txKEb':_0xe0fc9a(0x14c,0x155,0x13a,0x157)+'+$','WZjpo':function(_0x1cc7f1,_0x4b8ff8){return _0x1cc7f1===_0x4b8ff8;},'CvlrR':_0x5d3326(0x45d,0x443,0x45d,0x446),'LjOJE':_0x5d3326(0x4b7,0x4a7,0x491,0x4ae)+'2','TODmq':_0x5d3326(0x48a,0x468,0x474,0x491),'lxBWy':'hqTkv','uvxVx':function(_0x1eaaa6,_0x394d76){return _0x1eaaa6===_0x394d76;},'ozFKL':'ZcSbh','zgTQL':function(_0x18ed54,_0x3180d4){return _0x18ed54(_0x3180d4);},'kvFDi':function(_0x14c6b4,_0x5c6597){return _0x14c6b4+_0x5c6597;},'akVGD':_0x5d3326(0x481,0x483,0x494,0x47b)+'nction()\x20','Cxwmf':_0x5d3326(0x4c0,0x4a5,0x49d,0x4b6)+_0x5d3326(0x4b6,0x48b,0x499,0x495)+_0xe0fc9a(0x146,0x159,0x132,0x14a)+'\x20)','cRrkp':function(_0x38ea29,_0x4353a3){return _0x38ea29!==_0x4353a3;},'sccbS':_0x5d3326(0x473,0x45d,0x463,0x460),'KgnLh':function(_0xd9891c){return _0xd9891c();},'mRhoo':_0x5d3326(0x46a,0x451,0x460,0x44c),'DRZHp':'warn','dIwhX':_0xe0fc9a(0x183,0x1a7,0x162,0x163),'WyBQB':_0xe0fc9a(0x155,0x170,0x170,0x164),'sBWYY':_0xe0fc9a(0x18c,0x197,0x185,0x198),'TSniq':_0xe0fc9a(0x189,0x16e,0x167,0x177),'AnqDd':'trace','Fqkim':function(_0x13c65b,_0x5384d3){return _0x13c65b<_0x5384d3;},'roDZX':function(_0x258969,_0x292405,_0x5e9110){return _0x258969(_0x292405,_0x5e9110);},'uZwpe':function(_0x3d81c9){return _0x3d81c9();},'upgLV':'Hello\x20Worl'+'d!'},_0x592658=(function(){function _0x16a1c0(_0x11e433,_0x21eb5c,_0xf526d,_0x2a60e9){return _0xe0fc9a(_0xf526d-0x14,_0x21eb5c-0x1e5,_0xf526d-0x161,_0x11e433);}var _0x3ce525={'zcGMm':function(_0x51f2e0,_0x2d5ac6){function _0x303556(_0x925a1,_0x44b5e4,_0x2b4730,_0x2db8fd){return _0x4b74(_0x44b5e4-0x2a0,_0x2b4730);}return _0x5b511a[_0x303556(0x406,0x411,0x404,0x3f1)](_0x51f2e0,_0x2d5ac6);},'fHxDi':_0x5b511a[_0x1963a7(0xed,0xc9,0xf4,0xe0)],'LUyuC':_0x1963a7(0xdb,0xdd,0xb3,0xd6)};function _0x1963a7(_0x2a297a,_0x5b965c,_0x192bd6,_0x21d5eb){return _0x5d3326(_0x192bd6,_0x5b965c-0x1ef,_0x21d5eb- -0x386,_0x21d5eb-0x9f);}if(_0x5b511a[_0x16a1c0(0x176,0x17b,0x17a,0x165)]!==_0x5b511a[_0x16a1c0(0x159,0x191,0x17d,0x192)]){var _0x56b7b7=!![];return function(_0x351e6c,_0x16bd86){var _0x5082dc={'kEDUS':_0x1f927b(0x399,0x358,0x373,0x359)+'+$','Waeai':function(_0x7fb69f,_0x5448f0){function _0x492557(_0x529b03,_0x59267d,_0x3d5f83,_0x4d399b){return _0x1f927b(_0x59267d,_0x59267d-0xfe,_0x4d399b- -0x39c,_0x4d399b-0x112);}return _0x3ce525[_0x492557(0x15,0x9,0x26,0x18)](_0x7fb69f,_0x5448f0);},'tmdvO':_0x1f927b(0x3ab,0x3ba,0x398,0x37a),'CeKAc':_0x3ce525[_0x3d4289(0x4c8,0x4aa,0x4b9,0x4ba)],'eQiRJ':_0x3ce525['LUyuC']};function _0x3d4289(_0x4a2a2b,_0x45b0b3,_0x356e81,_0x39e6f9){return _0x1963a7(_0x4a2a2b-0x121,_0x45b0b3-0x49,_0x45b0b3,_0x39e6f9-0x3bb);}var _0x3d9e1f=_0x56b7b7?function(){function _0x2fa1a9(_0x1193ef,_0x501bbb,_0x436e0e,_0x36cf3b){return _0x1f927b(_0x36cf3b,_0x501bbb-0xb5,_0x436e0e- -0x3a8,_0x36cf3b-0x32);}function _0x3175eb(_0x286fee,_0x138243,_0x53dd42,_0xf56248){return _0x3d4289(_0x286fee-0x1ac,_0xf56248,_0x53dd42-0x187,_0x286fee- -0x580);}if(_0x5082dc['Waeai'](_0x5082dc['tmdvO'],_0x5082dc[_0x3175eb(-0xb9,-0x94,-0xc3,-0x9e)])){var _0x425e18=_0x4e0e4e?function(){function _0x419101(_0x542b03,_0x26c3af,_0x36c6a5,_0x39daa3){return _0x3175eb(_0x26c3af- -0x1c,_0x26c3af-0x18e,_0x36c6a5-0x151,_0x36c6a5);}if(_0x549a1c){var _0x86b756=_0x4c0734[_0x419101(-0xf4,-0x109,-0x11a,-0x102)](_0x21684c,arguments);return _0x515061=null,_0x86b756;}}:function(){};return _0x2e4782=![],_0x425e18;}else{if(_0x16bd86){if(_0x5082dc[_0x3175eb(-0xbf,-0xb5,-0xa0,-0xa0)]('FOilA',_0x5082dc[_0x2fa1a9(-0x16,-0x26,-0x2e,-0x2a)]))return _0x1a4690[_0x3175eb(-0xf3,-0xe2,-0xf7,-0xe8)]()['search'](fBmcLw[_0x3175eb(-0xb1,-0xc5,-0x94,-0xb2)])[_0x2fa1a9(-0x2d,-0x4a,-0x3e,-0x4a)]()[_0x3175eb(-0xb8,-0x9d,-0xdc,-0xc7)+'r'](_0x49769c)[_0x3175eb(-0xc2,-0xdd,-0xe5,-0xd4)](fBmcLw[_0x2fa1a9(-0x8,0x14,0x4,-0xf)]);else{var _0x13a053=_0x16bd86['apply'](_0x351e6c,arguments);return _0x16bd86=null,_0x13a053;}}}}:function(){};_0x56b7b7=![];function _0x1f927b(_0x365f18,_0x34afd3,_0x160684,_0xe27c36){return _0x1963a7(_0x365f18-0x17c,_0x34afd3-0x11b,_0x365f18,_0x160684-0x298);}return _0x3d9e1f;};}else{if(_0x25cb90){var _0x204651=_0x1e7de9['apply'](_0x2464ca,arguments);return _0x202036=null,_0x204651;}}}());function _0x5d3326(_0x267f5d,_0x7ed7c1,_0x15a000,_0x12780b){return _0x4b74(_0x15a000-0x319,_0x267f5d);}var _0x4af546=_0x5b511a[_0x5d3326(0x44f,0x44d,0x46f,0x47f)](_0x592658,this,function(){function _0xfbb5d7(_0x19f0a6,_0x32621d,_0x298cc2,_0x249d28){return _0x5d3326(_0x19f0a6,_0x32621d-0x7f,_0x249d28- -0x17c,_0x249d28-0x59);}function _0x4b03cf(_0x58df27,_0x2c2c16,_0x45e560,_0x1d979c){return _0xe0fc9a(_0x2c2c16-0x187,_0x2c2c16-0xea,_0x45e560-0x11f,_0x45e560);}return _0x4af546[_0xfbb5d7(0x2f5,0x2e7,0x2ea,0x2dc)]()['search'](_0x5b511a[_0xfbb5d7(0x346,0x343,0x327,0x323)])[_0xfbb5d7(0x2f3,0x2c3,0x2ba,0x2dc)]()['constructo'+'r'](_0x4af546)[_0x4b03cf(0x305,0x2fb,0x2fc,0x2f6)](_0x5b511a[_0x4b03cf(0x30a,0x311,0x2f4,0x312)]);});function _0xe0fc9a(_0x61408b,_0x754818,_0x1d9a07,_0x12b945){return _0x4b74(_0x61408b-0x4,_0x12b945);}_0x5b511a[_0xe0fc9a(0x176,0x17a,0x152,0x162)](_0x4af546);var _0x145e4a=(function(){var _0x5612f1={};_0x5612f1[_0x46e10c(0x1a4,0x19e,0x197,0x181)]=_0x5b511a[_0x46e10c(0x17e,0x14f,0x167,0x16e)];function _0x5e3750(_0x47f165,_0x2120aa,_0x16bd32,_0x1a634e){return _0x5d3326(_0x16bd32,_0x2120aa-0x13f,_0x2120aa- -0x453,_0x1a634e-0xac);}var _0x20cad0=_0x5612f1,_0x2b7791=!![];function _0x46e10c(_0x15aa9f,_0x2019d2,_0x3511ff,_0x2257e8){return _0xe0fc9a(_0x3511ff-0x25,_0x2019d2-0x15f,_0x3511ff-0xb7,_0x2019d2);}return function(_0x2f23f9,_0x18332f){function _0x4ed71c(_0x4f914a,_0x10aa30,_0x473960,_0x1e513e){return _0x46e10c(_0x4f914a-0x109,_0x1e513e,_0x4f914a-0x385,_0x1e513e-0x1be);}function _0x307b5f(_0x3a42f5,_0x2f7ce2,_0x5676d4,_0x8937db){return _0x46e10c(_0x3a42f5-0xdd,_0x5676d4,_0x2f7ce2- -0x34c,_0x8937db-0xd8);}if(_0x5b511a['WZjpo'](_0x5b511a['CvlrR'],_0x307b5f(-0x1a5,-0x1c9,-0x1ed,-0x1e0))){var _0x19e79a=_0x20cad0[_0x4ed71c(0x51c,0x52e,0x522,0x517)][_0x4ed71c(0x50b,0x50d,0x528,0x4e5)]('|'),_0x465901=-0xd79+-0x10a7+0xf1*0x20;while(!![]){switch(_0x19e79a[_0x465901++]){case'0':var _0xe89e3d=_0x5e7eca[_0x304784]||_0xebf947;continue;case'1':var _0x304784=_0xaae44c[_0x13711a];continue;case'2':_0x46eb33[_0x304784]=_0xebf947;continue;case'3':var _0xebf947=_0x40f664[_0x4ed71c(0x528,0x54a,0x52c,0x515)+'r'][_0x307b5f(-0x1dc,-0x1d7,-0x1cb,-0x1f2)][_0x307b5f(-0x1aa,-0x1cf,-0x1da,-0x1e0)](_0x5ba7df);continue;case'4':_0xebf947[_0x4ed71c(0x51d,0x4fa,0x50a,0x4fa)]=_0x162087[_0x307b5f(-0x1ed,-0x1cf,-0x1c0,-0x1f2)](_0x42be8c);continue;case'5':_0xebf947['toString']=_0xe89e3d[_0x4ed71c(0x4ed,0x508,0x50e,0x4e4)]['bind'](_0xe89e3d);continue;}break;}}else{var _0x160722=_0x2b7791?function(){function _0x137923(_0x3bc0f8,_0x2ddc59,_0x3b8a28,_0x47b758){return _0x307b5f(_0x3bc0f8-0x1b4,_0x47b758-0x383,_0x3bc0f8,_0x47b758-0x41);}if(_0x18332f){var _0x117f11=_0x18332f[_0x137923(0x1aa,0x19b,0x1c5,0x1a5)](_0x2f23f9,arguments);return _0x18332f=null,_0x117f11;}}:function(){};return _0x2b7791=![],_0x160722;}};}()),_0x309d1f=_0x145e4a(this,function(){function _0x8663ed(_0x1d0cac,_0x38711c,_0x1f4848,_0x4af0f8){return _0x5d3326(_0x38711c,_0x38711c-0x1cb,_0x1f4848- -0x33c,_0x4af0f8-0xe0);}function _0x567bc7(_0xc5e725,_0x2153ac,_0x4486a8,_0x1fb4b7){return _0x5d3326(_0x4486a8,_0x2153ac-0x1a3,_0xc5e725- -0x5f5,_0x1fb4b7-0x80);}var _0x495b77={'LxwlA':_0x5b511a[_0x567bc7(-0x178,-0x17d,-0x19e,-0x187)],'faZSs':_0x5b511a[_0x567bc7(-0x196,-0x19d,-0x17e,-0x198)],'OoNVa':function(_0x4556e5,_0x255c9c){return _0x5b511a['uvxVx'](_0x4556e5,_0x255c9c);},'TRHYe':_0x5b511a['ozFKL'],'yXqvr':function(_0x582704,_0x28430d){function _0x35e2f8(_0x1e50b8,_0x303958,_0x136719,_0x2fdf81){return _0x567bc7(_0x303958-0x167,_0x303958-0x15d,_0x2fdf81,_0x2fdf81-0x165);}return _0x5b511a[_0x35e2f8(0x36,0x12,0x2c,0x11)](_0x582704,_0x28430d);},'gKQlh':function(_0x9762eb,_0x9918f3){return _0x5b511a['kvFDi'](_0x9762eb,_0x9918f3);},'JYiDH':_0x5b511a['akVGD'],'FTEpX':_0x5b511a[_0x567bc7(-0x19b,-0x177,-0x185,-0x198)]};if(_0x5b511a[_0x8663ed(0x163,0x120,0x145,0x14e)](_0x5b511a[_0x8663ed(0x118,0x136,0x130,0x143)],'MoADL')){var _0x5bf8b1=function(){function _0x20e569(_0x3f2d37,_0x22d086,_0xa013a5,_0x218b6f){return _0x567bc7(_0x3f2d37-0x20c,_0x22d086-0x160,_0x22d086,_0x218b6f-0x188);}function _0x4e4579(_0x5c807a,_0x1d1459,_0x4b4bb6,_0x52864e){return _0x567bc7(_0x4b4bb6- -0xe,_0x1d1459-0xc4,_0x5c807a,_0x52864e-0x8a);}if(_0x495b77[_0x4e4579(-0x176,-0x188,-0x18c,-0x16a)]===_0x495b77[_0x4e4579(-0x187,-0x15f,-0x184,-0x19c)]){var _0x273568=_0x44efec[_0x4e4579(-0x19c,-0x1a2,-0x1a5,-0x1c8)](_0x54d418,arguments);return _0x3d1cf4=null,_0x273568;}else{var _0x206a53;try{if(_0x495b77[_0x20e569(0x85,0x8a,0x8b,0x9d)](_0x495b77[_0x4e4579(-0x194,-0x1a7,-0x181,-0x198)],_0x4e4579(-0x1a0,-0x174,-0x18e,-0x174))){if(_0x2a222e){var _0x2f455d=_0x4d5da9[_0x4e4579(-0x1bd,-0x183,-0x1a5,-0x189)](_0x1bfd06,arguments);return _0x62f095=null,_0x2f455d;}}else _0x206a53=_0x495b77['yXqvr'](Function,_0x495b77[_0x20e569(0x87,0x93,0x6e,0xa9)](_0x495b77[_0x4e4579(-0x18c,-0x14f,-0x173,-0x197)],_0x495b77[_0x4e4579(-0x14d,-0x153,-0x167,-0x147)])+');')();}catch(_0x5a98f8){_0x206a53=window;}return _0x206a53;}},_0x29ac33=_0x5b511a[_0x567bc7(-0x172,-0x15f,-0x16d,-0x163)](_0x5bf8b1),_0x239819=_0x29ac33[_0x8663ed(0x122,0x126,0x148,0x126)]=_0x29ac33[_0x567bc7(-0x171,-0x15b,-0x187,-0x152)]||{},_0x2c1451=[_0x5b511a[_0x8663ed(0x15a,0x134,0x140,0x148)],_0x5b511a[_0x8663ed(0x14f,0x122,0x13e,0x126)],_0x5b511a[_0x567bc7(-0x17c,-0x19a,-0x157,-0x191)],_0x5b511a[_0x8663ed(0x13f,0x105,0x126,0x111)],_0x5b511a['sBWYY'],_0x5b511a[_0x8663ed(0x11e,0x151,0x144,0x14b)],_0x5b511a[_0x567bc7(-0x15e,-0x146,-0x171,-0x140)]];for(var _0x37c8c9=0x5d7+-0x458+-0x17f*0x1;_0x5b511a[_0x8663ed(0x10f,0x150,0x12f,0x127)](_0x37c8c9,_0x2c1451[_0x8663ed(0x12e,0x160,0x13c,0x11c)]);_0x37c8c9++){var _0x4be522=_0x145e4a[_0x8663ed(0x133,0x172,0x157,0x168)+'r'][_0x567bc7(-0x190,-0x176,-0x1a2,-0x18e)][_0x567bc7(-0x188,-0x183,-0x199,-0x173)](_0x145e4a),_0x33e191=_0x2c1451[_0x37c8c9],_0x5984cd=_0x239819[_0x33e191]||_0x4be522;_0x4be522[_0x8663ed(0x142,0x146,0x14c,0x152)]=_0x145e4a[_0x567bc7(-0x188,-0x183,-0x16b,-0x17e)](_0x145e4a),_0x4be522[_0x8663ed(0x128,0x129,0x11c,0xf7)]=_0x5984cd[_0x8663ed(0x106,0x110,0x11c,0x10c)]['bind'](_0x5984cd),_0x239819[_0x33e191]=_0x4be522;}}else _0x1f0131=_0x5c817d;});_0x5b511a[_0x5d3326(0x4a9,0x478,0x48b,0x47e)](_0x309d1f),console[_0xe0fc9a(0x14b,0x129,0x125,0x12c)](_0x5b511a[_0xe0fc9a(0x17a,0x172,0x15d,0x19c)]);}function _0x4b74(_0x4f2682,_0x3836c5){var _0x259a04=_0x5c42();return _0x4b74=function(_0x21aa73,_0x39ff94){_0x21aa73=_0x21aa73-(0xeeb+-0x1141*0x2+-0x1*-0x14d5);var _0x5af900=_0x259a04[_0x21aa73];if(_0x4b74['slaUSB']===undefined){var _0x4d4a01=function(_0x19d7ab){var _0xed8e19='abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789+/=';var _0x171598='',_0xf1840a='',_0x1256fd=_0x171598+_0x4d4a01;for(var _0x561b6b=0x71*-0x33+-0x86b+-0xd6*-0x25,_0x352aed,_0x125c98,_0x1658b2=-0x1*-0x1541+0x2*0xa15+-0x296b;_0x125c98=_0x19d7ab['charAt'](_0x1658b2++);~_0x125c98&&(_0x352aed=_0x561b6b%(0x20fa+0x16c3*-0x1+-0xa33)?_0x352aed*(0x3c*0x47+0xee+0x3*-0x5c6)+_0x125c98:_0x125c98,_0x561b6b++%(-0x2481+-0x125f*-0x1+-0x17*-0xca))?_0x171598+=_0x1256fd['charCodeAt'](_0x1658b2+(-0x21*0x9e+-0x81b+0x1c83))-(-0x941+0xc*-0x110+-0x201*-0xb)!==0x1036*0x1+-0x3*0x17b+0x1*-0xbc5?String['fromCharCode'](-0x1243+0x146b*0x1+-0x3*0x63&_0x352aed>>(-(-0x1*0x16b+0xe7d*0x1+-0xd10)*_0x561b6b&0x164e+0x2*0xb9c+-0x2d80)):_0x561b6b:0x1*0x22e9+-0x302+0x1fe7*-0x1){_0x125c98=_0xed8e19['indexOf'](_0x125c98);}for(var _0x579882=0x5b3+0x1851+-0x1e04,_0xbc33f3=_0x171598['length'];_0x579882<_0xbc33f3;_0x579882++){_0xf1840a+='%'+('00'+_0x171598['charCodeAt'](_0x579882)['toString'](0x13f4+0x679*-0x1+0x1*-0xd6b))['slice'](-(-0x1d6d+-0x2*0x10bd+0x3ee9));}return decodeURIComponent(_0xf1840a);};_0x4b74['UWlgNw']=_0x4d4a01,_0x4f2682=arguments,_0x4b74['slaUSB']=!![];}var _0x7c5571=_0x259a04[-0xbad+-0x2*0x9a1+0x1eef],_0x250e12=_0x21aa73+_0x7c5571,_0x5f176f=_0x4f2682[_0x250e12];if(!_0x5f176f){var _0x248f47=function(_0x581f69){this['mEDesW']=_0x581f69,this['XTBuHM']=[-0x1a*-0x14c+0x1e2b+0x1e1*-0x22,-0x96a+0x1318+-0x9ae,-0x6d7*-0x4+0xe27+-0x2983*0x1],this['XGjLle']=function(){return'newState';},this['plMrSb']='\x5cw+\x20*\x5c(\x5c)\x20*{\x5cw+\x20*',this['oQPQxq']='[\x27|\x22].+[\x27|\x22];?\x20*}';};_0x248f47['prototype']['OvWWIP']=function(){var _0x226d90=new RegExp(this['plMrSb']+this['oQPQxq']),_0x58f783=_0x226d90['test'](this['XGjLle']['toString']())?--this['XTBuHM'][0xf9d+0x1308+-0x3*0xb8c]:--this['XTBuHM'][-0xc1e+0xb3*0x2a+-0x1140];return this['tdwSux'](_0x58f783);},_0x248f47['prototype']['tdwSux']=function(_0x5ed8dd){if(!Boolean(~_0x5ed8dd))return _0x5ed8dd;return this['nLbOdL'](this['mEDesW']);},_0x248f47['prototype']['nLbOdL']=function(_0x392e31){for(var _0x212ddd=-0x1669+-0x1*-0x9d+0x15cc,_0x8f1831=this['XTBuHM']['length'];_0x212ddd<_0x8f1831;_0x212ddd++){this['XTBuHM']['push'](Math['round'](Math['random']())),_0x8f1831=this['XTBuHM']['length'];}return _0x392e31(this['XTBuHM'][0x1936+-0x1*0x1a83+0x14d*0x1]);},new _0x248f47(_0x4b74)['OvWWIP'](),_0x5af900=_0x4b74['UWlgNw'](_0x5af900),_0x4f2682[_0x250e12]=_0x5af900;}else _0x5af900=_0x5f176f;return _0x5af900;},_0x4b74(_0x4f2682,_0x3836c5);}hi();
```

  
把上面的混淆代码保存为js文件\(命名为Medium.js\)，并编码为UTF-8模式。存放在 main.js 统一目录，运行命令:

```css
 node main.js Medium.js
```

  
运行后，同样可以在 output 文件夹看到还原后的结果。  
  
当然，你还可以指定生成的文件名，如下命令:

```css
node main.js Medium.js 666.js
```

可以发现，在main.js的同级目录新生成了一个 666.js文件，这就是还原后的文件。  
好了，脚本的使用就介绍到这里，希望各位大佬们不要吝惜你的star，帮忙点一个，感谢！
