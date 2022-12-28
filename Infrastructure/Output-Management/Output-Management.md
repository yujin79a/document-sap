# 输出管理
为表单模板的开发和维护、数据组装、呈现和表单的输出确定提供了必要的框架

## 输出控制
S/4HANA引入了一种新的输出管理（OM）风格 [2228611](https://launchpad.support.sap.com/#/notes/2228611)

激活使用新的输出管理框架

Cross-Application Components > Output Control > Manage Application Object Type Activation

输出参数确定，Define Business Rules for Output Parameter Determination
> OPD - Output Parameter Determination 

## 不同的输出框架
### SD Output control (NAST)
> NACE - Message Control

### FI Correspondence
Financial Accounting > Correspondence > Assign Programs for Correspondence Types

打印财务凭证信件，不同的信件类型，分配了程序和对应的变式
> F.61 - Correspondence: Print Requests 

### FI-CA Print Workbench
用于创建标准化传出通信的中央开发环境
> EFRM - Print Workbench: Application Form 

### CRM Post-Processing
后处理框架 （PPF） 在 SAP CRM 中用于计划和处理应用程序文档（如合同或活动）的操作和输出。

## 设置 SAP S/4HANA 输出控制
> 配置后台远程函数调用 （bgRFC）
>
> SBGRFCCONF - bgRFC Configuration 

输出控件使用 bgRFC 来处理输出，在 Define Supervisor Dest 页签，创建 RFC 目标

> 设置存储系统和存储类别

输出控制需要一个定义的存储系统（内容存储库）来保存将呈现的表单输出为 PDF

Cross-Application Components > Document Management > General Data > Settings for Storage Systems

维护，SOMU_DB，Output Management DB Storage

> 设置业务规则框架增强版 （BRFplus）

BRFplus 是一个通用框架，可用于定义和维护业务规则 用于业务应用程序，激活后，导入输出控制的程序 [2248229](https://launchpad.support.sap.com/#/notes/2248229)

For ABAP Workbench: /sap/bc/webdynpro/sap/fdt_wd_workbench

For Object Manager: /sap/bc/webdynpro/sap/fdt_wd_object_manager

For Catalog Browser: /sap/bc/webdynpro/sap/fdt_wd_catalog_browser

> 安装 Adobe Document Services （ADS）

## 打印
SPAD - Spool Administration

SE71 - SAPscript Form 

SMARTFORMS - Smart Forms

SFP - Interactive Forms

## 电子邮件
[Mail 发送配置](/Infrastructure/Mail-Transfer/Mail-Transfer.md)

## EDI
> WEDI - IDoc 和 EDI 基础