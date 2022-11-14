# select-files

选择文件组件

## Props

<!-- @vuese:select-files:props:start -->
|Name|Description|Type|Required|Default|
|---|---|---|---|---|
|accept|规定通过文件上传来提交的文件的类型|`String`|`false`|image/*|
|multiple|是否支持多选|`Boolean`|`false`|false|
|count|选择的文件数量|`Number`|`false`|1|
|size|选择的文件是否需要限制大小 兆（M）|`Number`|`false`|-|
|lrz|需要图片压缩|`Boolean`|`false`|true|
|quality|图片的压缩比重|`Number`|`false`|0.6|
|format|文件的格式，用作验证|`Array`|`false`|"bmp", "BMP", "gif", "GIF", "jpg", "JPG", "jpeg", "JPEG", "png", "PNG", "tiff", "TIFF"|
|callback|成功的回调方法|`Function`|`false`|-|
|fail|失败的回调方法|`Function`|`false`|-|

<!-- @vuese:select-files:props:end -->


