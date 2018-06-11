# Simple-Dependency-Injection

### 如果Class A 中包含 Class B的实例，那么可以说明Class A 对 Class B有一个依赖。

1、构造器注入；
       public class Teacher(){
          Student student;
          //在调用Teacher的构造方法之前外部就已初始化好Student对象
          //非自己主动初始化依赖，而通过外部传入依赖的方式称为依赖注入
          public Teacher(Student student){
            this.student=student;
          }
        }
        
2、接口注入
public interface ITeacher{
  
}

3、setter注入

4、注解注入
