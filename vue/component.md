### new vue和 vue.component的关系

    + new vue用于指定元素为vue对象
    + vue.component 则用于注册vue组件，组件实际上也是vue实例，data、method均具有

### 组件的一些特性

    - props : `props: [list],` 与data使用类似
        +eg： 
        ``` javascript
        props:['title','test'] 
        -------
        <el title="helloworld" test="custorm"></el>
        ```
    
        
### 组件向父级传输信息