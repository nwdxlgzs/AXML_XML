# AXML_XML
axml和xml互转工程

`lua`调用demo
`注意，支持函中文的反编译，但是回编译不支持中文`
<br/>
```lua
import"com.nwdxlgzs.utils.xml.export.*"

--解码
AXMLparser().parse(输入,输出)
--解码获得字符串
str=AXMLparser().parse(输入)

--编码
XMLparser().parse(activity,输入,输出)
--编码获得字节
byte=XMLparser().parse(activity,输入)
```
