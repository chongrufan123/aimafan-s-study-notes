---
title: emacs笔记
author: FAN Chongru
email: chongrufan@nuaa.edu.cn
---

# 一些基本操作
| 操作                   | 作用                               |
|------------------------|------------------------------------|
| c-n                    | 下一行                             |
| c-p                    | 前一行                             |
| c-f                    | 前一个字符                         |
| c-b                    | 后一个字符                         |
| c-k                    | 从光标位置到末尾删掉               |
| c-a                    | 回到行首                           |
| c-e                    | 去到行尾                           |
| m-<                    | 回到编辑区域最开始的位置           |
| m->                    | 去到编辑区域最后的位置             |
| c-v                    | 向下翻一屏                         |
| m-v                    | 向上翻一屏                         |
| m-f                    | 后一个单词                         |
| m-b                    | 前一个单词                         |
| m-a                    | 句子的最前面                       |
| m-e                    | 句子的最后面                       |
| c-l                    | 将光标显示到屏幕中央               |
| c-l c-l                | 光标显示到屏幕上方                 |
| c-u                    | 之后加数字                         |
| c-g                    | 终止emacs命令                      |
| c-x 1                  | 只保留当前窗格                     |
| c-x 2                  | 上下分屏                           |
| c-x 3                  | 左右分屏                           |
| c-d                    | 删除前一个字符                     |
| m-k                    | 删除到句尾的字符                   |
| c-@                    | 高亮显示                           |
| c-y                    | 修改召回                           |
| m-y                    | 跟在c-y之后,可以召回历史           |
| c-/                    | 撤销                               |
| c-x c-f                | 寻找一个文件                       |
| c-x c-s                | 保存                               |
| c-x c-b                | 列出缓存区                         |
| c-x b 缓存区文件名字   | 去缓存区的文件                     |
| c-x s                  | 保存多个缓存区                     |
| m-x                    | 命令名拓展                         |
| c-z                    | 挂起                               |
| fg/%emacs              | 回到emacs                          |
| c-x f                  | 设置最长一行的字符数               |
| c-s                    | 向前搜索                           |
| c-r                    | 向后搜索                           |
| c-m-v                  | 另一个窗口向下切屏                 |
| c-m-s-v                | 另一个窗口向上切屏                 |
| c-x o                  | 切换窗口                           |
| m-w                    | 复制                               |
| 左shift-w              | 剪切                               |
| c-y                    | 粘贴                               |
| c-x 左shift-e          | 执行                               |
| M-%                    | 替换                               |
| c-t                    | 光标前和光标所在两个字符替换       |
| m-t                    | 将光标前的单词和光标所在的单词替换 |
| m-=                    | 字符统计                           |
| c-x k                  | 杀死当前buffer                     |
| 在buffer选择界面中     |                                    |
| d                      | 标记删除                           |
| u                      | 取消当前行标记                     |
| U                      | 取消全部标记                       |
| x                      | 执行操作                           |
| ?                      | 查看帮助                           |
| c-x 0                  | 关闭当前分屏                       |
| c-x ^                  | 增加高度                           |
| c-x {                  | 减少宽度                           |
| c-x }                  | 增加宽度                           |
| m-o                    | 切换屏幕                           |
| 在切换屏幕中的一些功能 |                                    |
| x                      | 删除窗口                           |
| m                      | 移动窗口                           |

## markdown-mode
| 命令                             | 作用                                               |
|----------------------------------|----------------------------------------------------|
| c-c c-a                          | 插入超链接,打开插入链接界面                        |
| 下面是这些链接的后面的字母的意义 |                                                    |
| l                                | 插入链接,分别输入url,名称和标题                    |
| u                                | 插入一个纯url链接,只显示链接                       |
| f                                | 插入一个脚注,并在下方插入脚注文本,就是类似注释一样 |
| w                                | 插入一个wiki链接                                   |
|                                  |                                                    |
| c-c c-i                          | 插入图片                                           |
| c-c c-s                          | 插入样式                                           |
| 下面是这些链接的后面的字母的意义 |                                                    |
| e                                | 插入斜体                                           |
| s                                | 插入删除线                                         |
| c                                | 标记代码标签                                       |
| k                                | 加入kbd标记,表示是从键盘输入的                     |
| b                                | 加一个块引用                                       |
| p                                | 缩进                                               |
| l                                | 插入链接                                           |
| t                                | 插入表格                                           |
| h                                | 加入二级目录和分割线                               |
| F                                | 加入可以收缩的东西                                 |
| C                                | 插入大块的编程语言,可以自己选择语言                |
| q                                | 加入引用                                           |
| 数字                             | 加入几级标题                                       |
| c-c -                            | 插入分割线,前面可以跟数字                          |
| \!                               | 插入一级标题和分隔符                               |
| c-c c-o                          | 打开光标所在链接                                   |

