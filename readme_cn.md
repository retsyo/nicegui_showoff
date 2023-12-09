[English readme](readme.md)

[中文说明](readme_cn.md)

# 1. 首先，感谢帮我干掉bug、实现特定功能的朋友，特别是
[falkoschindler](https://github.com/falkoschindler)、[rodja](https://github.com/rodja)、[thetableman](https://github.com/thetableman)、[CrystalWindSnake](https://github.com/CrystalWindSnake)

# 2. 目前我用[NiceGUI](https://nicegui.io/)实现了2个可以在电脑上跑的项目、1个还在人脑中跑的项目


# 3. 项目1：选择题测试机
## 3.1 截图
### 3.1.1 登陆页面
3个区域，分别是：A登录区域、B各用户得分区域、C各分数段统计区域

<img src="project1_quizmachine\登录页面.png" width=50%/>

### 3.1.2 答题页面
可以看到，不同用户的题目是不一样的

  <table border="1">
   <tr>
    <td><img src="project1_quizmachine\宋江答题.png" width=80%/></td>
    <td><img src="project1_quizmachine\吴用答题.png" width=80%/></td>
   </tr>
  </table>


### 3.1.3 提交页面
可以看到得分、可以导出页面

<img src="project1_quizmachine\宋江提交.png" width=30%/>

## 3.2 待实现/改善功能
这些功能的实现，超过了我的能力范围，主要得依靠[NiceGUI](https://nicegui.io/)官方了。
- 添加用户实时头像。这依赖于[解决这个问题](https://github.com/zauberzeug/nicegui/discussions/2010)
- 更复杂的题目，例如包含数学公式、流程图。是的，我知道[NiceGUI](https://nicegui.io/)提供了单独的[Markdown组件](https://nicegui.io/documentation/section_text_elements#markdown_element)、[Mermaid组件](https://nicegui.io/documentation/section_text_elements#mermaid_diagrams)，但是我希望能够有一个全家桶的Markdown组件，让我不需要区分里面哪里是[Mermaid图](https://nicegui.io/documentation/section_text_elements#mermaid_diagrams)、哪里是[数学公式](https://github.com/zauberzeug/nicegui/discussions/696)
- 按用户信息导出PDF。这依赖于[解决这个问题](https://github.com/zauberzeug/nicegui/discussions/2140)

## 3.3 考虑中的功能

懒得写


# 4. 项目2：空闲时间调查工具
## 4.1 截图
### 4.1.1 登录页面
3个区域，分别是：登录区域A、统计区域B、各用户登录情况区域C

<img src="project2_tellmeyourfreetime\登录页面.png" width=50%/>

### 4.1.2 选择页面

<img src="project2_tellmeyourfreetime\选择页面.png" width=50%/>


## 4.2 待实现/改善功能
- 原计划每个用户每次选择时，对应的按钮跳动几秒。但是现在有其它选择之后，原有动画立马停止。原因及改进方法，暂时未知

## 4.3 考虑中的功能

懒得写

# 5. 项目3：暂时还只在人脑中运行，先不说了