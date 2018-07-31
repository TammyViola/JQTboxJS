# JQTboxJS
弹框插件
<p> version 1.0</p>
<pre>
// 弹框状态
// 有五种结果：
// 1.错误(error); 
// 2.成功(success); 
// 3.警告(warning); 
// 4.询问(ask);
// 5.正常(normal), 默认值;
state: 'normal',
 <p></p>
// 弹框出现形式，有两种形式
// 1.点击：'click'; 
// 2.直接弹出：'directOpen',此方式一般用于动态程序判断后
trigger: 'click',

// 设置图标引用路径
// 默认为 'images/'
imgUrl: 'images/',

// 设置弹框自动关闭时间
// 默认值为0，即不自动关闭；
closeTime: 0,

// 是否显示弹框头部
isShowHd: false,

// 头部标题
headTitle: '温馨提示',

// 是否显示确定按钮
isShowConfirm: true,

// 确认按钮文本设置，若是不显示按钮，则设置无效
btnConfirmTxt: '确认',

// 是否显示取消按钮
isShowCancel: false,

// 取消按钮文本设置，若是不显示按钮，则设置无效
btnCancelTxt: '取消',

// 弹框标题
boxTitle: null,

// 弹框内容
boxDoc: null,

// 设置加载完成后事件
onInitFun: null,

// 设置确认事件
onConfirmFun: null,

// 设置取消事件
onCancelFun: null

 </pre>
