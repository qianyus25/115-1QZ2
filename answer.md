# 第2次練習題目-隨堂-QZ2
>
>學號：113111114 
><br />
>姓名：黃品綾 
><br />
>作業撰寫時間：80 
><br />
>最後撰寫文件日期：2023/10/28 
>

本份文件包含以下主題：(至少需下面兩項，若是有多者可以自行新增)
- [x] 說明內容
- [x] 其他 (可以包含心得或是想跟老師反映)

## 說明內容

開始寫說明，該說明需說明想法，
並於之後再對上述想法的每一部分將程式進一步進行展現，
若需引用程式區則使用下面方法，
若為.cs檔內程式除了於敘述中需註明檔案名稱外，
還需使用語法` ```語言種類 程式碼 ``` `，其中語言種類若是要用python則使用py，java則使用java，C/C++則使用cpp，
下段程式碼為語言種類選擇csharp使用後結果：

```csharp
public void mt_getResult(){
    ...
}
```

若要於內文中標示部分網頁檔，則使用以下標籤` ```html 程式碼 ``` `，
下段程式碼則為使用後結果：

```html
<%@ Page Language="C#" AutoEventWireup="true" ...>

<!DOCTYPE html>

<html xmlns="http://www.w3.org/1999/xhtml">
<head runat="server">
<meta http-equiv="Content-Type" ...>
    <title></title>
</head>
<body>
    <form id="form1" runat="server">
        <div>
        </div>
    </form>
</body>
</html>
```
更多markdown方法可參閱[https://ithelp.ithome.com.tw/articles/10203758](https://ithelp.ithome.com.tw/articles/10203758)

請在撰寫"說明程式與內容"該塊內容，請把原該塊內上述敘述刪除，該塊上述內容只是用來指引該怎麼撰寫內容。

1. (需截圖說明，並且需截圖執行結果)

![w](img/w.png)

Ans:using UnityEngine.InputSystem;用來偵測玩家按鍵件
Keyboard keyboard = Keyboard.current;取得目前的鍵盤狀態
if (keyboard.wKey.isPressed)偵測 W 鍵是否按下
Debug.Log("玩家按了 W 鍵！");	在 Console 印出指定的文字

2. (需截圖說明，並且需截圖執行結果)

![A](img/A.png)

![S](img/S.png)

![D](img/D.png)


Ans:程式都一樣
只需將if (keyboard.wKey.isPressed)偵測 W 鍵是否按下
Debug.Log("玩家按了 W 鍵！");	在 Console 印出指定的文字
這兩段的程式(w)key改成(A)key  (S)key (D)key 印出的文字也更改就能顯示按了哪個鍵

## 其他
心得:實際上花了多久時間完成有點忘了，但第一次看的時候發現要想很久才能稍微看懂，要等實際操作後才知道卡在哪裡。