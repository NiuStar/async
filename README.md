# ASYNC

异步执行类，提供异步执行的功能，可快速方便的开启异步执行
通过NewAsync() 来创建一个新的异步操作对象
通过调用 Add 函数来向异步任务列表中添加新的任务
通过调用 Run 函数来获取一个接收返回的channel，当返回结果时将会返回一个map[string][]interface{}的结果集，包括每个异步函数所返回的所有的结果



