<!-- MDTOC maxdepth:6 firsth1:1 numbering:0 flatten:0 bullets:1 updateOnSave:1 -->

- [JetBrains全家桶 IDE 常用技巧](#jetbrains全家桶-ide-常用技巧)   
   - [启用Vim](#启用vim)   
   - [启用Vim相对行号](#启用vim相对行号)   
   - [鼠标滚动放大/缩小字体](#鼠标滚动放大缩小字体)   
   - [格式化代码](#格式化代码)   
   - [注释](#注释)   
   - [删除](#删除)   
   - [复制](#复制)   
   - [选中区域自动包裹括号引号](#选中区域自动包裹括号引号)   
   - [自动补全启用大小写支持](#自动补全启用大小写支持)   
   - [代码缩进及反缩进](#代码缩进及反缩进)   
   - [快速实现接口](#快速实现接口)   

<!-- /MDTOC -->
# JetBrains全家桶 IDE 常用技巧

## 启用Vim

File->Settings->Plugins 安装IdeaVim插件

![20210712_212220_63](image/20210712_212220_63.png)

File->Settings->Keymap 选择**适合**自己的开关，用于Vim模式和Idea模式快速切换


![20210712_212319_94](image/20210712_212319_94.png)

## 启用Vim相对行号

右小脚IdeaVim标志，没有配置则会创建，有配置就是open，添加vimrc内容即可

![20210718_111153_85](image/20210718_111153_85.png)

![20210718_111313_82](image/20210718_111313_82.png)


```
"" Source your .vimrc
"source ~/.vimrc

set nm
set relativenumber
```


## 鼠标滚动放大/缩小字体

方法一：

![20210713_192537_75](image/20210713_192537_75.png)

方法二：

File->Settings->Keymap 搜索中输入increase

![20210712_212433_95](image/20210712_212433_95.png)

![20210712_212455_76](image/20210712_212455_76.png)

![20210712_212505_42](image/20210712_212505_42.png)

File->Settings->Keymap 搜索中输入decrease

![20210712_212533_57](image/20210712_212533_57.png)

![20210712_212552_36](image/20210712_212552_36.png)

![20210712_212541_87](image/20210712_212541_87.png)

## 格式化代码

```
Ctrl + Alt + L (小写l)
```

## 注释

默认光标所在行注释，若选中多行则都会注释

```
Ctrl + /
```

## 删除

默认删除光标所在行，若选中多行则都会删除

```
Ctrl + x
```

## 复制

默认复制光标所在行，若选中多行则都会复制

```
Ctrl + d
```

## 选中区域自动包裹括号引号

```
Surround selection on typing quote or brace
```

Editor -> General -> Smart Keys

![20210713_200653_75](image/20210713_200653_75.png)


## 自动补全启用大小写支持

```
Match case
```

Edirotr -> Gneeral -> Code Completion

![20210713_200833_62](image/20210713_200833_62.png)


## 代码缩进及反缩进

```
缩进：Tab
反缩进：Shift + Tab
```

## 快速实现接口

在 type struct 上使用

![20210714_215053_26](image/20210714_215053_26.png)










---
