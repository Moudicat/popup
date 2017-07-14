# popup

一个弹出层组件 

## PC端 

* 使用popup
* 该文件为Vue组件
* 使用方法 `import Popup from 'services/popup'` `Vue.use(Popup)`
* 在需要弹出的地方使用 `this.$alert('')`

### message
|  参数  | 描述     |
|:-----:|:------:|
|type|类型     |
|message|内容     |
|duration|超时关闭  |

### messageBox
|  参数  | 描述     |
|:-----:|:------:|
|type|类型     |
|message|内容     |
|title|标题  |
|showClose| 是否显示关闭按钮|
|confirmText| 确认文字|
|cancelText|取消文字|


## 移动端

* 原生ES6
* 使用方法 `Popup.alert({title: '抱歉',message: 'xxxxx'});` 


### toast
|  参数  | 描述     |
|:-----:|:------:|
|message|内容     |
|timeout|超时     |
|position|定位    |

### alert
|  参数  | 描述     |
|:-----:|:------:|
|message|内容     |
|title| 标题  |
|okText|确认键文字|
|okColor|确认键背景色|
|callback|点击回调|
