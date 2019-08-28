<!--
 * @Descripttion: 
 * @version: 
 * @Author: Cici
 * @tpl: <-- Created on {createTime} By {author} -->
* 
 -->
# react-native-sechart
[![NPM Version](https://img.shields.io/npm/v/react-native-sechart.svg?style=flat)](https://www.npmjs.com/package/react-native-sechart)
  [![License](http://img.shields.io/npm/l/react-native-sechart.svg?style=flat)](https://github.com/cicistream/react-native-echarts/blob/master/LICENSE)
  
一个webview封装的图表组件。基于百度echarts4，相比native-echarts有echarts自带对象支持，例如渐变色等，用法与官网相同用法。

echarts version 4.2.1

注：react-native 最近几个版本 webview 包改动频繁，安装时请注意需要固定webview的版本，要不然会出现web与react-native通信的问题，导致api无反应，请仔细阅读安装步骤。

fork from [github:shifeng1993/react-native-secharts](https://github.com/shifeng1993/react-native-secharts)

### 1. 修复Unicode问题

```jsx
result = unescape(result.replace(/\\u/g, "%u"));
```

## 以下是示例图

#### 柱状图
![image](https://github.com/shifeng1993/react-native-echarts/blob/master/image/1.gif )

#### 折线图
![image](https://github.com/shifeng1993/react-native-echarts/blob/master/image/2.gif )

#### 饼状图
![image](https://github.com/shifeng1993/react-native-echarts/blob/master/image/3.gif )
