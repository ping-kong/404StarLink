## 信息收集 / reconnaissance

1. [ksubdomain](#ksubdomain)
2. [AppInfoScanner](#appinfoscanner)
3. [HaE](#hae)
4. [DarkEye](#darkeye)
5. [Kunyu](#kunyu)
6. [Glass](#glass)
7. [ZoomEye-Python](#zoomeye-python)
8. [ct](#ct)
9. [Zoomeye-Tools](#zoomeye-tools)
10. [ZoomEye-go](#zoomeye-go)

----------------------------------------

### [ksubdomain](detail/ksubdomain.md)
![Author](https://img.shields.io/badge/Author-w7ay-orange)
![Language](https://img.shields.io/badge/Language-Golang-blue)
![GitHub stars](https://img.shields.io/github/stars/knownsec/ksubdomain.svg?style=flat&logo=github)
![Version](https://img.shields.io/badge/Version-V0.7-red)

<https://github.com/knownsec/ksubdomain>

ksubdomain是一款基于无状态子域名爆破工具，支持在Windows/Linux/Mac上使用，它会很快的进行DNS爆破，在Mac和Windows上理论最大发包速度在30w/s,linux上为160w/s的速度。

### [AppInfoScanner](detail/AppInfoScanner.md)
![Author](https://img.shields.io/badge/Author-kelvinBen-orange)
![Language](https://img.shields.io/badge/Language-Python-blue)
![GitHub stars](https://img.shields.io/github/stars/kelvinBen/AppInfoScanner.svg?style=flat&logo=github)
![Version](https://img.shields.io/badge/Version-V1.0.8-red)

<https://github.com/kelvinBen/AppInfoScanner>

一款适用于以HW行动/红队/渗透测试团队为场景的移动端(Android、iOS、WEB、H5、静态网站)信息收集扫描工具，可以帮助渗透测试工程师、攻击队成员、红队成员快速收集到移动端或者静态WEB站点中关键的资产信息并提供基本的信息输出,如：Title、Domain、CDN、指纹信息、状态信息等。

### [HaE](detail/HaE.md)
![Author](https://img.shields.io/badge/Author-gh0stkey-orange)
![Language](https://img.shields.io/badge/Language-Java-blue)
![GitHub stars](https://img.shields.io/github/stars/gh0stkey/HaE.svg?style=flat&logo=github)
![Version](https://img.shields.io/badge/Version-V2.1.3-red)

<https://github.com/gh0stkey/HaE>

HaE是一款可以快速挖掘目标指纹和关键信息的Burp插件。

### [DarkEye](detail/DarkEye.md)
![Author](https://img.shields.io/badge/Author-zsdevX-orange)
![Language](https://img.shields.io/badge/Language-Golang-blue)
![GitHub stars](https://img.shields.io/github/stars/zsdevX/DarkEye.svg?style=flat&logo=github)
![Version](https://img.shields.io/badge/Version-V4.3.0-red)

<https://github.com/zsdevX/DarkEye>

基于go完成的渗透测试信息收集利器

### [Kunyu](detail/Kunyu.md)
![Author](https://img.shields.io/badge/Author-风起-orange)
![Language](https://img.shields.io/badge/Language-Python-blue)
![GitHub stars](https://img.shields.io/github/stars/knownsec/Kunyu.svg?style=flat&logo=github)
![Version](https://img.shields.io/badge/Version-V1.6.4-red)

<https://github.com/knownsec/Kunyu>

Kunyu(坤舆)，是一款基于ZoomEye API开发的信息收集工具，旨在让企业资产收集更高效，使更多安全相关从业者了解、使用网络空间测绘技术。

### [Glass](detail/Glass.md)
![Author](https://img.shields.io/badge/Author-s7ckTeam-orange)
![Language](https://img.shields.io/badge/Language-Python-blue)
![GitHub stars](https://img.shields.io/github/stars/s7ckTeam/Glass.svg?style=flat&logo=github)
![Version](https://img.shields.io/badge/Version-V2.0.6-red)

<https://github.com/s7ckTeam/Glass>

Glass是一款针对资产列表的快速指纹识别工具，通过调用Fofa/ZoomEye/Shodan/360等api接口快速查询资产信息并识别重点资产的指纹，也可针对IP/IP段或资产列表进行快速的指纹识别。

### [ZoomEye-Python](detail/ZoomEye-Python.md)
![Author](https://img.shields.io/badge/Author-Knownsec404-orange)
![Language](https://img.shields.io/badge/Language-Python-blue)
![GitHub stars](https://img.shields.io/github/stars/knownsec/ZoomEye-python.svg?style=flat&logo=github)
![Version](https://img.shields.io/badge/Version-V2.1.1-red)

<https://github.com/knownsec/ZoomEye-python>

ZoomEye-python 是一款基于 ZoomEye API 开发的 Python 库，提供了 ZoomEye 命令行模式，同时也可以作为 SDK 集成到其他工具中。该库可以让技术人员更便捷地搜索、筛选、导出 ZoomEye 的数据

### [ct](detail/ct.md)
![Author](https://img.shields.io/badge/Author-rungobier@Knownsec404-orange)
![Language](https://img.shields.io/badge/Language-Rust-blue)
![GitHub stars](https://img.shields.io/github/stars/knownsec/ct.svg?style=flat&logo=github)
![Version](https://img.shields.io/badge/Version-V1.0.5-red)

<https://github.com/knownsec/ct>

ct 是一款使用 rust 语言进行开发，并且基于ZoomEye域名查询以及利用域名字典进行子域名爆破的工具，同时在最终爆破完成后可使用脚本，将相应的的.gv 文件转化成为相应的 .png 文件进行可视化展示

### [Zoomeye-Tools](detail/ZoomEye-Tools.md)
![Author](https://img.shields.io/badge/Author-Knownsec404-orange)
![Language](https://img.shields.io/badge/Language-JS-blue)
![GitHub stars](https://img.shields.io/github/stars/knownsec/Zoomeye-Tools.svg?style=flat&logo=github)
![Version](https://img.shields.io/badge/Version-V0.3.2-red)

<https://github.com/knownsec/Zoomeye-Tools>

一个配合ZoomEye使用的Chrome插件，可以查看当前网页所在ip信息或跳转查看详细信息，还可以根据关键词一键跳转至ZoomEye进行搜索

### [ZoomEye-go](detail/ZoomEye-go.md)
![Author](https://img.shields.io/badge/Author-gyyyy-orange)
![Language](https://img.shields.io/badge/Language-Golang-blue)
![GitHub stars](https://img.shields.io/github/stars/gyyyy/ZoomEye-go.svg?style=flat&logo=github)
![Version](https://img.shields.io/badge/Version-V1.5.0-red)

<https://github.com/gyyyy/ZoomEye-go>

ZoomEye-go 是一款基于 ZoomEye API 开发的 Golang 库，提供了 ZoomEye 命令行模式，同时也可以作为SDK集成到其他工具中。该库可以让技术人员更便捷地搜索、筛选、导出 ZoomEye 的数据。

