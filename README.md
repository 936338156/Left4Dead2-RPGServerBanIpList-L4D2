# L4D2-RPGServerBanIpList

## 用途

* 通过将RPG服务器的IP加入到防火墙的黑名单里面来防止在服务器浏览器内搜索到RPG服务器（省的碍眼）
* 当快速匹配连接到RPG服务器的时候阻止连接。是的，快速匹配任然会尝试连接RPG服务器（我也不知道为什么，控制台内显示连接的就是RPG服务器的IP，按理说应该是无法被匹配到的）但现在会因为防火墙黑名单而导致连接超时。

---

## 使用方法

### 使用火绒导入

1. 到[Releases](https://github.com/936338156/Left4Dead2-RPGServerBanIpList-L4D2/releases)下载最新的 `L4D2-RPGServerBanIpList.json`
2. 前往火绒主界面
3. 依次点击右上角的三条横线[菜单]，安全设置，高级防护，IP黑名单
4. 点击IP黑名单下方的导入，选择 `L4D2-RPGServerBanIpList.json`再点击打开，然后就导入完成了

---

### ~~使用OpenWRT导入~~

~~我没有用过OpenWRT所以不会qwq，但据说可以导入~~
