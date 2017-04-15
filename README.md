# android开发向导介绍
> 在开发中封装一些工具类对开发效率有极大的提示，下面就给大家介绍一些自己封装方法  
> 本文章简单介绍一些android开发工具类和学习路径

### 小编特别介绍封装神方法配合反射使用此乃封装利器
```
泛型内部获取泛型类型
Type type = getClass().getGenericSuperclass();
Type trueType = ((ParameterizedType) type).getActualTypeArguments()[0];
Class<T> cls = (Class<T>) trueType;
LogA.e(cls.getClass());
```

###数据处理
 - [gson基本使用](./pro/gson.md)
 - [log打印对象](./pro/log.md)  
 - [定时缓存](./pro/cache.md)