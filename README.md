# Cnblogs-Theme-Xhanglog
博客园皮肤，在作者BNDong基础上修改，原地址https://github.com/BNDong/Cnblogs-Theme-SimpleMemory

博客设置
设置博客皮肤
博客皮肤：SimpleMemory

install_02

设置页面定制CSS代码
CSS代码位置：/src/style/base.min.css 拷贝此文件代码至页面定制CSS代码文本框处。

!> /src/style/base.min.css 的修改参考 /src/style/base.css。博客设置请使用压缩版本，直接使用 /src/style/base.css 会字符超限！

install_03

禁用模板默认CSS
选中页面定制CSS代码文本框下面的禁用模板默认CSS。

设置博客侧边栏公告
?> 推荐版本 >= v1.1.2，建议使用最新版本：GitHub release

在侧边栏HTML代码中设置以下代码：

<script type="text/javascript">
    window.cnblogsConfig = {
        GhVersions    : 'v1.2.3', // 版本
        blogUser      : "userName", // 用户名
        blogAvatar    : "https://xxxx.png", // 用户头像
        blogStartDate : "2016-11-17", // 入园时间，年-月-日。入园时间查看方法：鼠标停留园龄时间上，会显示入园时间
    }
</script>
<script src="https://cdn.jsdelivr.net/gh/BNDong/Cnblogs-Theme-SimpleMemory@v1.2.3/src/script/simpleMemory.min.js"></script>
!> 注意：引入的文件 simpleMemory.min.js 版本需要与配置 window.cnblogsConfig.GhVersions 一致！

详细配置参考相关文档。

install_04

配置完成保存即可成功应用博皮！
