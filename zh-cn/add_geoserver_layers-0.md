# 引用图层

>要想渲染图层,先要在全局地理信息中添加相应的图层引用.  

![图 12](https://s2.loli.net/2022/05/26/jsNTzVWYMARCdhg.png)  
点击![图 13](https://s2.loli.net/2022/05/26/VFAaX4iqotSsTYf.png ) 来添加一个图层记录  
记录所需的字段为:  

* **图层名**  
  用于标识一个业务图层的id,图层名作为图层渲染的主键,会在图层渲染/图层隐藏/图层导出等各项动作中匹配使用,**不能重复**  
  注意不是geoserver的图层名  
* **Geoserver图层名**
  使用的Geoserver图层名称,添加时会在前端获取到的geoserver图层列表中选择  
  ![图 14](https://s2.loli.net/2022/05/26/MOqu9pQSAtwKUj3.png)  
* **样式**  
  geoserver上定义的样式,添加时会在前端获取到的geoserver样式列表中选择  
* **显示类型**  
  图片瓦片/矢量瓦片/矢量图层
