# Summary
* [SUGO-TSA简介](book-index-tsa.md)
* 数据管理
  * [项目管理](project-management.md)
    * [创建项目](project-management.md#create-project)
    * [数据文件导入](project-management.md#file-access)
    * [日志导入](project-management.md#log-access)
    * [创建子项目](project-management.md#create-son)
  * [数据导入工具](data-import.md)
  * [维度管理](dimension-management.md)
    * [创建维度](dimension-management.md#anchor-1)
    * [维度标签](dimension-management.md#anchor-2)
    * [维度权限](dimension-management.md#anchor-3)
    * [排序与隐藏](dimension-management.md#anchor-4)
  * [指标管理](indicator-management.md)
    * [单维指标](indicator-management.md#anchor-1)
    * [复合指标](indicator-management.md#anchor-2)
    * [指标公式](indicator-management.md#anchor-3)
    * [指标标签](indicator-management.md#anchor-4)
    * [指标权限](indicator-management.md#anchor-5)
    * [排序与隐藏](indicator-management.md#anchor-6)
* [管理中心](mana-company.md)
* [多维分析](analytics/data-index.md)
  * [【案例1：页面浏览量的TOP 10】](analytics/data-index.md#case1)
  * [【案例2：最近30天浏览各页面的访客数变化趋势】](analytics/data-index.md#case2)
  * [界面介绍](analytics/data-index.md#intro)
  * [维度指标](analytics/dimen-quota.md)
  * [查询条件设置](analytics/query-condition.md)
  * [图表类型](analytics/chart-intro.md)
* 单图&看板 
  * [单图概述](analytics/slices&board.md#slices)
  * [数据看板](analytics/slices&board.md#board)
* [日志分析](analytics/log-index.md)
  * [界面介绍](analytics/log-index.md#intro)
  * [搜索/过滤](analytics/search.md)
  * [日志记录](analytics/log.md)
  * [图表统计](analytics/log.md#graphic)
* [监控告警](analytics/monitoring.md)
  * [错误码管理](analytics/monitoring.md#error-code)
  * 接口文档
    * [Sugo Plyql 使用文档](developer/interfaces/sugo-plyql.md)
      * [示例](developer/interfaces/sugo-plyql.md#example)
      * [操作符](developer/interfaces/sugo-plyql.md#operators)
      * [函数](developer/interfaces/sugo-plyql.md#functions)
      * [聚合](developer/interfaces/sugo-plyql.md#aggregations)
      * [JDBC 驱动文档](developer/interfaces/jdbc.md)
      * [下载部署sugo-plyql](/developer/interfaces/download-plyql.md)
      * [路线图](developer/interfaces/plyql-roadmap.md)
    * [Tindex接口使用文档](developer/query/index.md)
      - [查询接口文档](/developer/query/query.md)
      - [lookup使用文档](/developer/interfaces/lookup-jdbc.md)
    * [数据接入](developer/data-access/index.md)
      * [查找MiddleManager与Overlord](developer/data-access/overlord_middlemanager_guid.md)
      * 数据接入文档
        * [csv文件接入](developer/data-access/csv-druid.md)
        * [本地文件接入](developer/data-access/index-task.md)
        * [Kafka接入](developer/data-access/kakfa-druid.md)
        * [kafka动态维接入](developer/data-access/default-kafka.md)
        * [hadoop接入](developer/data-access/hadoop.md)
        * [数据段合并](developer/data-access/merge-druid.md)
      * [parser 类型](developer/data-access/parser.md)