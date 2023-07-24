# 输出管理
为表单模板的开发和维护、数据组装、呈现和表单的输出确定提供了必要的框架

## 输出控制
S/4HANA引入了一种新的输出管理 (OM) 风格 [2228611](https://launchpad.support.sap.com/#/notes/2228611)

激活使用新的输出管理框架

IMG > 跨应用组件 > 输出控制 >
管理应用程序对象类型激活

定义用于确定输出参数的业务规则
> OPD - Output Parameter Determination

### 技术设置
[2292571](https://me.sap.com/notes/2292571)
> 配置后台远程函数调用 (bgRFC)
>
> SBGRFCCONF - bgRFC Configuration 

输出控件使用 bgRFC 来处理输出, 在 Define Supervisor Dest 页签, 创建 RFC 目标

> 设置存储系统和存储类别

输出控制需要一个定义的存储系统 (内容存储库) 来保存将呈现的表单输出为 PDF

Cross-Application Components > Document Management > General Data > Settings for Storage Systems

维护, SOMU_DB, Output Management DB Storage

> 设置业务规则框架增强版 (BRFplus) 

[BRFplus](/Infrastructure/Business-Rule-Framework-plus/Business-Rule-Framework-plus.md)
是一个通用框架, 可用于定义和维护业务规则 用于业务应用程序, 激活后, 导入输出控制的程序 [2248229](https://launchpad.support.sap.com/#/notes/2248229)

For ABAP Workbench: /sap/bc/webdynpro/sap/fdt_wd_workbench

For Object Manager: /sap/bc/webdynpro/sap/fdt_wd_object_manager

For Catalog Browser: /sap/bc/webdynpro/sap/fdt_wd_catalog_browser

> 安装 Adobe Document Services (ADS) 

### 配置
[2292539](https://me.sap.com/notes/2292539)

### 新表单模板
[2294198](https://me.sap.com/notes/2294198)

## 不同的输出框架
### Message Control
[Message Control](/Infrastructure/Message-Control/Message-Control.md)

### FI 信函
IMG > 财务会计 (新) > 财务会计全局设置 (新) > 信函 >
定义信函类型

将公司代码分配给信函往来公司代码

创建信函的报告变式, SA38

为信函类型分配程序

信函格式定义发送者明细, 分配文本 ADRS
> SO10 - 标准文本

RSTXTRAN 文本传输

确定调用功能, 可以在不同的位置调用信函输出

开发信函的增强功能, SE38, RFKORIEX

#### 基于 SAPscript 的表格
定义信函格式
> SE71 - 表单

RSTXSCRP 格式导入/导出

定义信函打印的格式名称, 分配程序对应的表单格式

#### 打印信函
打印财务凭证信件, 不同的信件类型, 分配了程序和对应的变式
> F.61 - Correspondence: Print Requests 

### 打印工作台
可以集成, SAPscript Form, Smart Forms, Interactive Forms

SE43 - 区域菜单
> PWB - 打印工作台

#### 表单类
包含基础数据层次结构, 获取数据所需的数据库访问

每个表单类, 必须定义一个表单类库, 报表程序

##### 创建表单类
> EFCS - 编辑

输入表单类名称, 表单类库名称

创建表单级别

#### 申请表
应用程序表单是一个配置对象，从中生成功能模块形式的运行时对象

创建申请表，选择表单类

#### 在 ABAP 程序中调用表单打印

#### 打印流程和打印方案
可以输出到外部设备处理

打印到文件[161516 ](https://me.sap.com/notes/161516) 

### CRM Post-Processing
后处理框架 (PPF) 在 SAP CRM 中用于计划和处理应用程序文档 (如合同或活动) 的操作和输出

## 打印
SPAD - Spool Administration

SE71 - SAPscript Form

SMARTFORMS - Smart Forms

SFP - Interactive Forms

## 电子邮件
[Mail 发送配置](/Infrastructure/Mail-Transfer/Mail-Transfer.md)

## IDoc
[IDoc Interface/ALE](/Infrastructure/IDoc-Interface/IDoc-Interface.md)