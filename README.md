AndroidLife
==

<br>
<br>

- 源码解析
    - [AIDL 源码解析](https://github.com/shadowwingz/AndroidLife/blob/master/article/AIDL%20%E6%BA%90%E7%A0%81%E8%A7%A3%E6%9E%90.md)
    - [Binder 的使用及上层原理](https://github.com/shadowwingz/AndroidLife/blob/master/article/Binder%20%E7%9A%84%E4%BD%BF%E7%94%A8%E5%8F%8A%E4%B8%8A%E5%B1%82%E5%8E%9F%E7%90%86.md)
    - [Toast 源码解析](https://github.com/shadowwingz/AndroidLife/blob/master/article/Toast%20%E6%BA%90%E7%A0%81%E8%A7%A3%E6%9E%90.md)
    - [AlertDialog 源码解析](https://github.com/shadowwingz/AndroidLife/blob/master/article/AlertDialog%20%E6%BA%90%E7%A0%81%E8%A7%A3%E6%9E%90.md)
    - [ThreadLocal 源码解析](https://github.com/shadowwingz/AndroidLife/blob/master/article/ThreadLocal%20%E6%BA%90%E7%A0%81%E8%A7%A3%E6%9E%90.md)
    - [消息机制源码解析](https://github.com/shadowwingz/AndroidLife/blob/master/article/handler/handler.md)
        - [Handler、Looper、MessageQueue 分别运行在什么线程，为什么](https://github.com/shadowwingz/AndroidLife/blob/master/article/handler/handler.md#handlerloopermessagequeue-%E5%88%86%E5%88%AB%E8%BF%90%E8%A1%8C%E5%9C%A8%E4%BB%80%E4%B9%88%E7%BA%BF%E7%A8%8B%E4%B8%BA%E4%BB%80%E4%B9%88)
        - [Handler、Looper、MessageQueue 各有几个，为什么](https://github.com/shadowwingz/AndroidLife/blob/master/article/handler/handler.md#handlerloopermessagequeue-%E5%90%84%E6%9C%89%E5%87%A0%E4%B8%AA%E4%B8%BA%E4%BB%80%E4%B9%88)
        - [Handler、Looper、MessageQueue 是怎么关联的](https://github.com/shadowwingz/AndroidLife/blob/master/article/handler/handler.md#handlerloopermessagequeue-%E6%98%AF%E6%80%8E%E4%B9%88%E5%85%B3%E8%81%94%E7%9A%84)
        - [Android中为什么主线程不会因为 Looper.loop() 里的死循环卡死？（未完成）]()
    - [AsyncTask 源码解析](https://github.com/shadowwingz/AndroidLife/blob/master/article/asynctask/asynctask.md)
    - [事件分发源码解析](https://github.com/shadowwingz/AndroidLife/blob/master/article/%E4%BA%8B%E4%BB%B6%E5%88%86%E5%8F%91%E6%BA%90%E7%A0%81%E8%A7%A3%E6%9E%90.md)
    - [滑动冲突解决方式之外部拦截法](https://github.com/shadowwingz/AndroidLife/blob/master/article/%E6%BB%91%E5%8A%A8%E5%86%B2%E7%AA%81%E8%A7%A3%E5%86%B3%E6%96%B9%E5%BC%8F%E4%B9%8B%E5%A4%96%E9%83%A8%E6%8B%A6%E6%88%AA%E6%B3%95.md)
    - [滑动冲突解决方式之内部拦截法](https://github.com/shadowwingz/AndroidLife/blob/master/article/%E6%BB%91%E5%8A%A8%E5%86%B2%E7%AA%81%E8%A7%A3%E5%86%B3%E6%96%B9%E5%BC%8F%E4%B9%8B%E5%86%85%E9%83%A8%E6%8B%A6%E6%88%AA%E6%B3%95.md)
    - [MeasureSpec 源码解析](https://github.com/shadowwingz/AndroidLife/blob/master/article/MeasureSpec%20%E6%BA%90%E7%A0%81%E8%A7%A3%E6%9E%90.md)
    - View 的工作流程
        - [View 的 measure 原理](https://github.com/shadowwingz/AndroidLife/blob/master/article/View%20%E7%9A%84%20measure%20%E5%8E%9F%E7%90%86.md)
        - [View 的 layout 原理](https://github.com/shadowwingz/AndroidLife/blob/master/article/View%20%E7%9A%84%20layout%20%E5%8E%9F%E7%90%86.md)
        - [View 的 draw 原理](https://github.com/shadowwingz/AndroidLife/blob/master/article/View%20%E7%9A%84%20draw%20%E5%8E%9F%E7%90%86.md)
    - ViewGroup 的工作流程
        - [ViewGroup 的 measure 原理](https://github.com/shadowwingz/AndroidLife/blob/master/article/ViewGroup%20%E7%9A%84%20measure%20%E5%8E%9F%E7%90%86.md)
        - [LinearLayout 的 measure 原理](https://github.com/shadowwingz/AndroidLife/blob/master/article/LinearLayout%20%E7%9A%84%20measure%20%E5%8E%9F%E7%90%86.md)
        - [LinearLayout 的 layout 原理](https://github.com/shadowwingz/AndroidLife/blob/master/article/LinearLayout%20%E7%9A%84%20layout%20%E5%8E%9F%E7%90%86.md)
        - [RelativeLayout 的 measure 原理](https://github.com/shadowwingz/AndroidLife/blob/master/article/RelativeLayout%20%E7%9A%84%20measure%20%E5%8E%9F%E7%90%86.md)
        - [RelativeLayout 的 layout 原理](https://github.com/shadowwingz/AndroidLife/blob/master/article/RelativeLayout%20%E7%9A%84%20layout%20%E5%8E%9F%E7%90%86.md)
        - [LinearLayout 和 RelativeLayout 的 draw 原理](https://github.com/shadowwingz/AndroidLife/blob/master/article/LinearLayout%20%E5%92%8C%20RelativeLayout%20%E7%9A%84%20draw%20%E5%8E%9F%E7%90%86.md)
    - [RemoteViews 源码解析](https://github.com/shadowwingz/AndroidLife/blob/master/article/RemoteViews%20%E6%BA%90%E7%A0%81%E8%A7%A3%E6%9E%90.md)
    - Window 的内部机制
        - [Window 的添加过程](https://github.com/shadowwingz/AndroidLife/blob/master/article/Window%20%E7%9A%84%E6%B7%BB%E5%8A%A0%E8%BF%87%E7%A8%8B.md)
        - Window 的删除过程
        - Window 的更新过程
    - [LayoutInflater 源码解析](https://github.com/shadowwingz/AndroidLife/blob/master/article/LayoutInflater%20%E6%BA%90%E7%A0%81%E8%A7%A3%E6%9E%90.md)
    - [setContentView 源码解析](https://github.com/shadowwingz/AndroidLife/blob/master/article/setContentView%20%E6%BA%90%E7%A0%81%E8%A7%A3%E6%9E%90.md)
    - [LayoutParams 解析](https://github.com/shadowwingz/AndroidLife/blob/master/article/LayoutParams%E8%A7%A3%E6%9E%90.md)
    - 四大组件工作过程
        - [Activity 的工作过程](https://github.com/shadowwingz/AndroidLife/blob/master/article/how_activity_start/how_activity_start.md)
        - Service 的工作过程
            - [Service 的启动过程](https://github.com/shadowwingz/AndroidLife/blob/master/article/how_service_start/how_service_start.md)
            - [Service 的绑定过程](https://github.com/shadowwingz/AndroidLife/blob/master/article/how_service_bind/how_service_bind.md)
        - BroadcastReceiver 的工作过程
            - 广播的注册过程
            - 广播的发送和接收过程
        - ContentProvider 的工作过程
    - [ListView 源码解析(未完成)](https://github.com/shadowwingz/AndroidLife/blob/master/article/listview/listview.md)
    - [IntentService 源码解析(未完成)](https://github.com/shadowwingz/AndroidLife/blob/master/article/intentservice/intentservice.md)

- 开源框架源码解析
    - [EventBus 源码解析](https://github.com/shadowwingz/AndroidLife/blob/master/article/eventbus/eventbus.md)
        - [EventBus 注册订阅者源码解析](https://github.com/shadowwingz/AndroidLife/blob/master/article/eventbus/eventbus_register.md)
        - [EventBus 发送事件源码解析](https://github.com/shadowwingz/AndroidLife/blob/master/article/eventbus/eventbus_post.md)
        - [EventBus 解除注册源码解析](https://github.com/shadowwingz/AndroidLife/blob/master/article/eventbus/eventbus_unregister.md)
        - [EventBus 源码 + 注释](https://github.com/shadowwingz/EventBus)
    - [Retrofit 源码解析(未完成)]()
    - [RxJava 源码解析(未完成)]()
    - [Glide 源码解析(未完成)]()

- 性能优化
    - [使用 Looper 检测应用中的 UI 卡顿](https://github.com/shadowwingz/AndroidLife/blob/master/article/use_looper_to_detect_ui/use_looper_to_detect_ui.md)


- 细节知识点
    - `setResult` 调用时机
    - [compileSdkVersion、minSdkVersion、targetSdkVersion 含义](https://github.com/shadowwingz/AndroidLife/blob/master/article/compileSdkVersion%E3%80%81minSdkVersion%E3%80%81targetSdkVersion%20%E5%90%AB%E4%B9%89.md)

