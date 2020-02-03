# saver
```
//saver_comment
//saver_timestamp
//saver_history=[[saver_comment,saver_timestamp]]
saver
 .load(obj)
 .save()
 .val(k,v)
 .flg(k)
 .cnt(k)
 .isflg(k)
 .isval(k,v)
```

```
//loopend(()=>{},10,()=>{},1000)
function loopend(caller,inteval,endcaller,timeout){
 let cl=setInterval(caller,interval)
 setTimeout(()=>{return clearInterval(cl),endcaller()},timeout)
}


```
