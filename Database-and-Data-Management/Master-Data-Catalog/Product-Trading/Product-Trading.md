维护物料主数据
## 角色
> SAP_BR_PRODMASTER_SPECIALIST
## App
> Create Material, 创建物料
>
> Manage Product Master Data, 管理产品主数据
## 创建物料
### 基本数据
创建物料, 选择贸易货物, 选择视图 基本数据

![Create-Material-1](./img/Create-Material-1.png "基本数据视图")

在 基本数据1, 输入基本计量单位、物料组、产品组、普通项目类别组, 量纲数据

![Create-Material-2](./img/Create-Material-2.png "基本数据1")

回车跳转到 基本数据2, 点击保存

![Create-Material-3](./img/Create-Material-3.png "基本数据2")

### 销售数据
创建物料, 选择贸易货物, 选择视图 销售数据

![Create-Material-4](./img/Create-Material-4.png "销售数据视图")

选择组织级别, 输入销售范围

![Create-Material-5](./img/Create-Material-5.png "销售范围")

在 销售：销售组织数据1, 维护基本计量单位、交货工厂, 维护税分类

![Create-Material-6](./img/Create-Material-6.png "销售：销售组织数据1")

在 销售：销售组织数据2, 维护物料统计组、项目类别组、物料科目分配组

![Create-Material-7](./img/Create-Material-7.png "销售：销售组织数据2")

在 销售：一般/工厂, 维护可用性检查, 在装运数据, 维护运输组、装载组, 在一般工厂参数, 维护利润中心

![Create-Material-8](./img/Create-Material-8.png "销售：一般/工厂")

如果需要维护国际贸易的控制代码, 选择国际贸易：出口页签

### 采购数据
创建物料, 选择贸易货物, 选择视图 采购

![Create-Material-9](./img/Create-Material-9.png "采购视图")

选择组织级别, 输入工厂

![Create-Material-10](./img/Create-Material-10.png "工厂")

在 采购, 维护基本计量单位、采购组、物料组

![Create-Material-11](./img/Create-Material-11.png "采购")

在其他数据/供应商数据, 维护收货处理时间

![Create-Material-12](./img/Create-Material-12.png "其他数据/供应商数据")

### MRP 数据
创建物料, 选择贸易货物, 选择视图 物料需求计划

![Create-Material-13](./img/Create-Material-13.png "物料需求计划视图")

选择组织级别, 输入工厂、库存地点

![Create-Material-14](./img/Create-Material-14.png "工厂、库存地点")

在 物料需求计划1, 维护MRP类型、MRP控制者, 在批量数据, 维护批量程序

![Create-Material-15](./img/Create-Material-15.png "物料需求计划1")

在 物料需求计划2, 维护计划交货时间、收货处理时间、计划边际码

![Create-Material-16](./img/Create-Material-16.png "物料需求计划2")

在 物料需求计划3, 维护策略组, 可用性检查、总计补货提前时间

![Create-Material-17](./img/Create-Material-17.png "物料需求计划3")

在 物料需求计划4, 维护 独立/集中 需求标识, 在重复制造/装配/展开策略, 维护重复制造、重复制造参数文件

![Create-Material-18](./img/Create-Material-18.png "物料需求计划4")

### 工厂存储数据
创建物料, 选择贸易货物, 选择视图 一般工厂数据

![Create-Material-19](./img/Create-Material-19.png "一般工厂数据视图")

选择组织级别, 输入工厂、库存地点

![Create-Material-20](./img/Create-Material-20.png "工厂、库存地点")

在 工厂数据/存储1, 维护收货单据数、批次管理

![Create-Material-21](./img/Create-Material-21.png "工厂数据/存储1")

### 会计数据
创建物料, 选择贸易货物, 选择视图 会计

![Create-Material-22](./img/Create-Material-22.png "会计")

选择组织级别, 输入工厂

![Create-Material-23](./img/Create-Material-23.png "工厂")

在 会计1, 一般评估数据, 维护评估分类, 在价格和值, 维护价格和价格控制

![Create-Material-24](./img/Create-Material-24.png "会计1")

### 可配置物料
创建物料, 选择贸易货物, 选择视图 基本数据、分类

