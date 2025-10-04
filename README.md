# SvgPathEditor (SVG路径代码编辑器)
在浏览器中创建或编辑 SVG 路径代码: https://yhdsl.github.io/svg-path-editor/ (汉化版) 或 https://yqnn.github.io/svg-path-editor/ (原版)
![Yaktocat 图像](./doc/screenshot.png)

---

## 关于此中文项目

[SvgPathEditor](https://github.com/Yqnn/svg-path-editor) 是一个界面友好，
允许快速直观创建或编辑 SVG 路径代码的项目

但由于 SvgPathEditor 项目并不支持 i18n，
我手动修改了项目内硬编码的文本，
将前端页面更改为了中文页面

---

## 如何使用

##### 基础:
- 在 **路径代码** 区域粘贴或编辑原始路径代码
- 点击 **+** 按钮添加新的命令、选择命令类型，然后点击目标坐标
- 通过拖放移动路径
- 点击目标坐标点，然后点击 **...** 按钮立即插入新命令、删除当前命令或者更改命令类型

##### 命令面板:
- 点击命令类型图标可在相对坐标类型和绝对坐标类型之间切换
- 相对坐标类型命令颜色为 **橙色**，而绝对坐标类型命令颜色为 **紫色**
- 点击 **...** 按钮并继续点击 **删除** 按钮即可删除所选命令
- 点击 **...** 按钮并继续点击 **插入** 按钮即可在所选命令之后插入新命令
- 点击 **...** 按钮并继续点击 **转换为** 按钮即可将所选命令转换为新类型
- 点击 **...** 按钮并继续点击 **从此开始** 按钮即可重新排序路径，使得当前所选命令位于第一个
- 点击 **...** 按钮并继续点击 **从此开始子路径** 按钮即可重新排序路径，使得当前所选命令位于子路径中的第一个
- 点击 **...** 按钮并继续点击 **翻转子路径** 按钮即可逆序排序整个子路径代码

##### 视图:
- 使用鼠标滚轮，或者点击 **放大** 和 **缩小** 按钮来放大/缩小视图
- 使用拖放操作来移动视图
- 点击 **自适应缩放** 按钮以根据路径代码自动调节视图大小
- 还可以根据 **x**， **y**， **宽度** 和 **高度** 字段手动调节视图

##### 路径操作:
- 使用 **缩放** 按钮缩放整个路径代码
- 使用 **平移** 按钮平移整个路径代码
- 使用 **旋转** 按钮旋转整个路径代码
- 使用 **四舍五入** 按钮舍入整个路径代码中的数值
- 使用 **转换为相对路径** 或 **转换为绝对路径** 按钮将全部命令转换为绝对类型或相对类型
- 使用 **翻转命令** 按钮逆序排序整个路径代码
- 使用 **代码优化** 按钮优化整个路径代码

##### 快捷键:
- 按下 **m**， **l**， **v**， **h**， **c**， **s**， **q**， **t**， **a** 或 **z** 以便在所选命令后快速插入指定的新命令
- 按下 **shift** + **m**， **l**， **v**， **h**， **c**， **s**， **q**， **t**， **a** 或 **z** 以便将所选命令转换为新类型
- 按下 **escape** 以删除正在创建的新命令，或者取消正在进行的移动操作
- 按下 **delete** 或 **backspace** 以删除所选命令
- 按下 **ctrl** + **z** 或 **cmd** + **z** 以撤销
- 按下 **ctrl** + **shift** + **z** 或 **cmd** + **shift** + **z** 以恢复
- 移动时按下 **ctrl** 以忽略 `与网格对齐` 约束

## 库

原项目的核心功能现在可以做为独立的库使用： [`svg-path-editor-lib`](https://www.npmjs.com/package/svg-path-editor-lib).

## 在本地运行

### 使用 Node.js

##### 前置需求
- [Node.js](https://nodejs.org/) v18.13 或更高的版本。

##### 安装依赖
运行 `npm install` 以检索并安装该项目的全部依赖项。

##### 开发服务器
运行 `npm start` 启动开发服务器。导航至 `http://localhost:4200/` 。如果你修改了任何源代码，网页会自动重新加载。

##### 构建
运行 `npm run build` 以构建该项目。构建生成的文件将储存至 `dist/` 文件夹内。

##### 运行单元测试
运行 `npm test` 以通过 [Karma](https://karma-runner.github.io) 运行单元测试。

## 特别感谢
非常感谢原项目的赞助商 🙇 !

[@riovir](https://github.com/riovir), [@miniBill](https://github.com/miniBill), [@GitHub](https://github.com/GitHub), [@alexandernst](https://github.com/alexandernst), [@Filimoa](https://github.com/Filimoa), [@agrogers](https://github.com/agrogers), [@MilesTails01](https://github.com/MilesTails01), [@robetus](https://github.com/robetus), [@adcar](https://github.com/adcar), [@getsentry](https://github.com/getsentry), [@simplicitywebdesign](https://github.com/simplicitywebdesign) 😎, [@PassPilot](https://github.com/PassPilot), [@zeroin](https://github.com/zeroin), [@jholmes-dev](https://github.com/jholmes-dev), [@sh-csg](https://github.com/sh-csg), [@MarcoRudin](https://github.com/MarcoRudin), [@Oddpod](https://github.com/Oddpod), [@roboflow](https://github.com/roboflow), [@lasaldan](https://github.com/lasaldan), [@stevekerrick](https://github.com/stevekerrick), [@toth-istvan-zoltan](https://github.com/toth-istvan-zoltan), [@PBI-DataVizzle](https://github.com/PBI-DataVizzle), [@gucr](https://github.com/gucr), [@Guiorgy](https://github.com/Guiorgy), [@LeaVerou](https://github.com/LeaVerou)
