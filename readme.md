<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/NcuSpm-1.23-brightgreen.svg" alt="版本"></a>
  <a href="#"><img src="https://img.shields.io/badge/BackEnd-Node%2BExpress-blue.svg" alt="BackEnd"></a>
  <a href="#"><img src="https://img.shields.io/badge/FrontEnd-Vue%2BAmazeUI-blue.svg" alt="FrontEnd"></a>
</p>

## 项目情况
### 简介：
一直想重构自己学院的官网。项目于2015.12.24正式开始。数据直接从原官网获取。图片等文件则使用爬虫爬取并自动上传到七牛。（图片上传暂未实现）
### 项目后台：
Node+Express
### 数据来源：
Cheerio+Request爬虫。存在项目的json文件中。
### 前端：
使用AmazeUI框架+Vue.js+Vue-loader+Webpack（组件化）
## 项目构思
后台只负责数据的抓取和提供API。前端则通过Ajax获取数据，通过Vue进行列表渲染。
因为数据量比较小，所以没有采用数据库。且也没有在新浪云上找到MongoDB的使用方式。
预期是在服务器上，每十二个小时就去爬取一次网页，然后更新JSON文件,从而达到网页动态更新的效果。
### 地址
[南昌大学公共管理学院](http://www.ncuhr.win)

## 项目结构
![项目结构图](http://7xk109.com1.z0.glb.clouddn.com/QQ%E6%88%AA%E5%9B%BE20151226151519.jpg)