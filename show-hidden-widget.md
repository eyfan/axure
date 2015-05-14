# 显示隐藏的部件  

## 步骤 1 添加一个矩形部件
首先，打开 AxureShowHiddenWidget.rp 然后打开“显示隐藏的部件”页面。      

在这个例子中，我们会创建一个当登录失败时的错误信息。

在部件面板中拖放一个矩形部件到设计区域的登录按钮下方。  

![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/showhiddenwidget1.png)  

## 步骤 2 为部件命名
当矩形被选中时：

在部件交互和注释面板顶部为部件命名为“错误信息”。

![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/showhiddenwidget2.png) 

## 步骤 3 设计错误信息
使用样式工具去创建一个红底白字的错误信息：

“登录信息不正确。请重新尝试。”

![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/showhiddenwidget3.png) 

## 步骤 4 设置部件为隐藏状态
当矩形被选中时，在样式页签中切换“可见”选项。这会使页面上的部件默认为隐藏状态并且你会看见一个黄色的覆盖面。


![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/showhiddenwidget4.png) 

## 步骤 5 添加“登录成功”用例
现在，我们一起为“登录”按钮添加交互动作。作为第一个用例，我们想登录成功时就打开“我的账户”页面。

在设计区域中选中登录按钮。为点击时事件添加一个用例，在用例编辑器的左上角更改用例名称为“登录成功”。然后，添加“打开链接”动作并选择“我的账户”页面。

点击“确定”关闭用例编辑器。

![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/showhiddenwidget5.png) 

## 步骤 6 添加“登录失败”用例
在第二个用例中，我们想在登录失败时显示错误信息。  

在点击时事件中添加第二个用例“登录失败”。然后，添加“显示”动作，选中“错误信息”。点击“确定”。

![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/showhiddenwidget6.png)

## 步骤 7 预览原型
在工具栏中点击预览按钮来预览原型。你会看见点击登录按钮时会显示两个用例。点击“登录成功”会跳转到我的账户页面，点击“登录失败”会显示错误信息。

![image](https://raw.githubusercontent.com/jikexueyuanwiki/axure/master/images/showhiddenwidget7.png)

显示，隐藏，让这些交互生动起来！

依然需要帮助？查看 [论坛](http://www.axure.com/c/forum.php) 或者给我们留言 [support@axure.com](mailto:support@axure.com) 。