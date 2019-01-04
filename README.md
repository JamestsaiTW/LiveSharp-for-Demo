# LiveSharp in Xamarin.Forms Demo

## What is LiveSharp?

LiveSharp is a .NET tool that lets you develop your code without recompilation.  
LiveSharp 讓你在使用 .NET 開發程式不需要重新編譯就能看到執行結果的工具。

Read more:  
了解更多:  
https://github.com/OYIon/LiveSharp

## Use LiveSharp in Xamarin.Forms

This demo code is a sample/documentation to know how use LiveSharp in Xamarin.Forms.  
這個 demo code 是讓你知道如何在 Xamarin.Forms 當中使用 LiveSharp 的一個展示範例/說明。

### For Visual Studio Settings

1. Install [LiveSharp Visual Studio extension](https://marketplace.visualstudio.com/items?itemName=ionoy.LiveSharp).  
安裝 [LiveSharp Visual Studio 擴充套件](https://marketplace.visualstudio.com/items?itemName=ionoy.LiveSharp)。  

2. In Visual Studio menu: Tools > Options > (or Debug > Options) > Debugging > General, deselect "Edit and Continue" in the right pane.  
   在 Visual Studio 選單: 工具 > 選項 > (或 偵錯 > 選項) > 偵錯 > 一般, 在右邊窗格中取消 "啟用編輯後繼續" 的勾選。  
   
   ref: [How to: Enable and disable Edit and Continue (C#, VB, C++)](https://docs.microsoft.com/en-us/visualstudio/debugger/how-to-enable-and-disable-edit-and-continue?view=vs-2017)


### For this Demo code

1. Update all Nuget packages in each project, then make sure demo code build success and work with no error.  
   在每一個專案當中更新所有的 Nuget 套件, 然後確認此 demo code 編譯正常成功沒有錯誤。
   
2. Use Debug Mode (F5) to run your App.  
   使用偵錯 (F5) 執行你的 App。
   
3. Write or Edit your C# Code in Visual Studio.  
   回到 Visual Studio 當中撰寫或編輯 C# Code。  


### For Your Empty Project Settings

1. Create a Xamarin.Forms project.  
   建立一個 Xamarin.Forms 的方案。  
   
2. Update all Nuget packages in each project, then make sure your project build success and work with no error.
   在每一個專案當中更新所有的 Nuget 套件, 然後確認所建立的方案編譯正常成功沒有錯誤。  
   
3. Install [LiveSharp.Support.XamarinForms Nuget package](https://www.nuget.org/packages/LiveSharp.Support.XamarinForms/). (Just only on Xamarin.Forms Project.)  
   安裝 [LiveSharp.Support.XamarinForms Nuget 套件](https://www.nuget.org/packages/LiveSharp.Support.XamarinForms/)。(只要在 Xamarin.Forms 專案中就好。)  
   
4. Try to build your App and make sure no error.  
   嘗試建置你的 App 並且確認沒有錯誤。
   
5. Use Debug Mode (F5) to run your App.  
   使用偵錯 (F5) 執行你的 App。  
   
6. Write or Edit your C# Code in Visual Studio.  
   回到 Visual Studio 當中撰寫或編輯 C# Code。
