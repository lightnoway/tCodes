## Date 2018-03-27

##切图流程

### 语义

### 盒子

- width ,height
- margin ,border ,padding 

### 定位

- 文字
### 调整

- 对着图片调整
  - 先大后小,先整体后局部
  - ps快捷键
    - **z** 放大
    - **m** 选区
    - **F8** 信息

- 测量
    - 字体大小: 
        - 20以下  **fq** 高度+1 ; 事实
    - 行高 策略
      - 默认约1.3 * font-size ,行高为选中文字背景位置

### 优化

- 样式中的数字尽量不耦合: 设计图调整时,修改尽可能少的数字

## 知识点

### margin合并

- 动机:样式通用,审美紧凑
- 纵轴 && block
- 父子无border
- [ ] 合并小于0时

### 浏览器加载网页
- html => dom; css(dom) ;render(dom);
- [ ] js
### vertical-align
- 相对父元素		子baseline 相对父的
   - baseline : baseline
     - sub		:  subscript-baseline 
        super		:  superscript-baseline  
         text-top : 	top of element's font 
         text-bottom:	bottom of elments' font
         middle	:	baseline + x-height/2
     - 数值
        百分比	: baseline + line-height%
     - 参考 [baseline是什么](https://www.cnblogs.com/xuhaodong/p/basseline.html)
       - ![baseline图片](./images/baseline.png)
       - baseline 英文字母大字本的描线  a 下边,q 在下半部分
       - x-height, baseline 和上面一条线的距离
       - font-size 
          - 英文 fq高度
- 相对 line
  - top	  子top 与 line top
     bottom	子bottom 与 line bottom
     extarea [浏览器差异] 没有定义baseline 位置, 	
### font-size
- px
- em 参照父级比例
- rem 参照跟比例
- xxSmall 参照默认字体大小 
	- [ ]不可设置
### inline-block
### [ ]文档构成: 语义
	- 标题: 多级
		- 网页 1个h1,多个2,
		- h3上有h2
	- 正文
	- 修饰
		- 粗
		- 斜
		- 下划线,删除线
		- 字体,字号,颜色
### [ ] 标签默认样式

### 内部标准

- textarea baseline , 浏览器差异
- 私有默认样式 fieldset,legend,input,file

## 问题

#### [ ] margin:auto 上下居中

- 所在轴:伸展/自动撑开 && 宽度固定 && margin设置auto


- ```css
  .box{
      position:absolute;
      top:0;bottom:0;
      height:100px;
      margin: auto 0;
  }
  ```

#### [ ] img 的width 和 style 里的width 

#### [ ] % 相对父级

-  横轴 (width + padding)%
-  [ ] 纵轴

#### [  ] 定位

- 相对  padding 边界


#### []电脑交互
## 作业注意事项

- 使用:Keywords,description
- 禁止驼峰式命名



## 思考角度

### 编程

- ast 抽象数据结构

### 语义

### 布局

### 交互

### 注意

- 语句,上下文
- 排序重点
- 不阻塞
- 调整情绪
- 今日事今日毕

## 工具

- typora markdown
- pxCook 量图