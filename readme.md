[English readme](readme.md)

[中文说明](readme_cn.md)

# 1. Thanks go to amigos who helped me in killing the bug, implementing some functions

[falkoschindler](https://github.com/falkoschindler)、[rodja](https://github.com/rodja)、[thetableman](https://github.com/thetableman)、[CrystalWindSnake](https://github.com/CrystalWindSnake)

# 2. Now I have used [NiceGUI](https://nicegui.io/) in 2 projects which run on PC, and 1 project which runs in my brain


# 3. project 1: choice quiz training application
## 3.1 snap
### 3.1.1 logging page
3 regions, i.e. A for logging,  B for users' score, C for statistics

<img src="project1_quizmachine\登录页面.png" width=50%/>

### 3.1.2 answering page
different users have different quizs

  <table border="1">
   <tr>
    <td><img src="project1_quizmachine\宋江答题.png" width=80%/></td>
    <td><img src="project1_quizmachine\吴用答题.png" width=80%/></td>
   </tr>
  </table>


### 3.1.3 submitting page
scores can be found here, user can export page

<img src="project1_quizmachine\宋江提交.png" width=30%/>

## 3.2 features to be implemented/bug
These features can be implemented only if official [NiceGUI](https://nicegui.io/) supports them.
- living user camera image, which depends on [this feature](https://github.com/zauberzeug/nicegui/discussions/2010)
- more complex quiz with math formula, diagram. Although [NiceGUI](https://nicegui.io/) supplies [Markdown element](https://nicegui.io/documentation/section_text_elements#markdown_element)、[Mermaid element](https://nicegui.io/documentation/section_text_elements#mermaid_diagrams), I do hope there is an all-in-one Markdown elemenet which spares me distinguishing and treating whether it is a [Mermaid diagram](https://nicegui.io/documentation/section_text_elements#mermaid_diagrams) or [math expression](https://github.com/zauberzeug/nicegui/discussions/696)
- saving PDF by using username, which depends on [this feature](https://github.com/zauberzeug/nicegui/discussions/2140)



# 4. project 2: tell me your free time
## 4.1 snapshot
### 4.1.1 logging page
3 regions, i.e. A for logging,  B for result, C for statistics on logged users

<img src="project2_tellmeyourfreetime\登录页面.png" width=50%/>

### 4.1.2 answering page

<img src="project2_tellmeyourfreetime\选择页面.png" width=50%/>


## 4.2 features to be implemented/bug
- the buttons on logging page stops its animation immediately when a new button is clicked by any user. I don't know the reason and how to fix it

# 5. project 3：it only stays in my brain till now
