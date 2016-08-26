# jquery-page.js

> 基于jQuery的简易分页组件

* 使用api

  - url: 请求地址
  
  - cb: 回调处理请求结果函数
  
  - opts: 渲染分页组件的config
  
    ```
    {
      "isInitQuery": false,       //初始化是否查询数据
      "currentForm": "body",      //格式： "jQuery(#myForm)" -- 同一页面多个分页组件必传
      "method": "GET",            //默认请求方法
      "currentPage": 0,           //当前页数
      "pageSize": 10,             //默认每页显示条数
      "maxPageNum": 8,            //默认每批最大页面数
      "firstPageNum": 1,          //默认第一个页码数
      "itemsCount": 0,            //总条数
      "pagesCount": 0,            //总页数
      "showCountInfo": true,      //展示数据统计信息
      "showGoBtn": true,          //展示跳转按钮
    }
    ```

  ```
  /*
   * @url
   * @callback
   * @opts
   * exampel: jQuery("#container").Pager(url, cb, opts)
   * author: cycle
   * create date: 2015-08-21
   */
  ```
