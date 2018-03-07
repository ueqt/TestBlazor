# blazor测试

https://github.com/aspnet/Blazor

https://github.com/aspnet/Blazor-Hackathon

https://github.com/aspnet-community-demos/Blazor-Demos

https://github.com/SteveSanderson/Blazor/

## 新建项目

在windows中下载https://github.com/SteveSanderson/Blazor/releases/download/v0.3.1/Blazor.VSExtension.vsix安装

使用Blazor模板新建项目

## 编译

```bash
cd BlazorApplication1
dotnet restore BlazorApplication1.sln
dotnet build BlazorApplication1.sln
```
[~/Downloads/TestBlazor/BlazorApplication1]
-> % dotnet build BlazorApplication1.sln

## 运行

```bash
cd BlazorApplication1
dotnet blazor serve
```

[~/Downloads/TestBlazor/BlazorApplication1/BlazorApplication1]
-> % dotnet blazor serve