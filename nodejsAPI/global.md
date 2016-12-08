# nodejs 全局对象

## javascript里面的全局对象 window
## nodejs里面有一个全局对象  global


###global里面的子对象
1. console
     1.1 console.log()在控制台输出消息
     1.2 console.error()在控制台输出一个错误的消息
     1.3 console.time() 在程序运行之前，记录当前的时间
     1.4 console.timeEnd() 在程序运行完成之后调用，记录当前的时间
     1.5 console.trace() 程序追踪
2. modules  export
3. process  用来操作或者是获取或者查看 当前进程的相关信息
    3.1  argv  是用来获取敏玲行相关的参数的，["执行的二进制"]
    3.2  chdir() 改变进程运行的目录
    3.3  cwd() 当前进程所在的目录
    3.4  stdin  标准的输入流
         事件：  "data" process.stdin.on("data",function(){})
         主动的触发自定义的事件  process.stdiin.emit(event,function())
         输入溜状态
         暂停： process.stdin.pause(); 
         重启： process.stdin.resume();
    3.5 stdout 标准的输出流
        process.stdout.write();
        
### global 里面的方法
 1. setInterval();
 2. clearInterval();
 3. setTimeOut();
 4. clearTimeOut();
 5. require(path); 引入其他模块
    require.cache  记录了当前文件所引用的所有模块
    require.resolve("./nodeq.js") 将引用的相对路径，转换为绝对路径
  
### 魔术常量
  1. _dirname  当前文件运行文件的目录
  2. _filename 当前运行的文件
  
### 

