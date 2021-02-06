---
layout:     post
title:      保险数据库枚举值对照
subtitle:   
date:       2021-01-28
author:     Smile
# header-img: img/post-bg-cook.jpg
catalog: true
tags:
    - INSURANCES
---

<iframe allow="autoplay *; encrypted-media *;" frameborder="0" height="150" style="width:100%;max-width:660px;overflow:hidden;background:transparent;" sandbox="allow-forms allow-popups allow-same-origin allow-scripts allow-storage-access-by-user-activation allow-top-navigation-by-user-activation" src="https://c.y.qq.com/base/fcgi-bin/u?__=0gsaY"></iframe>

--https://embed.music.apple.com/cn/album/%E6%98%8E%E6%98%8E%E5%B0%B1/584787541?i=584787542
## ————***ENUM***————

### ClaimsPolicy  :

#### 	status :  （理赔单状态）

> **0**：***<s>  保留   </s>***
>
> **1**：已发起，审核中
>
> **2**：审核通过
>
> **3**：已赔付
>
> **4**：已拒赔

### CommonLogger：

#### 	handleType：（操作类型)

> **login**：登录
>
> **select**：查询信息
>
> **update**：更新信息
>
> **insert**：插入信息
>
> **delete**：删除信息
>
> **upload**：上传文件
>
> **excel**：上传ecel
>
> **unknown**：未知
>
> **register**：注册

### DrivingCompany：

#### 	status：（公司状态）

> **0**：***<s>  保留   </s>***
>
> **1**：审核中
>
> **2**：审核失败
>
> **3**：营业
>
> **4**：注销

### DrivingManager：

#### 	level：（驾校管理员等级）

> **0**：***<s>  保留   </s>***
>
> **1**：超级管理员
>
> **2**：管理员
>
> **3**：操作员
>
> **4**：新用户

### FinancialLogger：

#### 	handleType：（操作类型)

> **login**：登录
>
> **select**：查询信息
>
> **update**：更新信息
>
> **insert**：插入信息
>
> **delete**：删除信息
>
> **upload**：上传文件
>
> **excel**：上传ecel
>
> **unknown**：未知
>
> **register**：注册
>
> **pay**：支付

### InsCoManager：

#### 	level：（保险公司管理员等级）

> **0**：***<s>  保留   </s>***
>
> **1**：超级管理员
>
> **2**：操作员

### InsCompany：

#### 	status：

> **0**：***<s>  保留   </s>***
>
> **1**：审核中
>
> **2**：审核失败
>
> **3**：营业
>
> **4**：注销

### InsPlan：

#### 	status：（保险方案状态）

> **0**：***<s>  保留   </s>***
>
> **1**：使用中
>
> **2**：已停用

### InsPolicy：

#### 	status：（保单状态）

> **0**：***<s>  保留   </s>***
>
> **1**：待支付
>
> **2**：出单中
>
> **3**：出单完成
>
> **4**：保障中
>
> **5**：保障期满
>
> **6**：取消保单
>
> **7**：退保

### ProtectionScope：

#### 	protectionProject：（保障项目）

> **0**：***<s>  保留   </s>***
>
> **1**：补考
>
> **2**：重考
>
> **3**：意外身故/意外伤残

### Student：

#### 	sex：（性别）

> **0**：***<s>  保留   </s>***
>
> **1**：男
>
> **2**：女

#### 	licenseType：（报考驾照类型）

> **0**：***<s>  保留   </s>***
>
> **A1**：
>
> **A2**：
>
> **A3**：
>
> **B1**：
>
> **B2**：
>
> **C1**：
>
> **C2**：
>
> **C3**：
>
> **C4**：
>
> **C5**：
>
> **D**：
>
> **E**：
>
> **F**：
>
> **M**：
>
> **N**：
>
> **P**：

#### 	insStatus：（投保状态）

> **0**：***<s>  保留   </s>***
>
> **1**：已投保
>
> **2**：未投保

### StudentClaimsRecords：

#### 	currentExam：（当前考试科目）

> **0**：***<s>  保留   </s>***
>
> **1**：科目一
>
> **2**：科目二
>
> **3**：科目三
>
> **4**：科目四

### studentExamRecords：

#### 	currentExam：（当前考试科目）

> **0**：***<s>  保留   </s>***
>
> **1**：科目一
>
> **2**：科目二
>
> **3**：科目三
>
> **4**：科目四

#### 	licenseType：（报考驾照类型）

> **0**：***<s>  保留   </s>***
>
> **A1**：
>
> **A2**：
>
> **A3**：
>
> **B1**：
>
> **B2**：
>
> **C1**：
>
> **C2**：
>
> **C3**：
>
> **C4**：
>
> **C5**：
>
> **D**：
>
> **E**：
>
> **F**：
>
> **M**：
>
> **N**：
>
> **P**：

### TopupWithdrawOrder：

#### 	orderStatus：订单状态

> **0**：***<s>  保留    </s>***
>
> **1**：订单已提交，待支付
>
> **2**：订单已取消
>
> **3**：订单已完成（支付即完成）

#### 	orderType：（订单交易类型）

> **0**：***<s>  保留    </s>***
>
> **1**：线上充值
>
> **2**：线下充值
>
> **3**：提现

#### 	orderWay：（订单交易方式）

> **0**：***<s>  保留    </s>***
>
> **1**：支付宝
>
> **2**：微信
>
> **3**：网银
>
> **4**：线下打款
>
> **5**：对公转账

### TradeOrder：

#### 	orderStatus：订单状态

> **0**：***<s>  保留    </s>***
>
> **1**：订单已提交，待支付
>
> **2**：订单已取消
>
> **3**：订单已完成（支付即完成）

#### 	orderType：（订单交易类型）

> **0**：***<s>  保留    </s>***
>
> **1**：线上充值
>
> **2**：线下充值
>
> **3**：账单结算
>
> **4**：返现
>
> **5**：理赔
>
> **6**：投保支出
>
> **7**：拒赔

#### 	orderWay：（订单交易方式）

> **0**：***<s>  保留    </s>***
>
> **1**：支付宝
>
> **2**：微信
>
> **3**：网银
>
> **4**：对公转账