## org mode相关内容 
- 基本
  - \*后面可以跟一个清单,\*后面可以跟很多个\*\*
  - s+右 加一个todo或done标签
  - c-c . 激活的标签
  - c-c ! 非激活的标签
  - \-\- 时间区间
- 三个状态
  - c-c c-s schedule
  - c-c c-d deadline 
  - closed 要在开头加*+STARTUP: logdone
  - c-c c-c 添加tag 可以在文件开头添加*+TAGS: 小王(w)
- 不同的显示样式
  有三种大纲显示模式模式,又分为两种不同的状态
  - 子项
    - FOLDED 折叠,全部折叠进来
    - CHILDREN 只是释放一级
    - SUBTREE 全部释放
    TAB可以切换,S-TAB可以调用全局显示状态
  - 全局
    - overview 概览
    - CONTENTS 目次
    - SHOW ALL 全部显示
    可以在键入S-TAB在这三种模式切换,C-u C-u C-u TAB直接切换到全局  
    org-startup-folded 是设置打开org之后默认显示状态,默认是概览  
    如果针对单独文件设置,在最开始加
    ```org
    *+STAARTUP: overview
    可选有
    content
    overview
    shwoall
    ```
- 移动相关
  | 命令    | 作用           |
  |---------|----------------|
  | C-c C-n | 下一个标题     |
  | C-c C-p | 上一个标题     |
  | C-c C-f | 下一个同级标题 |
  | C-c C-b | 上一个同级标题 |
  | C-c C-u | 跳转到父级目录 |
- 结构编辑  
  | 命令         | 作用                           |
  |--------------|--------------------------------|
  | M-RET        | 创建同级别标题                 |
  | M-S-RET      | 创建同级别todo条目             |
  | TAB          | 循环改变未指定标题名的标题等级 |
  | M-LEFT/RIGHT | 将当前标题升级或降级           |
  | M-UP/DOWN    | 上下交换同级别                 |
  | C-c C-w      | 将当前条目放置到指定条目       |
  | C-x n s/w    | 将当前子项为单位变宽或变窄     |
- 清单列表
  - ::指定列表的说明,将条目和说明隔开  
    | 命令        | 作用                   |
    |-------------+------------------------|
    | TAB         | 类似与标题的折叠       |
    | M-RET       | 创建同级项目           |
    | M-S-RET     | 新建带有复选框的同级项 |
    | M-S-UP/DOWN | 上下移动当前项         |
    | C-c C-c     | 勾选复选框             |
    | C-c _       | 循环修改当前项目条目   |
- 表格
  | 命令                 | 作用                         |            |
  |----------------------|------------------------------|------------|
  | \                    | - TAB                        | 创建分割符 |
  | 创建第一行之后按TAB  | 创建表格                     |            |
  | C-c C-c              | 重新对齐表格                 |            |
  | TAB                  | 移动到下一个单元格           |            |
  | S-TAB                | 移动到上一个单元格           |            |
  | S-UP/DOWN/LEFT/RIGHT | 交换单元格为上下左右的单元格 |            |
  | M-LEFT/RIGHT         | 交换左右的列                 |            |
  | M-S-LEFT             | 删除当前列                   |            |
  | M-S-RIGHT            | 向右插入新列                 |            |
  | M-UP/DOWN            | 上下移动当前列               |            |
  | M-S-UP               | 删除当前行                   |            |
  | M-S-DOWN             | 在当前行上方插入新行         |            |
  | C-c -                | 在当前行上加入分割线         |            |
  | C-c RET              | 在当前行下方加入分割线       |            |
  | C-x ^                | 根据当前列给表格排序         |            |
- 超链接
  ```org
  两种定义方式
    带说明的超链接
    [[https://www.baidu.com][百度]]
    不带说明的超链接
    [[https://www.baidu.com]]
  链接方式
    内部链接  
    可以链接到当前文章某处  
    [[MY Target][目标]]  
    被链接处加上符号  
    <<MY Target>>
    外部链接
    可以指定行号
    [[file:~/.emacs.d/init.el::15][打开init.el的第15行]]
    指定特殊目标
    [[file:~/.emacs.d/test.el::Teat Target][打开test.el的Test Target标记]]
  ```
  - 处理超链接
    | 命令    | 作用                               |
    |---------|------------------------------------|
    | C-c C-l | 插入链接                           |
    | C-c C-l | 当光标在一个超链接上面时编辑超链接 |
    | C-c C-o | 打开超链接                         |
    | C-c l   | 储存当前位置是超链接               |
