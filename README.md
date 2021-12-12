# Toutube去广告教程，Toutube小火箭去广告代码

### 观看视频教程操作：

### 操作步骤<br>

1、打开Shadowrocket → 配置 → default.conf → 编辑配置 → HTTPS解密 → 开启HTTPS解密 → 生成新的CA订书 → 生成新的CA订书 → 安装证书 → 允许 → 打开设置 → 已下载描述文件 → 安装 → 安装 → 安装 → 完成 → 通用 → 关于本机 → 证书信任设置 → 开启信任Shadowrocket证书 → 继续 → 打开Shadowrocket → 关闭 → √ → √ → 配置 → default.conf → 编辑纯文本 → 滚动条拉到最下面 <br>
在最下面粘贴以下代码：

第一段：

    [URL Rewrite]
    ctier=L?ctier=A?302
    ^https:\/\/[\s\S]*\.googlevideo\.com/.*&(oad|ctier)?_?REJECT



第二段：

    *.googlevideo.com


再点击保存。

4、在Shadowrocket添加节点，开启科学上网