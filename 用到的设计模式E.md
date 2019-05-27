# MyBatis里面用到了哪些设计模式？
SqlSessionFactoryBuilder：建造者模式  
SqlSessionFactory：单例模式  
缓存CachingExecutor：装饰器模式  
Mapper对象：是MapperProxy的代理对象，（动态）代理模式  
对结果集的处理，转换为实体类：工厂模式  
插件：责任链模式  
