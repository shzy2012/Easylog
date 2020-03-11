# Easylog
C# 简单的log输出到文件 log.txt,生成的文件自动递增

适用场景：用于单个项目的小项目打印日志

example

```C#
Easylog.Log log = new Easylog.Log();


log.Info("hello i am log"); //输出日志信息

try
{
    //code
}
catch (Exception ex)
{
    log.Error("desc", ex);  //输出错误信息
}

```

<img src="https://github.com/shzy2012/static/blob/master/easy_log.png?raw=true" width="900" height="400">

<img src="https://github.com/shzy2012/static/blob/master/easy_log_context.png?raw=true" width="900" height="400">
