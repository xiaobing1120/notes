

## 在当前页面的.json 文件中引用组件

```javascript 
{
  "usingComponents": {
    "DefaultPage": "../../components/default-page/default-page"
  }
}
```



### 参数

1. type
> 类型：Number  
> 必传：是  
> 释义： 显示内容的类型  
> 可选值： 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9  
```
1 加载中 
2 暂无数据 
3 404         
4 搜索无结果 
5 下拉刷新
6 暂无评论  
7 没有更多了
8 无网络 
9 加载失败
```

2. fullScreen
> 类型：Boolean  
> 必传：否  
> 释义： 是否全屏显示，默认false  
> 可选值： true | false  

3. vertical
> 类型：String  
> 必传：否  
> 释义： 垂直显示位置，默认 'center'  
> 可选值： 'flex-start' | 'center' |  'flex-start'  

