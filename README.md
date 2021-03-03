中华人民共和国行政区划代码
---

[![Github Issues](https://img.shields.io/github/issues/uiwjs/province-city-china.svg)](https://github.com/uiwjs/province-city-china/issues) [![Github Forks](https://img.shields.io/github/forks/uiwjs/province-city-china.svg)](https://github.comuiwjs/province-city-china/network) [![Github Stars](https://img.shields.io/github/stars/uiwjs/province-city-china.svg)](https://github.com/uiwjs/province-city-china/stargazers) [![Github Release](https://img.shields.io/github/release/uiwjs/province-city-china.svg)](https://github.com/uiwjs/province-city-china/releases) ![](http://wabg.github.io/sb/status/no-dependencies.svg) [![npm package](https://img.shields.io/npm/v/province-city-china.svg)](https://www.npmjs.com/package/province-city-china)

中华人民共和国行政区划（五级）：省级、地级、县级、乡级和村级。来自中华人民共和国民政部，用于查询中国省，市和区数据的网站。 

```
数据更新时间：2020/11/24 20:24:52 GMT+0800 (中国标准时间)
```

- [中华人民共和国行政区划代码，更新时间：2020-11-20](http://www.mca.gov.cn/article/sj/xzqh/2020/)  
- [统计用区划和城乡划分代码，更新时间：2020-11-06](http://www.stats.gov.cn/tjsj/tjbz/tjyqhdmhcxhfdm/)
- [国家和地区代码列表(下载)，更新时间：2011-12-06](http://www.mohrss.gov.cn/SYrlzyhshbzb/zhuanti/jinbaogongcheng/Jbgcbiaozhunguifan/201112/t20111206_47429.html)

### 数据更新 Diff

- [数据更新 2020/11/24](https://github.com/uiwjs/province-city-china/compare/v6.1.1...v7.0.0) 
- [数据更新 2020/11/05](https://github.com/uiwjs/province-city-china/compare/v6.0.3...v6.1.1) 
- [数据更新 2020/07/28](https://github.com/uiwjs/province-city-china/commit/f511f4b) 县以上行政区【没变】，县以下发生变更
- [数据更新 2020/03/30](https://github.com/uiwjs/province-city-china/commit/14cb636)
- [数据更新 2020/03/06](https://github.com/uiwjs/province-city-china/commit/eacab73)
- [数据更新 2019/12/24](https://github.com/uiwjs/province-city-china/commit/85cde25)
- [数据更新 2019/11/25](https://github.com/uiwjs/province-city-china/commit/d001be0)
- [数据更新 2019/11/05](https://github.com/uiwjs/province-city-china/commit/5e9eeba854677018fcb7975dd460c86195b98ccc)
- [数据更新 2019/06/21](https://github.com/uiwjs/province-city-china/commit/77408e62c1945cc3235f68f2b7c7f79be132bf99)

### 安装

```bash
npm install province-city-china --save-dev
```

| 包名 | 说明  | 版本 | 大小 |
| ---- | ---- | ---- | ---- |
| [province-city-china](https://github.com/uiwjs/province-city-china) | 包含所有包内容 | [![npm package](https://img.shields.io/npm/v/province-city-china.svg)](https://www.npmjs.com/package/province-city-china) | - |
| [@province-city-china/country](packages/country) | 国家和地区代码列表 | [![npm package](https://img.shields.io/npm/v/@province-city-china/country.svg)](https://www.npmjs.com/package/@province-city-china/country) |![](https://img.shields.io/bundlephobia/min/@province-city-china/country) |
| [@province-city-china/data](packages/data) | 总数据(省/地/县/乡) | [![npm package](https://img.shields.io/npm/v/@province-city-china/data.svg)](https://www.npmjs.com/package/@province-city-china/data) | ![](https://img.shields.io/bundlephobia/min/@province-city-china/data) |
| [@province-city-china/province](packages/province) | 省级(省/直辖市/特别行政区) | [![npm package](https://img.shields.io/npm/v/@province-city-china/province.svg)](https://www.npmjs.com/package/@province-city-china/province) | ![](https://img.shields.io/bundlephobia/min/@province-city-china/province) |
| [@province-city-china/city](packages/city) | 地级(城市) | [![npm package](https://img.shields.io/npm/v/@province-city-china/city.svg)](https://www.npmjs.com/package/@province-city-china/city) | ![](https://img.shields.io/bundlephobia/min/@province-city-china/city) |
| [@province-city-china/area](packages/area) | 县级(区县) | [![npm package](https://img.shields.io/npm/v/@province-city-china/area.svg)](https://www.npmjs.com/package/@province-city-china/area) | ![](https://img.shields.io/bundlephobia/min/@province-city-china/area) |
| [@province-city-china/town](packages/town) | 乡级(乡镇/街) | [![npm package](https://img.shields.io/npm/v/@province-city-china/town.svg)](https://www.npmjs.com/package/@province-city-china/town) | ![](https://img.shields.io/bundlephobia/min/@province-city-china/town) |
| [@province-city-china/level](packages/level) | 总数据(省/地/县/乡)层级数据 | [![npm package](https://img.shields.io/npm/v/@province-city-china/level.svg)](https://www.npmjs.com/package/@province-city-china/level) | ![](https://img.shields.io/bundlephobia/min/@province-city-china/level) |
| [@province-city-china/utils](packages/utils) | 提供使用数据方法 | [![npm package](https://img.shields.io/npm/v/@province-city-china/utils.svg)](https://www.npmjs.com/package/@province-city-china/utils) | ![](https://img.shields.io/bundlephobia/min/@province-city-china/utils) |
| [@province-city-china/types](packages/types) | 类型文件 | [![npm package](https://img.shields.io/npm/v/@province-city-china/types.svg)](https://www.npmjs.com/package/@province-city-china/types) | - |

### 使用

```js
const { data, province, city, area, town } = require('province-city-china/data');
```

- `data` - 总数据(省/地/县/乡)
- `province` - 省级(省/直辖市/特别行政区)
- `city` - 地级(城市)
- `area` - 县级(区县)
- `town` - 乡级(乡镇/街)

**所有数据**

```js
const provinces = require('province-city-china/dist/data.json');
// provinces 输出 ===>
[
  {"code":"110000","name":"北京市","province":"11","city":0,"area":0,"town":0},
  {"code":"110101","name":"东城区","province":"11","city":"01","area":"01","town":0},
  {"code":"110102","name":"西城区","province":"11","city":"01","area":"02","town":0},
  {"code":"110105","name":"朝阳区","province":"11","city":"01","area":"05","town":0},
  ....
]
```

规则：

- `province - 省级(省/直辖市/特别行政区)` - `city=0`, `area=0`, `town=0`
- `city - 地级(城市)` - `area=0`, `town=0`
- `area - 县级(区县)` - `town=0` 其它不为 `0`
- `town - 乡级(乡镇/街)` - 所有值不为 `0`

> `province` 第一位表示：华北区`1`，东北区`2`，华东区`3`，中南区`4`，西南区`5`，西北区`6`。 如 `湖北省 -> 42` 以 `4` 开头，表示为 `中南区`。

**获取城市数据**

```js
const city = require('province-city-china/dist/city.json');
// city 输出 ===>
[
  {"code":"01","name":"石家庄市","province":"13"},
  {"code":"02","name":"唐山市","province":"13"},
  {"code":"03","name":"秦皇岛市","province":"13"},
  {"code":"04","name":"邯郸市","province":"13"},
  {"code":"05","name":"邢台市","province":"13"},
  ....
]
```

说明：

- `code` - 城市代码
- `name` - 城市名称
- `province` - 省/直辖市/特别行政区代码

## 更多数据

> 可以通过 [UNPKG](https://unpkg.com/province-city-china/dist/) 下载使用 `CDN` 资源: https://unpkg.com/province-city-china/dist/

| 文件列表 | JSON | CSV | SQL | CDN |
| ---- | ---- | ---- | ---- |  ---- |
| 国家和地区代码列表([#13](https://github.com/uiwjs/province-city-china/issues/13)) | [country.json](https://github.com/uiwjs/province-city-china/blob/gh-pages/country.json) ([min](https://github.com/uiwjs/province-city-china/blob/gh-pages/country.min.json)) | [country.csv](https://github.com/uiwjs/province-city-china/blob/gh-pages/country.csv) | - | [csv](https://unpkg.com/province-city-china/dist/country.csv) / [json](https://unpkg.com/province-city-china/dist/country.json) |
| 总数据(省/地/县/乡) | [data.json](https://github.com/uiwjs/province-city-china/blob/gh-pages/data.json) ([min](https://github.com/uiwjs/province-city-china/blob/gh-pages/data.min.json)) | [data.csv](https://github.com/uiwjs/province-city-china/blob/gh-pages/data.csv) | [data.sql](https://github.com/uiwjs/province-city-china/blob/gh-pages/data.sql) | [data.sql](https://unpkg.com/province-city-china/dist/data.sql) / [csv](https://unpkg.com/province-city-china/dist/data.csv) / [json](https://unpkg.com/province-city-china/dist/data.json) |
| 总数据(省/地/县/乡)层级数据 | [level.json](https://github.com/uiwjs/province-city-china/blob/gh-pages/level.json) ([min](https://github.com/uiwjs/province-city-china/blob/gh-pages/level.min.json)) | - | - | [level.json](https://unpkg.com/province-city-china/dist/level.json) |
| 省级(省/直辖市/特别行政区) | [province.json](https://github.com/uiwjs/province-city-china/blob/gh-pages/province.json) ([min](https://github.com/uiwjs/province-city-china/blob/gh-pages/province.min.json)) | [province.csv](https://github.com/uiwjs/province-city-china/blob/gh-pages/province.csv) | - | [province.json](https://unpkg.com/province-city-china/dist/province.json) / [csv](https://unpkg.com/province-city-china/dist/province.csv) |
| 地级(城市) | [city.json](https://github.com/uiwjs/province-city-china/blob/gh-pages/city.json) ([min](https://github.com/uiwjs/province-city-china/blob/gh-pages/city.min.json)) | [city.csv](https://github.com/uiwjs/province-city-china/blob/gh-pages/city.csv) | - | [city.json](https://unpkg.com/province-city-china/dist/city.json) / [csv](https://unpkg.com/province-city-china/dist/city.csv) |
| 县级(区县) | [area.json](https://github.com/uiwjs/province-city-china/blob/gh-pages/area.json) ([min](https://github.com/uiwjs/province-city-china/blob/gh-pages/area.min.json)) | [area.csv](https://github.com/uiwjs/province-city-china/blob/gh-pages/area.csv) | - | [area.json](https://unpkg.com/province-city-china/dist/area.json) / [csv](https://unpkg.com/province-city-china/dist/area.csv) |
| 乡级(乡镇/街) | [town.json](https://github.com/uiwjs/province-city-china/blob/gh-pages/town.json) ([min](https://github.com/uiwjs/province-city-china/blob/gh-pages/town.min.json)) | [town.csv](https://github.com/uiwjs/province-city-china/blob/gh-pages/town.csv) | - | [town.json](https://unpkg.com/province-city-china/dist/town.json) / [csv](https://unpkg.com/province-city-china/dist/town.csv) |
| 县市区没有乡级数据 | [cityNotFoundTown.json](https://github.com/uiwjs/province-city-china/blob/gh-pages/cityNotFoundTown.json) ([min](https://github.com/uiwjs/province-city-china/blob/gh-pages/cityNotFoundTown.min.json)) | - | - | [cityNotFoundTown.json](https://unpkg.com/province-city-china/dist/cityNotFoundTown.json) |

更多 CDN 数据访问

- https://unpkg.com/province-city-china/dist/city.json
- https://raw.githack.com/uiwjs/province-city-china/gh-pages/city.json
- https://cdn.statically.io/gh/uiwjs/province-city-china/gh-pages/city.json

```bash
> <省市区>数据：3212
  ✔ 数据保存: dist/data.json
> <省>数据：34
  ✔ 数据保存: dist/province.json
  ✔ 数据保存: dist/province.csv
> <市>数据：333
  ✔ 数据保存: dist/city.json
  ✔ 数据保存: dist/city.csv
> <区>数据：2845
  ✔ 数据保存: dist/area.json
  ✔ 数据保存: dist/area.csv
> 省市区:数据生成完成！
```

### 国家和地区代码列表

[country.json](https://github.com/uiwjs/province-city-china/blob/gh-pages/country.json) | [country.min.json](https://github.com/uiwjs/province-city-china/blob/gh-pages/country.min.json) | [country.csv](https://github.com/uiwjs/province-city-china/blob/gh-pages/country.csv)

<kbd>id=序号</kbd>、<kbd>cnname=中文简称</kbd>、<kbd>name=英文简称</kbd>、<kbd>fullname=英文全称</kbd>、<kbd>alpha2=两字母代码</kbd>、<kbd>alpha3=三字母代码</kbd>、<kbd>numeric=数字代码</kbd>

```js
[
  {
    "id": 1,
    "cnname": "阿富汗",
    "name": "Afghanistan",
    "fullname": "the Islamic Republic of Afghanistan",
    "alpha2": "AF",
    "alpha3": "AFG",
    "town": 4
  },
  {
    "id": 45,
    "cnname": "中国",
    "name": "China",
    "fullname": "the People's Republic of China",
    "alpha2": "CN",
    "alpha3": "CHN",
    "town": 156
  }
  // ...
]
```

压缩数据说明 [country.min.json](https://github.com/uiwjs/province-city-china/blob/gh-pages/country.min.json)

```js
id: 'i'
cnname: 'c'
name: 'n'
fullname: 'f'
alpha2: 'a2'
alpha3: 'a3'
numeric: 'r'
```

### 总数据(省/地/县/乡)

[data.json](https://github.com/uiwjs/province-city-china/blob/gh-pages/data.json) | [data.min.json](https://github.com/uiwjs/province-city-china/blob/gh-pages/data.min.json) | [data.csv](https://github.com/uiwjs/province-city-china/blob/gh-pages/data.csv) | [data.sql](https://github.com/uiwjs/province-city-china/blob/gh-pages/data.sql) 

```js
[
  {
    "code": "110000",
    "name": "北京市",
    "province": "11",
    "city": 0,
    "area": 0,
    "town": 0
  },
  // ...
]
```

压缩数据说明 [data.min.json](https://github.com/uiwjs/province-city-china/blob/gh-pages/data.min.json)

```js
code: 'c'
name: 'n'
province: 'p'
city: 'y'
area: 'a'
town: 't'
```

### 省/地/县/乡层级数据

[level.json](https://github.com/uiwjs/province-city-china/blob/gh-pages/level.json) | [level.min.json](https://github.com/uiwjs/province-city-china/blob/gh-pages/level.min.json)

```js
[
  {
    "code": "420000",
    "name": "湖北省",
    "province": "42",
    "children": [
      {
        "code": "420100",
        "name": "武汉市",
        "province": "42",
        "city": "01",
        "children": [
          {
            "code": "420102",
            "name": "江岸区",
            "province": "42",
            "city": "01",
            "area": "02"
          },
          // ...
        ]
      }
      // ...
    ]
  }
  // ...
]
```

压缩数据说明 [level.min.json](https://github.com/uiwjs/province-city-china/blob/gh-pages/level.min.json)

```js
code: 'c'
name: 'n'
province: 'p'
city: 'y'
area: 'a'
children: 'd'
```

### 省级(省/直辖市/特别行政区)

[province.json](https://github.com/uiwjs/province-city-china/blob/gh-pages/province.json) | [province.min.json](https://github.com/uiwjs/province-city-china/blob/gh-pages/province.min.json) | [province.csv](https://github.com/uiwjs/province-city-china/blob/gh-pages/province.csv)

```js
[
  {
    "code": "110000",
    "name": "北京市",
    "province": "11"
  },
  {
    "code": "120000",
    "name": "天津市",
    "province": "12"
  },
  // ...
]
```

压缩数据说明 [level.min.json](https://github.com/uiwjs/province-city-china/blob/gh-pages/level.min.json)

```js
code: 'c'
name: 'n'
province: 'p'
city: 'y'
area: 'a'
children: 'd'
```

### 地级(城市)

[city.json](https://github.com/uiwjs/province-city-china/blob/gh-pages/city.json) | [city.min.json](https://github.com/uiwjs/province-city-china/blob/gh-pages/city.min.json) | [city.csv](https://github.com/uiwjs/province-city-china/blob/gh-pages/city.csv)

```js
[
  {
    "code": "130100",
    "name": "石家庄市",
    "province": "13",
    "city": "01"
  },
  // ...
]
```

压缩数据说明 [city.min.json](https://github.com/uiwjs/province-city-china/blob/gh-pages/city.min.json)

```js
code: 'c'
name: 'n'
province: 'p'
city: 'y'
```

### 县级(区县)

[area.json](https://github.com/uiwjs/province-city-china/blob/gh-pages/area.json) | [area.min.json](https://github.com/uiwjs/province-city-china/blob/gh-pages/area.min.json) | [area.csv](https://github.com/uiwjs/province-city-china/blob/gh-pages/area.csv)

```js
[
  {
    "code": "110101",
    "name": "东城区",
    "province": "11",
    "city": "01",
    "area": "01"
  },
  // ...
]
```

压缩数据说明 [city.min.json](https://github.com/uiwjs/province-city-china/blob/gh-pages/city.min.json)

```js
code: 'c'
name: 'n'
province: 'p'
city: 'y'
area: 'a'
```

### 乡级(乡镇/街)

[town.json](https://github.com/uiwjs/province-city-china/blob/gh-pages/town.json) | [town.min.json](https://github.com/uiwjs/province-city-china/blob/gh-pages/town.min.json) | [town.csv](https://github.com/uiwjs/province-city-china/blob/gh-pages/town.csv)

```js
[
  {
    "code": "110101001000",
    "name": "东华门街道",
    "province": "11",
    "city": "01",
    "area": "01",
    "town": "001000"
  },
  // ...
]
```

压缩数据说明 [city.min.json](https://github.com/uiwjs/province-city-china/blob/gh-pages/city.min.json)

```js
code: 'c'
name: 'n'
province: 'p'
city: 'y'
area: 'a'
town: 't'
```

### 县市区没有乡级数据

[cityNotFoundTown.json](https://github.com/uiwjs/province-city-china/blob/gh-pages/cityNotFoundTown.json) | [cityNotFoundTown.min.json](https://github.com/uiwjs/province-city-china/blob/gh-pages/cityNotFoundTown.min.json)

```js
[
  {
    "code": "659010",
    "name": "胡杨河市",
    "province": "65",
    "city": "90",
    "area": "10",
    "town": 0
  },
  // ...
]
```

压缩数据说明 [cityNotFoundTown.min.json](https://github.com/uiwjs/province-city-china/blob/gh-pages/cityNotFoundTown.min.json)

```js
code: 'c'
name: 'n'
province: 'p'
city: 'y'
area: 'a'
town: 't'
```

## 参考链接

- [国家统计局 - 行政区划代码](http://www.stats.gov.cn/tjsj/tjbz/tjyqhdmhcxhfdm/)
- [民政部 - 中华人民共和国行政区划代码](http://www.mca.gov.cn/article/sj/xzqh)
- [高德地图 - 行政区划](https://lbs.amap.com/api/webservice/guide/api/district)
- [维基百科 - 中华人民共和国行政区划](https://zh.wikipedia.org/wiki/%E4%B8%AD%E5%8D%8E%E4%BA%BA%E6%B0%91%E5%85%B1%E5%92%8C%E5%9B%BD%E8%A1%8C%E6%94%BF%E5%8C%BA%E5%88%92)
- [维基百科 - 中华人民共和国行政区划代码](https://zh.wikipedia.org/wiki/%E4%B8%AD%E5%8D%8E%E4%BA%BA%E6%B0%91%E5%85%B1%E5%92%8C%E5%9B%BD%E8%A1%8C%E6%94%BF%E5%8C%BA%E5%88%92%E4%BB%A3%E7%A0%81)
- [统计上使用的县以下行政区划代码编制规则](http://www.mca.gov.cn/article/sj/xzqh/1980/201507/20150715854849.shtml)
- [民政统计代码编制规则](http://www.mca.gov.cn/article/sj/xzqh/1980/201507/20150715854848.shtml)
- [国家和地区代码列表（下载）](http://www.mohrss.gov.cn/SYrlzyhshbzb/zhuanti/jinbaogongcheng/Jbgcbiaozhunguifan/201112/t20111206_47429.html)

## License

[MIT](./LICENSE)
