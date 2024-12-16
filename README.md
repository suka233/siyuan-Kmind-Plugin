# 思源笔记-kmind 插件

    xmind你不要打电话来了，我怕kmind误会

## QQ 交流群号：[130584086](https://qm.qq.com/cgi-bin/qm/qr?k=ViZ2ouiFw8LF5Zx1fg1SQUr1Y0bH1FAR&jump_from=webapi&authKey=UR61OGV1muKUgQZFTdBuxgdcXDWm2TLGisL5RZ9X6VYRY7NPM32L4ciyF426+qPF)

## 在线反馈：[点我反馈](https://txc.qq.com/products/662653)

## 最近一次更新记录

### [v2.6.1(2024年12月16日)](https://docs.kmind.app/changelog/kimind-v261-global-configuration-of-one-click-transition-map-1hoxvv.html)

#### 说明：新增思源文档一键转KMind的全局配置，可以配置转换后显示的主题，结构等等，去除了一些日志，优化性能，修复一些bug

![PixPin_2024-12-16_09-53-10](https://s2.loli.net/2024/12/16/FCg9cQDA5a3whjX.webp)


#### 新增：

### 1.思源文档一键转KMind的全局配置，现在可以自定义转换后的主题和结构


#### 修复：

### 1. 修复全局配置“左键拖拽右键选择”的文案错误

### 2. 修复一键转KMind时，导出会弹框两次的bug

### 3. 修复彩虹线条配置第二次保存失败的bug


#### 其它：

### 1. 更新导图保存逻辑，旧导图初次渲染，拦截首次的自动保存操作

### 2. 去除一些不必要的日志log，优化性能

### [v2.6.0(2024年11月29日)](https://docs.kmind.app/changelog/v260.html)

#### 说明：新增了全局配置功能，可以使用KMind插件设置全局导图的行为，包括文档树导图，dock栏导图，挂件导图。新增智能粘贴思源超链接为节点超链接

#### 新增：

##### 1.新增快速粘贴思源超链接为节点超链接的功能：

以往需要复制siyuan://开头的思源超链接，然后点击节点，点击超链接按钮，点击确认；

现在不需要这么麻烦啦！直接复制思源的超链接，然后选中节点，ctrl+v粘贴即可。

![PixPin_2024-11-29_12-32-13-20241129123225-hjodksn.gif](https://s2.loli.net/2024/11/29/TBXkVpu9iRgAOj2.gif)

##### 2. KMind全局配置，可以一键配置所有导图的默认行为，当前开放了：1.鼠标左键选择右键拖拽配置；2.打开导图的时候自动进入禅模式的配置；3.创建导图（包括文档树导图，dock栏导图，挂件导图）默认选择主题，选择默认结构（pro）

![PixPin_2024-11-29_12-34-00-20241129123433-atg13d5.gif](https://s2.loli.net/2024/11/29/LEmsFr2i9cJHCUe.gif)

#### 优化：

##### 1. 去除底部工具栏切换语言下拉，自动适配思源i18n

##### 2.优化一些性能问题，修复一些不影响功能的报错log，优化批量格式刷性能

#### 其它：

以上标注为pro的功能为本版本限免，无需付费即可使用 ：P



### [2.5.0（2024年11月11日）](https://siyuannote.space/x/20241111153508-dx2yrwp)

说明：新增数据兜底保护策略，保存的时候会拦截异常数据的写入；新增历史记录功能；最大化保护数据

新增：
- 历史记录功能，文档树导图，dock栏导图和挂件导图均可用。功能说明，会在数据变动的时候，自动每隔6分钟保存一份历史记录，基于存储空间的考量，目前最多保存3份，旧的会被自动删除：
- kmind概览功能：可以在全局配置里查看当前工作空间的导图数量（pro）
- 一键为已存在的导图创建固定历史版本功能（pro）（使用此功能创建的历史版本不会自动清理，可以手动删除）
- 新增保存数据的时候的兜底保护策略，自动拦截异常数据的写入，避免潜在的导图数据丢失风险

优化：
- 去除一些非必要的console，优化性能

其它：
- 以上标注为pro的功能为本版本限免，无需付费即可使用，将在月底的涨价版本发布后取消限免 ：P

### 2.4.3（2024 年 10 月 29 日）

说明：更新底层库，带来了拖拽调整节点大小，原地编辑等效果，新增节点思源子文档快捷打开位置悬浮按钮

新增：

- 新增拖拽调整节点大小
- 新增节点子文档快捷指定打开位置的悬浮按钮

优化：

- 编辑默认为原地编辑效果

### 2.4.2（2024 年 10 月 8 日）

修复：

- 修复了非思源超链接类型的超链接无法正常跳转的 bug
- 修复部分设备激活状态无法保存的 bug

新增：

- 新增根据订单号找回激活码功能

### 2.4.1-plugin.1（2024 年 10 月 6 日）

说明：

- 更新插件适配思源版本说明，请更新思源版本到 3.1.8 及以上后使用本插件

### [v2.4.0（2024 年 10 月 5 日）](https://siyuannote.site/x/20241005113503-s68860l)

说明：

- 新增了直接在思源文档树中创建 KMind 文档的能力，新增节点右击创建思源节点子文档，以适配 MOC 流程~

新增：

- 现在可以直接在思源文档树中创建 KMind 文档，操作方法：右键文档树 -> 插件 -> KMind -> 创建 KMind 文档（pro）
- 新增节点直接创建关联思源文档功能；操作方法：选中节点 -> 右键节点 -> 点击 ‘节点子文档’（pro）

优化 & 修复：

- 优化 KMind 中对思源超链接的处理，现在无论是移动端，docker 端，还是 PC 端，都能在思源内部正确的跳转到指定的思源块，不会出现 docker 端点击超链接，会拉起本机 PC 端的情况了
- 修复挂件初次渲染的时候，没有自动进入禅模式的 bug
- 优化 KMind 在移动端的展示效果，目前仅可查看不可编辑，编辑请在 PC 端进行

缺陷：

- 由于 KMind 的源文件保存粒度是整个文档保存，所以请不要在同一时空同时打开同一张 KMind 导图！否则会出现数据相互覆盖的情况，包括的危险操作如下：
  - 多端打开同一张导图（是的，同时打开也会导致冲突，因为 KMind 还会存储视图数据到源文件中，一旦你打开了拖拽查看了的话，视图数据就会更新，这个时候，多端的数据就会不一致了）
  - 向右 or 向下 分屏操作同一张导图
  - 其它同时打开同一张导图的情况...
- 打开文档树中的 KMind 文档的时候，如果第一个 KMind 文档没有加载完毕就切换到第二个 KMind 文档，那么第一个 KMind 文档会一直加载不了，这个时候重新开关一下第一个 KMind 文档就行了（数据是安全的，不会丢失）
- 由于上面提到的原因，移动端目前仅开启查看功能

### [v2.3.1（2024 年 9 月 29 日）](https://ld246.com/article/1727602784074)

说明：

- 优化了挂件的使用方式，优化了挂件和镜像块蒙版的展示效果，优化底部工具栏的展示位置

新增：

- 新增了挂件的快捷穿透蒙版功能：按住 ctrl 键+左键单击节点，可以快速聚焦节点，直接进行编辑
- 底部工具栏新增禅模式按钮，现在移动端不必调出右键菜单就能直接进入禅模式了
- 新增了镜像块的一键跳转编辑功能，点击镜像块的右上角，即可跳转到源导图进行编辑（pro）

优化：

- 优化了挂件和镜像块蒙版的展示效果，现在只有鼠标划上去，才会展示蒙版提示
- 优化底部工具栏的位置，现在会随着侧栏的展开而动态更改位置了，避免被覆盖

### v2.3.0（2024 年 9 月 21 日）

说明：

- 优化了镜像块的使用手感，镜像块，一键转 kmind，插件导图自适应思源黑暗模式，并同步了上游库的一些功能与更新

新增：

- UI 界面自动适配思源的黑暗模式
- 导出水印自定义
- 思源文档一键转 KMind 功能新增解析图片；（pro）
- 备注：技术限制，图片大小默认强制为 100\*100，双击节点即可自动调整
- 思源文档一键转 KMind 功能自适应黑暗模式；（pro）
- 镜像块新增蒙版：防止误操作 & 捕获思源笔记页面滚轮；（pro）

其它：

- 去除一些日志输出，优化性能

### v2.2.0-plugin.1（2024 年 9 月 18 日）

说明：

- 优化性能，更新捐赠单号说明

### v2.2.0（2024 年 9 月 17 日）

说明：

- 中秋快乐~此为中秋特别版
- 加入了大家期待已久的付费功能 - -！付费指引[点我查看](https://siyuannote.space/x/20240917120223-roa3lpm)，以下有 `(pro)`后缀的功能为付费功能
- 建议在 PC 端扫码付费，然后通过思源的云同步，将 KMind 付费状态同步到移动端，移动端同步后，重启一下移动端的思源即可。

新增：

- 新建导图的时候，侧边操作栏默认隐藏；
- 新增思源文档一键转 KMind 功能，功能查看以及说明[点我查看](https://siyuannote.site/x/20240917102811-jx1umib)（pro）
- 新增 KMind 镜像块功能，功能查看以及说明[点我查看](https://siyuannote.site/x/20240917094117-jeem5c6)（pro）

优化：

- 优化镜像块的性能

## 使用方式

1.在插件市场安装并启用后，在左下角找到 kmind 的 dock，然后点击新建即可
![newKmind.gif](img%2FnewKmind.gif)

2.快捷键的说明详见插件菜单（挂件遇到此问题同理）
![shortcut.png](img%2Fshortcut.png)

## 反馈

如果你需要反馈，可以去我的 github 仓库提交[issue](https://github.com/suka233/siyuan-kmind-plugin/issues),如果你没有 github 账号，可以[点我反馈](https://txc.qq.com/products/662653)。如果你要捐赠我，可以[点我](https://wj.qq.com/s2/12591272/adf1/)，
或者去我的 github 仓库给[本插件](https://github.com/suka233/siyuan-kmind-plugin/issues)点一颗 star 吧~

## 付费

kmind 插件的基础编辑功能永久免费使用，不限制导图数量，也不限制节点数量。~~之后与思源或者外部结合的高级功能可能需要付费 （目前此插件收益负 50 元，因为我向上游库的导图库作者捐赠了 50 元 😋 ），等到正式付费，各位的捐赠金额可以双倍抵扣 kmind 费用。~~

kmind pro 版本已经上线，不会影响免费版使用，只是多了两个跟思源结合的 pro 功能。请在发布日前的捐赠过的用户输入自己的转账单号，即可自动计算抵扣金额，注意，由于微信捐赠码设计原因（付款方转账单号和收款方转账单号不一致），所以请先加 qq 群私聊我你的转账单号。。！
有任何疑问请 qq 群联系我：QQ 交流群号：[130584086](https://qm.qq.com/cgi-bin/qm/qr?k=ViZ2ouiFw8LF5Zx1fg1SQUr1Y0bH1FAR&jump_from=webapi&authKey=UR61OGV1muKUgQZFTdBuxgdcXDWm2TLGisL5RZ9X6VYRY7NPM32L4ciyF426+qPF)

感谢各位的捐赠，时间有限，不能一一列出~。~ 主要是懒

## 缘起

思源笔记是一款我很喜欢的笔记软件，但是它的导图功能却不是很完善，而我恰好是思维导图重度使用者

一直以来都是用的 xmind 做笔记，规划生活等等，但是由于 xmind 比较贵，并且绑定设备，而且必须要使用 xmind 客户端才能打开，
拥有多台设备的我感觉很痛苦，并且在与其它软件或者生态的联动方面，xmind 一直都迟迟不做改进。

所以我基于开源库开发了思源思维导图挂件：[kmind](https://github.com/suka233/siyuan-Kmind)。
后来，思源的目录插件作者[@TinkMingKing](https://github.com/TinkMingKing)建议我开发一个插件版思维导图，
我想想，确实，挂件版本的 kmind 由于只能插入到某篇具体的文档中，和单篇文档高度相关，无法覆盖所有的思维导图应用场景，所以这个插件就诞生啦~

高强度使用此插件半个多月的我突然发现，我已经好久没有打开过 xmind 了，所以，xmind 你以后不要打电话来了，我怕 kmind 误会 :p

## kmind 特点

1.随意导入 or 导出 xmind 文件，并且额外支持导出为图片、markdown、svg 文件，以及通用的 json 文件，这也是我从 xmind 转为 kmind 的底气
![exportToXmind.gif](img%2FexportToXmind.gif)

2.现代化的设计：采用了蚂蚁的 Ant Design UI 组件库，界面简洁大方

3.高度可配置：支持自定义主题、结构、节点的字体、字号、并且可以配置新建导图的默认动作，比如新建一张 kmind 的时候，自动选择某个设定好的主题，自动开启禅模式等等
![changeStyle.gif](img%2FchangeStyle.gif)

4.富文本节点：目前市面上的思维导图的节点为普通的文本格式，富文本节点由于可以加粗指定文字，更改背景或者文字颜色，可以更好的突出重点

5.和思源笔记深度结合：如果把节点的超链接设置为思源的块超链接，点击即可跳转到思源笔记的指定块，如果按住 Alt 键点击，还可以直接在 kmind 中悬浮预览思源笔记的指定块
![kmindguide.gif](img%2Fkmindguide.gif)

6.开放性：得益于开源的力量，单个节点能承载的功能可以开发出更多玩法，比如：在节点中渲染出思源笔记指定的编辑区是什么样的体验？
![siyuanBlock.gif](img%2FsiyuanBlock.gif)

7.数据安全：kmind 的所有数据全部存储于本地，并且与思源的笔记本数据完全隔离，也没有任何交互。所以不会对思源的数据造成任何影响。此外，kmind 会在你编辑的时候，智能每隔 1s 自动保存数据到本地，意外断电也不怕丢失啦。

## 致谢

感谢[@wanglin2/mind-map](https://github.com/wanglin2/mind-map)大佬开发的导图库，没有他就没有本项目，如果您对导图的功能满意，请考虑直接[捐赠他](https://wanglin2.github.io/mind-map-docs/sponsor.html)

感谢思源目录插件作者：[@TinkMingKing](https://github.com/TinkMingKing/siyuan-index-plugins) 大佬的提议与帮助

感谢顶栏日历插件作者：[@svchord](https://github.com/svchord/siyuan-arco-calendar) 大佬的 vue 模板参考

感谢开放 API 插件作者：[@Zuoqiu-Yingyi](https://github.com/Zuoqiu-Yingyi) 萌佬的插件参考与答疑，kmind 挂件的悬浮预览脱胎于此

感谢插件系统的开拓者：[@zuoez02](https://github.com/zuoez02/siyuan-plugin-excalidraw) Z 佬的[Excalidraw 插件](https://github.com/zuoez02/siyuan-plugin-excalidraw)

和[@frostime](https://github.com/frostime)大佬的[文档流插件](https://github.com/frostime/sy-docs-flow)参考，抄了亿点点新建自定义 tab 页的写法，嘿嘿

## 以往更新记录

### v2.1.0（2024 年 9 月 4 日）

说明：

- 跟 KMind 挂件更新保持一致。

新增：

- 更新图标 ICON 的视觉风格，入口：选择节点->图标->表情图标

修复：

- 加入缺少的 14 号字体

### v2.0.0-beta.1（2024 年 7 月 25 日）

简介：插件重构，底层更新，与挂件解耦，无需安装挂件即可直接使用，更新了 UI 视觉风格，黑暗模式，大纲编辑等等一系列功能，更新了富文本编辑器，更好用了

修复：修复无法切换主题的 bug [#39](https://github.com/suka233/siyuan-kmind-plugin/issues/39)

新增：

1.新增黑暗模式 & 主题 [#23](https://github.com/suka233/siyuan-kmind-plugin/issues/23)

2.导图样式支持调节概要，关联线的样式

3.支持导图的节点内边距，节点外边距，图片，图标

4.支持更换导图的背景颜色

5.添加了更多主题

6.添加了一个向左的逻辑结构

7.重构了大纲和搜索，支持比较简单的大纲编辑，全屏大纲编辑和大纲拖拽调整节点位置等等

8.左下角展示节点和字数

9.上方的按钮栏重构，更新视觉 UI，适配黑暗模式和小屏幕模式（小屏幕将会自动折叠按钮）[#29](https://github.com/suka233/siyuan-kmind-plugin/issues/29)

10.右键菜单添加了一键去除样式，复制为 md 文档，txt 文档，kmind 数据，插入父节点，仅删除当前节点等等功能 [#25](https://github.com/suka233/siyuan-kmind-plugin/issues/25) [#12](https://github.com/suka233/siyuan-kmind-plugin/issues/12)

11.修复了节点内的字号（如标题）无法生效的 bug

12.添加了编辑节点的时候的快捷富文本操作栏

13.其它的一些小优化，如右键菜单自动调整到可视区，操作栏按钮在分辨率低的屏幕上自动折叠，添加常用按钮到操作区域，方便触屏使用等等 [#18](https://github.com/suka233/siyuan-kmind-plugin/issues/18)

#### v1.1.7（2024 年 3 月 20 日）

修复：

- 修复 nginx 反代思源笔记的时候，kmind 插件可能无法正常使用的问题

#### v1.1.6（2024 年 2 月 18 日）

修复：

- 修复思源 v2.12.4 版本更新导致的 dock 图标过大的 bug

#### v1.1.5（2024 年 2 月 18 日）

修复：

- 修复当有 kmind tab 页打开的时候，无法删除这张 kmind 的 bug

#### v1.1.4

修复：

- 修复思源版本 v2.10.9 更新插件 api 导致无法打开 tab 页的 bug，该版本可能无法在低于 v2.10.9 的思源版本中使用

新增：

- 复制 kmind 超链接的功能：现在，你可以复制一个 kmind 的超链接，然后在另一个 kmind 的节点上或者思源中或者其它任何地方粘贴，点击即可跳转到该 kmind。

优化：

- 点击左下角 dock 栏的 kmind 文件列表，如果该 kmind 已经打开，则会自动跳转到已经打开的 tab 页
