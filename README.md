# Простой проект

## Подзаголовок
### Some code right here

```java
public class FooBar{
    public static void main(String[] args){
        Runnable runnable = () -> {
        try {
            String name = Thread.currentThread().getName();
            System.out.println("Foo " + name);
            TimeUnit.SECONDS.sleep(1);
            System.out.println("Bar " + name);
        }
        catch (InterruptedException e) {
            e.printStackTrace();
        }
    };

    Thread thread = new Thread(runnable);
    thread.start();
    }
}
```

## What-is-recursion


|----------------------| move down the stairs

|----------------------|

|----------------------|

|----------------------|

|----------------------|

|----------------------|

|----------------------|

|----------------------|

|----------------------|

|----------------------| down

|----------------------|

|----------------------|

|----------------------|

|----------------------|

|----------------------|

|----------------------|

|----------------------| down

|----------------------|

|----------------------|

|----------------------|

|----------------------|

|----------------------|

|----------------------|

|----------------------|

|----------------------|

|----------------------|

|----------------------|

|----------------------|

|----------------------| down

|----------------------|

|----------------------|

|----------------------|

|----------------------|

|----------------------|

|----------------------|

|----------------------|

|----------------------|

|----------------------|

|----------------------|

|----------------------|

|----------------------|

|----------------------|

|----------------------|

|----------------------| down

|----------------------|

|----------------------|

|----------------------|

|----------------------|

|----------------------|

|----------------------|

|----------------------|

|----------------------|

### [Click here to discover recursion](##What-is-recursion)


