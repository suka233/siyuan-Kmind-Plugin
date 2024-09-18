# 思源笔记-kmind 插件
    xmind你不要打电话来了，我怕kmind误会

## QQ交流群号：130584086

## 在线反馈：[点我反馈](https://txc.qq.com/products/662653)

## 最近一次更新记录

### v2.2.0-plugin.1（2024年9月18日）

说明：

- 优化性能，更新捐赠单号说明


### v2.2.0（2024年9月17日）

说明：

- 中秋快乐~此为中秋特别版
- 加入了大家期待已久的付费功能 - -！付费指引[点我查看](https://siyuannote.space/x/20240917120223-roa3lpm)，以下有`(pro)`后缀的功能为付费功能
- 建议在PC端扫码付费，然后通过思源的云同步，将KMind付费状态同步到移动端，移动端同步后，重启一下移动端的思源即可。

新增：

- 新建导图的时候，侧边操作栏默认隐藏；
- 新增思源文档一键转KMind功能，功能查看以及说明[点我查看](https://siyuannote.site/x/20240917102811-jx1umib)（pro）
- 新增KMind镜像块功能，功能查看以及说明[点我查看](https://siyuannote.site/x/20240917094117-jeem5c6)（pro）

优化：

- 优化镜像块的性能

## 使用方式
1.在插件市场安装并启用后，在左下角找到kmind的dock，然后点击新建即可
![newKmind.gif](img%2FnewKmind.gif)

2.快捷键的说明详见插件菜单（挂件遇到此问题同理）
![shortcut.png](img%2Fshortcut.png)
## 反馈

如果你需要反馈，可以去我的github仓库提交[issue](https://github.com/suka233/siyuan-kmind-plugin/issues),如果你没有github账号，可以[点我反馈](https://wj.qq.com/s2/12591272/adf1/)。如果你要捐赠我，可以[点我](https://wj.qq.com/s2/12591272/adf1/)，
或者去我的github仓库给[本插件](https://github.com/suka233/siyuan-kmind-plugin/issues)点一颗star吧~

## 付费

kmind插件的基础编辑功能永久免费使用，不限制导图数量，也不限制节点数量。之后与思源或者外部结合的高级功能可能需要付费 ~~（目前此插件收益负50元，因为我向上游库的导图库作者捐赠了50元😋 ）~~~~，~~~~等到正式付费，各位的捐赠金额可以双倍抵扣kmind费用。~~

kmind pro版本已经上线，请在发布日前的捐赠过的用户输入自己的转账单号，即可自动计算抵扣金额，有任何疑问请qq群联系我：QQ交流群号：130584086

感谢各位的捐赠，时间有限，不能一一列出~。~ 主要是懒


## 缘起
思源笔记是一款我很喜欢的笔记软件，但是它的导图功能却不是很完善，而我恰好是思维导图重度使用者

一直以来都是用的xmind做笔记，规划生活等等，但是由于xmind比较贵，并且绑定设备，而且必须要使用xmind客户端才能打开，
拥有多台设备的我感觉很痛苦，并且在与其它软件或者生态的联动方面，xmind一直都迟迟不做改进。

所以我基于开源库开发了思源思维导图挂件：[kmind](https://github.com/suka233/siyuan-Kmind)。
后来，思源的目录插件作者[@TinkMingKing](https://github.com/TinkMingKing)建议我开发一个插件版思维导图，
我想想，确实，挂件版本的kmind由于只能插入到某篇具体的文档中，和单篇文档高度相关，无法覆盖所有的思维导图应用场景，所以这个插件就诞生啦~

高强度使用此插件半个多月的我突然发现，我已经好久没有打开过xmind了，所以，xmind你以后不要打电话来了，我怕kmind误会 :p

## kmind特点

1.随意导入 or 导出xmind文件，并且额外支持导出为图片、markdown、svg文件，以及通用的json文件，这也是我从xmind转为kmind的底气
![exportToXmind.gif](img%2FexportToXmind.gif)

2.现代化的设计：采用了蚂蚁的Ant Design UI组件库，界面简洁大方

3.高度可配置：支持自定义主题、结构、节点的字体、字号、并且可以配置新建导图的默认动作，比如新建一张kmind的时候，自动选择某个设定好的主题，自动开启禅模式等等
![changeStyle.gif](img%2FchangeStyle.gif)

4.富文本节点：目前市面上的思维导图的节点为普通的文本格式，富文本节点由于可以加粗指定文字，更改背景或者文字颜色，可以更好的突出重点

5.和思源笔记深度结合：如果把节点的超链接设置为思源的块超链接，点击即可跳转到思源笔记的指定块，如果按住Alt键点击，还可以直接在kmind中悬浮预览思源笔记的指定块
![kmindguide.gif](img%2Fkmindguide.gif)

6.开放性：得益于开源的力量，单个节点能承载的功能可以开发出更多玩法，比如：在节点中渲染出思源笔记指定的编辑区是什么样的体验？
![siyuanBlock.gif](img%2FsiyuanBlock.gif)

7.数据安全：kmind的所有数据全部存储于本地，并且与思源的笔记本数据完全隔离，也没有任何交互。所以不会对思源的数据造成任何影响。此外，kmind会在你编辑的时候，智能每隔1s自动保存数据到本地，意外断电也不怕丢失啦。


## 致谢

感谢[@wanglin2/mind-map](https://github.com/wanglin2/mind-map)大佬开发的导图库，没有他就没有本项目

感谢思源目录插件作者：[@TinkMingKing](https://github.com/TinkMingKing/siyuan-index-plugins) 大佬的提议与帮助

感谢顶栏日历插件作者：[@svchord](https://github.com/svchord/siyuan-arco-calendar) 大佬的vue模板参考

感谢开放API插件作者：[@Zuoqiu-Yingyi](https://github.com/Zuoqiu-Yingyi) 萌佬的插件参考与答疑，kmind挂件的悬浮预览脱胎于此

感谢插件系统的开拓者：[@zuoez02](https://github.com/zuoez02/siyuan-plugin-excalidraw) Z佬的[Excalidraw插件](https://github.com/zuoez02/siyuan-plugin-excalidraw)

和[@frostime](https://github.com/frostime)大佬的[文档流插件](https://github.com/frostime/sy-docs-flow)参考，抄了亿点点新建自定义tab页的写法，嘿嘿

## 以往更新记录

### v2.1.0（2024年9月4日）

说明：

- 跟KMind挂件更新保持一致。

新增：
- 更新图标ICON的视觉风格，入口：选择节点->图标->表情图标

修复：

- 加入缺少的14号字体

### v2.0.0-beta.1（2024年7月25日）

简介：插件重构，底层更新，与挂件解耦，无需安装挂件即可直接使用，更新了UI视觉风格，黑暗模式，大纲编辑等等一系列功能，更新了富文本编辑器，更好用了

修复：修复无法切换主题的bug [#39](https://github.com/suka233/siyuan-kmind-plugin/issues/39)

新增：

1.新增黑暗模式 & 主题 [#23](https://github.com/suka233/siyuan-kmind-plugin/issues/23)

2.导图样式支持调节概要，关联线的样式

3.支持导图的节点内边距，节点外边距，图片，图标

4.支持更换导图的背景颜色

5.添加了更多主题

6.添加了一个向左的逻辑结构

7.重构了大纲和搜索，支持比较简单的大纲编辑，全屏大纲编辑和大纲拖拽调整节点位置等等

8.左下角展示节点和字数

9.上方的按钮栏重构，更新视觉UI，适配黑暗模式和小屏幕模式（小屏幕将会自动折叠按钮）[#29](https://github.com/suka233/siyuan-kmind-plugin/issues/29)

10.右键菜单添加了一键去除样式，复制为md文档，txt文档，kmind数据，插入父节点，仅删除当前节点等等功能 [#25](https://github.com/suka233/siyuan-kmind-plugin/issues/25) [#12](https://github.com/suka233/siyuan-kmind-plugin/issues/12)

11.修复了节点内的字号（如标题）无法生效的bug

12.添加了编辑节点的时候的快捷富文本操作栏

13.其它的一些小优化，如右键菜单自动调整到可视区，操作栏按钮在分辨率低的屏幕上自动折叠，添加常用按钮到操作区域，方便触屏使用等等 [#18](https://github.com/suka233/siyuan-kmind-plugin/issues/18)

#### v1.1.7（2024年3月20日）

修复：

- 修复nginx反代思源笔记的时候，kmind插件可能无法正常使用的问题

#### v1.1.6（2024年2月18日）

修复：

- 修复思源v2.12.4版本更新导致的dock图标过大的bug


#### v1.1.5（2024年2月18日）

修复：

- 修复当有kmind tab页打开的时候，无法删除这张kmind的bug

#### v1.1.4

修复：
- 修复思源版本v2.10.9更新插件api导致无法打开tab页的bug，该版本可能无法在低于v2.10.9的思源版本中使用

新增：
- 复制kmind超链接的功能：现在，你可以复制一个kmind的超链接，然后在另一个kmind的节点上或者思源中或者其它任何地方粘贴，点击即可跳转到该kmind。

优化：
- 点击左下角dock栏的kmind文件列表，如果该kmind已经打开，则会自动跳转到已经打开的tab页
