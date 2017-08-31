# postbirdImageGlass
postbird-img-glass.js 图片放大镜

### 说明:
```
*   图片放大镜
*   Author : Postbird
*   Website: http://www.ptbird.cn
*   License: MIT
```
### 引入方式：
```
src="./js/postbird-img-glass.js
```
### 使用方式：
```
// 示例中使用的方式
PostbirdPictureMagnifyingGlass.init({
    domSelector:".img-container img",
    animation:true
});
```
### 参数说明：
```
init({})传入参数为对象
* domSelector  - dom选择器             默认 img  
* width        - 放大后图片宽度        默认 auto
* height       - 放大后图片高度        默认 auto
* boxClassName - 放大镜的容器的class   默认 postbird-img-glass-box
* boxBgColor   - 放大镜容器的背景色   默认  rgba(0,0,0,0.8)
* animation    - 是否开启CSS3动画     默认 false IE10+ 才有效
```
### 注意事项:
```
1. animation 使用css3动画，需要 IE10+
2. 最低支持 IE9 ，事件监听使用 addEventListener
3. 需要在文档加载完成后才能进行操作 
4. css样式及动画可以将css复制并格式化后，自定义。
```
