# java笔记
1. 抽象方法没有方法体

抽象方法只写声明就好了
如：
```
abstract class one{//含有抽象方法的类十一个抽象类
 abstract void print();//抽象方法
 void printmain(){};//具体方法
}
```
2. 在接口中的静态方法需要有方法体

```
public interface Something {
    public static void doSomething(){};
    public abstract String dosomething();
}
```
 

