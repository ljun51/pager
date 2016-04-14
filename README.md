# pager
分页组件，依赖boostrap.css样式表，通过传入JSON对象实现分页。支持自定义分页大小，分页按钮数量。

#### 用法

1 pager.init(currentPage, pageSize, pageButton); currentPage: 当前页，默认为第一页；pageSize: 每页记录数量;每页按钮数量，按钮数量必须>=6.

2 pager.setLayout(selectorId, jsonData, totalSize, callback); selectorId:分页容器ID; jsonData:JSON对象; totalSize:总记录数; callback:调布局函数.

3 pager.start() 当前页开始记录，pager.end() 当前页结束记录.
