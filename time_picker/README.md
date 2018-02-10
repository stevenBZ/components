### 时间选择控件

使用方法:

1.引入jquery

2.引入fontawesome文件

3.引入脚本文件borain-timeChoice.js和样式文件css/borain-timeChoice.css

4.在HTML文本中使用input标签，定义class

如:
```
<input class="start" type="text" value="" />
```
5.在脚本中调用onLoadTimeChoiceDemo()创建日历结构

6.调用 
```
borainTimeChoice({
        start,
        end,
        level,
        less
    });
```
  来启动控件

### 参数说明
|param|说明|
|--|--|
|start|起始日期input的class名，必须|
|end|结束日期input的class名，非必须，为空时填null或""|
|level|evel分为 YM YMD H HM HMS 5个有效值，分别表示年月、年月日、年月日时、年月日时分、年月日时分秒|
|less|less表示是否不可小于当前时间|

使用例子参见index.html