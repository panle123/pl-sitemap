<<<<<<< HEAD
<<<<<<< HEAD
# pl-sitemap
sitemap包
=======


# directive

> A Vue.js project

## Build Setup

``` 



const sitemap = require("yf-redis-sitemap");

* @param client  redis
* @param default_list 默认数据
* @param weight 权重分配
* @param save_path 保存路径
* @param day 默认更新时间1天

sitemap.init({
    client:client,
    default_list:newres,
    weight:[
    {
        url:/\.(com|top)(\/)?$/,
        priority:1
    },
    {
        url:/.*relatedGoods.*/,
        priority:0.8
    },
    {
        url:/.*/,
        priority:0.6
    },
    ],
    save_path:'sitemap3.xml'
})

sitemap.deleSitemap(context); 删除redis数据
sitemap.addSitemap(context); 添加redis新数据
sitemap.deleAll() 清空redis所有数据
```
>>>>>>> 3.3
=======
# pl-sitemap
sitemap包
>>>>>>> b94bc1f7cda0d0ee776a2e4e85d6359196d32a51
