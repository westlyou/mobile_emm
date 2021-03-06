# 策略和配置管理

通过策略方案管理，管理员可以设置如何使用已经定义好的策略组。

管理员通过“设备信息管理”、“设备组管理”的指派策略方案功能，将已定义好的策略方案应用到指定的设备上。

## 策略方案管理

点击“策略和配置”->“策略方案管理”菜单进入“策略方案管理”页面：

![](/articles/emm/2-/images/image76.png)

通过策略方案管理，管理员可以设置如何使用已经定义好的策略组。

管理员通过“设备组管理”的指派策略方案功能，将已定义好的策略方案应用到指定的设备上。

## 策略组

通过策略组节点，管理员可以对策略组进行新增、修改和删除等操作。

策略组允许管理员做如下策略设置：

1、 启用解锁密码；如选是则允许管理员从已定义密码策略中选择；

2、 禁止隐私保护；

3、 禁止越狱或Root的设备访问系统；

4、 连接指定WIFI的设备才能访问系统，如果选是则指定对应SSID;

5、 设置设备功能限制策略，从已定义的设备功能限制策略中选择；

6、 设置应用黑白名单策略，从已定义的应用黑白名单策略中选择；

7、 设置应用版本控制策略，从已定义的应用版本控制策略中选择；

点击“策略和配置”->“策略组”菜单进入“策略组”页面，页面左侧列出已定义的策略组，页面右侧策略组详细显示区，可直接对已选中的策略组进行编辑修改。如下图所示：

![](/articles/emm/2-/images/image77.png)

## 密码策略

点击“策略和配置”->“密码策略”菜单进入“密码策略”页面，如下图所示：

![](/articles/emm/2-/images/image78.png)

如果管理员需要接入设备启用密码，那么管理员可以通过“密码策略”定义设备启用密码时，密码应该遵循的密码策略。

iOS密码策略定义如下：

![](/articles/emm/2-/images/image79.png)

Android密码策略定义如下：

![](/articles/emm/2-/images/image80.png)

当管理员在“密码质量”选择复杂密码时，密码策略项多出最少字母数、最少小写字母等等的设置项。

![](/articles/emm/2-/images/image81.png)

## 设备功能限制策略

点击“策略和配置”->“设备功能限制策略”菜单进入“设备功能限制策略”页面，如下图所示：

![](/articles/emm/2-/images/image82.png)

管理员可以通过此策略分别对IOS和Andorid设备上的硬件功能、软件使用进行限制。

iOS可设置限制策略如下：

→ 禁用设备功能

![](/articles/emm/2-/images/image83.png)

→ 禁止访问设备上的应用程序

![](/articles/emm/2-/images/image84.png)

→ 禁止访问iCloud服务

![](/articles/emm/2-/images/image85.png)

→ 强制使用安全与隐私政策

![](/articles/emm/2-/images/image86.png)

→ 控制对应用程序和媒体的访问

![](/articles/emm/2-/images/image87.png)

Android可设置限制策略如下：

![](/articles/emm/2-/images/image88.png)

## 应用黑白名单

如果管理员需要通过黑白名单的方式控制指定的设备可访问或者不可以访问MA，那么管理员可以通过“应用黑白名单”定义应用访问控制策略。

通过点击“策略和配置”->“应用黑白名单”菜单进入“应用黑白名单”页面，如下图所示：

![](/articles/emm/2-/images/image89.png)

选择“白名单”表示：部署此策略的设备只能使用白名单内的APP，不能使用其它APP。

选择“黑名单”表示：部署此策略的设备除了黑名单上的APP不能使用外，可以使用其它APP。

为了应对iOS、Android上不同APP加入黑名单或白名单的情况，支持分别设置iOS、Android应用列表。

应用黑白名单的控制点由服务器端（MA）、设备端两个部分组成。其控制点根据策略定义决定如何控制APP是否可用。

## 应用版本控制策略

应用版本控制策略提供给管理员定义允许使用的APP的最低版本、禁止使用的版本。其控制点由服务器端（MA）、设备端两个部分组成。其控制点根据策略定义决定如何控制某版本的APP是否可用。

通过点击“策略和配置”->“应用版本控制策略”菜单进入“应用版本控制策略”页面，如下图所示：

![](/articles/emm/2-/images/image90.png)

为了应对iOS、Android上不同应用版本控制策略的情况，支持分别设置iOS、Android应用列表。

App最低版本控制和App版本黑名单可以都不选或者都选或者只选其中一个，默认情况下为全部勾选。