- 角注标记
  - 添加角注链接

- 图片
  - 创建图片
    ```org
    [[file:~/a.png]]
    ```
  - 用C-c C-x C-v 的方式让图片显示出来

    [[file:~/a.png][图片]]

- 字体
  | 符号  | 描述   | 展示     |
  |-------|--------|----------|
  | 两边* | 粗体   | *粗体*   |
  | 两边/ | 斜体   | /斜体/   |
  | 两边+ | 删除线 | +删除线+ |
  | 两边_ | 下划线 | _下划线_    |

- 导出和发布
  - 自带导出功能

    导出时数据设置
    ```org
    #+TITLE:
    #+AUTHOR:
    #+EMAIL:
    #+KEYWORDS:
    ```
  - 导出为markdown
    M-x org-md-export-as-markdown
- 区块
  - 居中区块CENTER

    #+begin_center
    大卫奖
阿对外交流
    #+end_center
  - 例子EXAMPLE

    #+begin_example
    这是一个例子
    #+end_example
  - 注释COMMENT

    #+begin_center
    大卫的理解
    达到节能
    #+end_center
  - HTML区块HTML

    #+begin_export html
    嵌入的
    #+end_export

- 代办事项
  - 基础

    当标题开头是todo时,该标题就会成为一个代办事项
    
    
  - 按键
  
  | 按键      | 作用           |
  |-----------|----------------|
  | C-c C-t   | 选择代办状态   |
  | C-c ,     | 选择优先级     |
  | S-UP/DOWN | 提升降低优先级 |
  | [/]或[%]     | 显示进度       |
  | C-c C-c   | 刷新进度       |

- 标签 

  在标题后由两个冒号包住的单词  

  子标题的标签可以继承父标题的标签  

  也可以在文件开头写下面这段话,让当前文件的所有标签继承与他

  ```org
  *+FILETAGS: :EvanMeek:
  ```
  
  在文件开头指定该文件的标签
  ```org
  *+TAGS: @work(w) @home(h)
  ```

  - 标签组

  用[]之间的就是多选的标签

  在{}之间的就是单选的标签

  
  - 按键
| 按键    | 作用                              |
|---------|-----------------------------------|
| C-c C-q | 为当前标题创建新的标签            |
| C-c C-c | 同上,不过只有光标在标签上面才有效 |

- 属性
  属性是包含在

  ```org
  :PROPERTIES:...
  ```
  之间的

  - 按键
  
  | 按键      | 作用         |
  |-----------|--------------|
  | C-c C-x p | 设置属性     |
  | C-c C-c d | 删除当前属性 |

- 时间和日期
  - 时间缀
    - 基本时间缀
      ```org
      <2020-05-19 一>
      ```
      
    - 有规律的时间缀
      ```org
      <2020-05-19 一 +1y>
      ```

      每年都会提醒

    - 日记样式的时间厝

    - 时间日期范围

      两个时间厝之间用--连接

    - 非活动时间错
    ```org
    [2020-05-18 一]
    ```
    不会被agenda管理

  - 创建时间错
    - 键位
| 键位         | 作用                   |
|--------------|------------------------|
| C-c .        | 插入时间厝             |
| C-c !        | 插入非活动时间厝       |
| S-LEFT/RIGHT | 将时间厝提前或后退一天 |
| S-UP/DOWN    | 支持对年月日周等变换   |
| C-c C-d      | 插入截止时间错         |
| C-c C-s      | 插入开始时间厝         |
| C-c C-x C-i  | 开始为当前代办计时     |
| C-c C-x C-o  | 停止计时               |
| C-c C-x C-e  | 更新计时任务进度       |
| C-c C-x C-q  | 取消计时               |
| C-c C-x C-j  | 跳转到计时任务         |


  - 截止日期和计划安排

