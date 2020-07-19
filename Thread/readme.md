创建线程方法1：继承 Thread 类，重写 run() 方法，调用 start 方法开启线程

创建线程方法2：实现runnable接口，重写 run() 方法，执行线程需要丢入runnable接口实现类，调用start方法.
