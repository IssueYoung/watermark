# watermark
给table加水印

使用方式
$('#table').watermark({
        texts : ["A B C X Y Z"], //水印文字
        textColor : "#FFFFFF", //文字颜色
        textFont : '16px 微软雅黑', //字体
        width : 130, //水印文字的水平间距
        height : 120,  //水印文字的高度间距（低于文字高度会被替代）
        textRotate : -20 //-90到0， 负数值，不包含-90
    })