### capture相关的内容 
[参考资料](https://www.zmonster.me/2018/02/28/org-mode-capture.html)

一个模板主要有5个部分构成
| 模板组成    | 描述               |
|-------------|--------------------|
| key         | 选择模板的字符     |
| description | 展示模板的描述     |
| type        | 新增内容的类型     |
| target      | 新增内容的存储位置 |
| template    | 新增内容的模板     |

  ```org
  例子:
  '("t" "Task" entry (file+headline "" "Tasks") "* TODO %?\n  %u\n  %a")
  ```

  - 新增内容类型type
| type      | description            |
|-----------+------------------------|
| entry     | 带有headline的一个节点 |
| item      | 一个列表项             |
| checkitem | 一个checkbox列表项     |
| plain     | 普通文本               |

### agenda
[org使用手册](https://grass.show/omegat/target/Org%E4%BD%BF%E7%94%A8%E6%89%8B%E5%86%8C(%E5%AE%8C%E6%95%B4%E7%89%88).html)
### latex公式 
  参考资料:[org mode 使用latex](https://blog.csdn.net/csfreebird/article/details/43636615)

  - 希腊字母等特殊字符
    ```org
    \alpha \beta \gamma  
    \times    //乘号
    ```
    - 实例:
      \alpha \beta \gamma  

      \times
    - 用 $M-x\ \ org-entities-help$ 可以察看所有entitles
  - 上下标
    ```org
    a_1   a_{1}   //下标
    b^5   b^{5}   //上标签
    ```
    - 实例:

      a_1   a_{1}   

      b^5   b^{5}   
  - 求和符号
    ```org
    \begin{equation}
    \sum_{i=1}^n(单项评分_i*权重)    //求和符号
    \end{equation}
    ```
    - 实例:
      \begin{equation}
      \sum_{i=1}^n(单项评分_i*权重)    
      \end{equation}
    - *注:equation和$$的区别是后面会不会有一个数字标签*
  - 分式
    ```org
    \begin{equation}
    \frac{1^p+2^p+\cdot\cdot\cdot+n^p}{n^{1+p}}  //分式
    \end{equation}
    ```
    - 实例:

    \begin{equation}
    \frac{1^p+2^p+\cdot\cdot\cdot+n^p}{n^{1+p}}  
    \end{equation}                               
  - 箭头上面数字
    ```org
    $$\stackrel{abc}{\longrightarrow}$$   //箭头上有abc
    ```
    - 实例:
      $$\stackrel{abc}{\longrightarrow}$$   
  - 分段函数
    ```org
    \begin{equation}
    Y=\left\{
    \begin{aligned}
    +1 & , & if &&X \geq \theta \\     
    -1 & , & if && X < \theta           //分段函数
    \end{aligned}
    \right.
    \end{equation}
    ```
    - 实例:
      \begin{equation}
      Y=\left\{
      \begin{aligned}
      +1 & , & if &&X \geq \theta \\     
      -1 & , & if && X < \theta           
      \end{aligned}
      \right.
      \end{equation}
    - 解释:
      - $反斜杆$ 是换行的意思
      - $&&$ 之间可以夹一些如逗号什么的东西
## 文件管理
## eaf
- 浏览器

| 命令 | 作用     |
|------|----------|
| m    | 设置书签 |
| f    | 跳转     |

## ledger
   参考资料:[程序员的记账工具](https://segmentfault.com/a/1190000022077344),[使用Ledger来记账](https://c-tan.com/zh/post/ledger-org-babel-example/)

   - 账户划分方法
     | *Assets*              | *表示用户的资产* |
     |-----------------------|------------------|
     | Assets:Checking       | 表示消费账户     |
     | Assets:Investment     | 表示投资的账户   |
     |
     | *Expense*             | *用户的支出*     |
     |
     | Expense:Clothes       | 衣物             |
     | Expense:Education     | 书籍文具等       |
     | Expense:Entertainment | 电影游戏等       |
     | Expense:Food          | 买菜就餐等       |
     | Expense:Work          | 工作方面的            |
     |
     | *Equity*              | *初始化账户余额* |
     | *Income*              | *收入*           |
    

# 常用的命令

| 命令                                    | 作用               |
|-----------------------------------------|------------------|
| replace-string                          | 替换字符串         |
| recover file                            | 恢复自动保存文件   |
| fundamental-mode                        | 切换模式           |
| text-mode                               | 切换文本编辑模式   |
| auto-fill-mode                          | 自动折行开启(关闭) |
| benchmark-init/show-durations-tree      | 树状图展示启动耗时 |
| benchmark-init/show-durations-tabulated | 表格展示启动耗时   |
| sort-lines                              | 行排序             |
| count words                             | 字符统计           |
| eaf-open-bookmark                       | 展示当前书签       |

