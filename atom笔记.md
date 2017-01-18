[链接](https://flight-manual.atom.io)
### chaper1: Getting started
#### Why Atom?
> Atom is a specialized variant of Chromium designed to be a next editor rather than a web browser.

---
#### Atom Basics

**Ctrl + Shift + P** 会打开命令面板  <br>
**打开目录** File > Add Project Folder or **Alt + Ctrl + o** （不过我这里不知道为什么没用)  <br>
**打开关闭目录视图** 可以使用 **ctrl + \** 使用 **Alt + \** 可以移动焦点在便器区和目录视图  <br>
**打开在项目下面的文件** 使用 **ctrl + T** 或者 **ctrl + p**  <br>
**在已打开文件中打开文件** 使用 **ctrl + B**   <br>
**在git提交之前中打开文件** 使用 **ctrl + shift + B**  <br>

---
### Chapter2: Using Atom
#### Atom Packages
---
#### Moving in Atom
**ctrl + Left** 移动到单词的开头（上一个或者本单词）  <br>
**ctrl + right** 移动到单词的末尾  <br>
**Home** 移动到改行的第一个字节处  <br>
**End** 移动到该行的最后一个字节处  <br>
**Ctrl + Home** 移动到当前文档的最开头  <br>
**Ctrl + End** 移动到当前文档的最后面  <br>
**Ctrl + G** 移动到某一行某一列（eg:26:10）  <br>
#### Navigationg by Symbols
**Ctrl + R** 跳转到某一个标记 **Ctrl + T** 在打开文件中跳转到某个标记
#### Bookmarks
**Alt + ctrl + f2** 将会标记当前行位一个书签  <br>
**f2** 跳转到当前文档的下个标签  <br>
**shift + f2** 相反的方向跳转到下个标签  <br>
**ctrl + f2** 观看当前项目所有书签  <br>

---
#### Atom Selections
**shift + Up** 想上选中  <br>
**shift + down** 向下选中  <br>
**shift + left** 向左选中一个字节  <br>
**shift + right** 向右选中一个字节  <br>
**ctrl + shift + left**  到单词开头之间全部选中  <br>
**ctrl + shift + right** 到单词结束之间全部选中  <br>
**shift + End** 到该行结束之间全部选中  <br>
**shift + Home** 到该行第一个单词之间全部选中  <br>
**ctrl + shift + home** 到该文档最初之间全部选中  <br>
**ctrl + shift + end** 到该文档末尾知之间全部选中  <br>
**ctrl + A** 当前文档全部选中  <br>
**ctrl + L** 当前行全部选中  <br>

---
#### Editing and Deleting Text
**ctrl + J** 把下一行加入到当前行后面（合并下一行）  <br>
**ctrl + up/down** 移动当前行想上/下   <br>
**ctrl + shift + D** 复制当前行  <br>
**ctrl + k,ctrl + U** 全部大写（英文字符全部大写）  <br>
**ctrl + k,ctrl + L** 全部小写  <br>

---
#### Deleting and Cutting
**ctrl + shift + k** 删除当前行  <br>
**ctrl + backspace** 删除到当前单词开头  <br>
**ctrl + Delete** 删除到当前单词结束  <br>

---
#### Multiple Cursors and Selections
**Ctrl + Click**  在点击的地方增加一个新的输入光标  <br>
**Alt + Ctrl + Up/Down** 在当前光标上面或下面增加光标(没反应？)  <br>
**Ctrl + D** 选中下个当前选中的单词  <br>
**Alt + f3** 选中当前选中一样的内容在当前文档中选中  <br>

---
#### whitespace
#### Brackets

**ctrl + M** 跳转到匹配的符号（“”《》(){}[]）  <br>
**alt +ctrl + M** 选中当前匹配符号之间的内容 (没反应？) <br>
**Alt + ctrl + ,** 关闭当前XML/HTML标签  <br>

---
#### Encoding
**ctrl +shift + u** 打开当前编码格式toggle(我的是alt + U)  <br>

---
#### Find And Replace
**ctrl + f** 在打开文档中搜寻  <br>
**ctrl +shift + f** 在当前项目中搜寻  <br>
**esc** 关闭搜寻框  <br>

---
#### Snippets
控制面板中输入 **Snippets:Available** 打开提示按钮  <br>

---
#### Autocomplete
using **Tab** 或者 **Enter** 来快速选中  <br>

---
#### Folding
**ctrl + alt + [** 折叠代码  <br>
**ctrl + alt + ]** 打开折叠代码  <br>
**ctrl + alt + shift + [** 折叠全部代码  <br>
**ctrl + alt + shift + ]** 打开全部折叠代码  <br>
**ctrl + K,ctrl + 0-9** 按照缩进深度进行代码折叠  <br>
**ctrl + alt + f** 选择折叠选项(没反应)  <br>

---
#### Panes
**ctrl + k,up/down/left/right** 分割编辑区  <br>
**ctrl +k,ctrl + up/down/left/right** 移动当前选中编辑区

---
#### Pending Pane Items
---
#### Grammar
**ctrl + shift + l** 打开文本代码选择器  <br>

---
#### version control in Atom
**alt + ctrl + z** 检查head revision  <br>
**alt + g,O** 在github中打开文件  <br>
**alt + g,B** 在github中已blame视图打开文件  <br>
**alt + g,H** 在github中以histroy视图打开文件  <br>
**alt + g,C** 复制在github中打开文件的URL  <br>
**alt + g,R** 比较分支  <br>

---
#### Writing in Atom
**ctrl + shift + ;** 打开语法提示输入框  <br>
**ctrl + shift + m** 打开markdown预览视图  <br>
```css
![]() 插入Snippets
```
---
