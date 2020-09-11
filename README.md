# rfc 不BB  这是一个国产编程语言 
* 目的就是骗取经费 但是真的是纯国产的 而且能运行 并且简洁高效
## 抄袭的语言包括但不限于 反正能抄的都抄 毕竟国产化嘛
* rust  dart JavaScript Go Scala erlang  


## 不bb 直接上 例子 简单看下语法 
```js
use http
use (json,task)

f main(){

    var str = "hello"
    println(str)
    srt = "world"
    println(str)

    println("hello f-lang")
    val a = await f2()
    println(a)

    val taskReturns =  task.all(
        getUrl("http://baidu.com"),
        getUrl("https://baidu.com"),
    )

    for   tReturn  await  taskReturns {
        println(tReturn.body.string())
    }
    
}


f f1(){
    print("this is f 1")
}

async f2(){
   return 1
}


async getUrl(url string){
   r await http.get(url)
}


struct Person{
    name string
    age int
}


```
