# MVVM.Light.Snippets

## Description

These snippets are used in Visual Studio 2015,2017,2019.  
**VB.NET**.   
It's easy to generate code by using shortcut.   
Some snippets are containing Chinese, because I am.  
You can genenerate your own snippets(C# or VB.NET), following the official link:
[Walkthrough: Create a code snippet](https://docs.microsoft.com/en-us/visualstudio/ide/walkthrough-creating-a-code-snippet?view=vs-2019 "Markdown")
## Contains

1.Property     
2.RelayCommand  
3.Regions(I divide the viewmodel code into seprate regions,like property region or relaycommand region, convinient to manage code)  
4.Inherits ViewModelBase  
5.Messenger.Send  
6.Messenger.Register  

For example, Property: In VB.NET, type "mlprop" then "TAB", you will get
``` vb.net
    ''' <summary>
    ''' 做什么
    ''' </summary>
    Dim _变量 As 数据类型 = 初始值
    Public Property Property名称 As 数据类型
        Get
            Return _变量
        End Get
        Set(value As 数据类型)
            [Set](NameOf(Property名称), _变量, value)
        End Set
    End Property
```  
## How to add snippets


First, in Visual Studio 2019, **CTRL +K, CTRL + B** to open snippets code management.

Second, choose your lanaguage.

Third, select **My Code Snippets**.

Fourth, add the folder you download from here, or the folder of snippets you created in **.snippet**.

Fifth, done!


## Usage
Well, I use VB.NET most time, there is a slight difference between C# and VB.NET usage.

C# usage:

**shortcut** TAB TAB

VB.NET usage:

**shortcut** TAB


## Some Tips
1.Please use the shortcut that you can remember easily, like "mlprop" - means mvvm.light property.  
2.Don't try to remember the shortcut from official snippets, try to modify them to fit your own style.  

Just open xx.snippet and modify the **\<Shortcut\>** section under **\<Header\>**