![Create-Material-25](./img/Create-Material-25.png "基本数据、分类视图")

在 基本数据2, 维护物料是可配置的标识

![Create-Material-26](./img/Create-Material-26.png "基本数据2")

在 分类, 选择类型 300 变式

![Create-Material-27](./img/Create-Material-27.png "分类")

分配变式

![Create-Material-28](./img/Create-Material-28.png "分配变式")

再次创建新的物料, 在 基本数据2, 在一般可配置物料位置, 维护刚创建的可配置物料

### 创建附件
创建物料, 选择贸易货物, 选择视图 基本数据

![Create-Material-1](./img/Create-Material-1.png "基本数据视图")

在应用工具栏, 选择对象的服务, 创建附件, 按提示上载文件

![Create-Material-29](./img/Create-Material-29.png "创建附件")

### 扩展SPP基本数据
创建物料, 选择贸易货物, 选择视图 基本数据、拓展SPP基本数据

![Create-Material-30](./img/Create-Material-30.png "拓展SPP基本数据视图")

在 拓展SPP基本数据 维护计划场景, 组装订购的产品、采购至订单

![Create-Material-31](./img/Create-Material-31.png "拓展SPP基本数据")

### 拓展SPP
创建物料, 选择贸易货物, 选择视图 拓展SPP

![Create-Material-32](./img/Create-Material-32.png "拓展SPP视图")

选择组织级别, 输入工厂、库存地点

![Create-Material-33](./img/Create-Material-33.png "工厂、库存地点")

在 拓展SPP, 维护产品警报、库存计划数据

![Create-Material-34](./img/Create-Material-34.png "拓展SPP")

## 管理产品主数据
### 基本数据
点击创建按钮, 创建主数据记录, 选择产品类型、产品组、基本单位, 确定

![Material-manage-1](./img/Material-manage-1.png "创建主数据记录")

在 基本信息, 维护产品组, 维护多语言描述

![Material-manage-2](./img/Material-manage-2.png "基本信息")

在基本计量单位, 维护毛重、净重, 点击保存

![Material-manage-3](./img/Material-manage-3.png "基本计量单位")

### 销售数据
编辑产品, 选择 分销链 页签, 创建

![Material-manage-4](./img/Material-manage-4.png "分销链")

维护销售数据

![Material-manage-5](./img/Material-manage-5.png "销售数据")

维护分组条件、税分类

![Material-manage-6](./img/Material-manage-6.png "分组条件、税分类")

### 采购数据
编辑产品, 选择 采购 页签, 产品组, 需要在抬头维护

![Material-manage-7](./img/Material-manage-7.png "采购")

### MRP 数据
编辑产品, 选择 工厂 页签, 创建

![Material-manage-8](./img/Material-manage-8.png "工厂")

在基本信息, 维护工厂、利润中心、装载组

![Material-manage-9](./img/Material-manage-9.png "工厂基本信息")

维护MRP数据、批量数据

![Material-manage-10](./img/Material-manage-10.png "MRP数据")

维护采购收货处理时间

![Material-manage-11](./img/Material-manage-11.png "采购收货处理时间")

维护预测数据

![Material-manage-12](./img/Material-manage-12.png "预测数据")

### 工厂存储数据
编辑产品, 选择 工厂 详细信息, 存储地点, 创建

![Material-manage-13](./img/Material-manage-13.png "存储地点")

### 会计数据
编辑产品, 选择 评估范围 页签, 创建

![Material-manage-14](./img/Material-manage-14.png "评估范围")

维护估计范围、评估类, 价格

![Material-manage-15](./img/Material-manage-15.png "评估类")

### 可配置物料
编辑产品, 选择 配置 页签, 维护产品可配置

![Material-manage-16](./img/Material-manage-16.png "配置")

选择 分类 页签, 分配变式

![Material-manage-17](./img/Material-manage-17.png "分类")

选择 变式 页签, 选择产品变式

![Material-manage-18](./img/Material-manage-18.png "变式")

### 创建附件
编辑产品, 选择 附件 - 文档管理服务 页签, 添加链接或上载附件

![Material-manage-19](./img/Material-manage-19.png "附件")

### 扩展SPP数据
编辑产品, 选择 Extendend Service Parts Planning, 未找到页签