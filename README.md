# MaoTai_GUI 可视化（即 exe 可运行文件）

JD 京东抢购、京东抢茅台 Windows 端、开箱即用无需配置环境。开发在即（开源协议采用 Apache License）

首先感谢无名作者提供部分代码思路，根据原作者部分代码，所采用 Apache License2.0 开源方式。

~~脚本软件开发调试中具体情况等待回复~~
<br/>


# 免责声明
感谢您使用本程序的开源代码/程序。在下载和使用此代码/程序之前，请仔细阅读并理解以下声明。

1. 保护知识产权：本程序的开源代码受版权法和相关法律的保护。作者享有其代码的所有权利，包括但不限于著作权、专利权和商标权。未经作者许可，禁止以任何形式侵犯这些权益。
2. 学习交流目的：本程序的开源代码仅供学习和交流使用。下载者应将其用途限定在个人研究、学习或非商业项目中。严禁将本代码用于任何违法、侵权、破坏性或其他有害行为。
3. 法律合规性：下载者应遵守所在地的法律法规，并承担使用本代码所产生的一切法律责任。对于因使用本代码引起的任何损失或法律纠纷，作者概不负责。
4. 删除义务：下载者同意，在下载、使用或停止使用本程序的开源代码后，应在24小时内彻底删除该代码/程序及其衍生物。此举旨在保护作者的知识产权和隐私。
5.  免责声明的限制：本免责声明不排除或限制适用于法律规定的任何责任。在适用法律允许的最大范围内，作者不对使用本程序代码所导致的任何直接或间接损害承担责任


请务必仔细阅读并理解以上声明。下载、使用本程序的开源代码即表示您同意遵守上述规定并承担相应的法律责任。

### 周末考试，暂停捐赠。下周开放。（已捐赠用户不受影响） 

~~**唯一联系捐赠方：zcsupercn@foxmail.com**~~



## 看教程/捐赠前你需要知道的几件事
1. 秒回+远程协助时间为 工作日 9：00~18：00 其余时间恢复甚慢！
2. 觉得软件一定能够抢到的用户，我建议直接原价买茅台。
3. 重新写教程的目的是发现指导用户实在太太太浪费时间了，根本没法专心开发。这就导致版本更新慢，甚至错误。
4. 所以以后我会缩短自己指导的时间，专心研发。
5. 盗版售卖用户猖狂，特别是我下面曝光的这一位，我希望能够利用各位的能力解决掉恶意售卖的骗子。
6. 这段时间我想了很多，骗子真的特别影响开发者维护的心态。如果盗版依旧存在，本人永久停止维护。
7. 捐赠用户得到的是源代码+软件。可以递给亲朋好友使用。传播量大JD秒封。

## 使用教程

**<a href='https://docs.qq.com/doc/DR2RwZ0t5dXBZbGJr'>【必看】拿到软件后我应该知道什么or做什么？</a>**

**<a href='https://docs.qq.com/doc/DR0VWbUl0cVVva3hG'>【必看】如何查看我抢购成功或失败？</a>**

**<a href='https://docs.qq.com/doc/DR2ZGVmphcHREQkJw'>安卓手机如何抓包(正在写)</a>**

**<a href='https://docs.qq.com/doc/DR2d5ZHdtRG9hRFRl'>苹果手机如何抓包</a>**





## 更新日志：
### 2023年10月13日
- 周末前临时改个问题。
- **修复了JD中文用户名无法登录，无法预约抢购报错{'login':-1} 问题**
- 如果你是中文用户名，请联系我远程协助。
- 谁是骗子我不说，聪明人看下GitHub首页 commit代码历史就可以。本人21年正式接触编程工作。技术栈分别为 前端vue react、小程序、Flutter移动开发 、Python开发。
- 论资质，论经验，论技术，我谁都比不过，唯一被我踩在脚底的，就是我曝光的骗子。

### 2023年10月13日（12日晚）
 - 紧急修复！！！请所有捐赠者找我要代码！！！
  - 修复了抢购时候出现的登陆失败{login：-1}
  - 修复地址错误
  - 更改Sign算法
  - 提前30分钟自动预约

# 警惕骗子！！！

## **<a href='https://docs.qq.com/doc/DR3dnamJaeVpYRHlG'>点我查看骗子详细信息</a>**

- 骗子QQ：2335625964
- 骗子QQ：2972306946
- 骗子微信：yc2335625964

**骗子第一个仓库地址为：https://github.com/huawei-hw/JD-2023-10-8**

**骗子第二个仓库地址为：https://github.com/BigC5201314/jd**


## 更新日志：

### 2023年10月11日
- Cookie一键配置（取消多文件来回修改）
- 其他参数简化配置 （小白也可配置）
- 压缩包增加了Windows的python环境安装包，便携安装
<br/>
<img src='imgs/1011addconfig.png' width='40%' />
  

### 2023年10月8日
- 再次修复了JD服务器时间戳错误不准确问题
- （这次是实打实JD服务器返回时间）
<br/>
<img src='imgs/NowTime.png' width='40%' />

### 2023年10月6日

- 修复了JD获取时间戳的问题，以前可能存在误差过大的情况。
<br/>
<img src='imgs/jdtime.png' width='40%' />

### 2023年9月27日

- 增加了多线程执行功能，这将提高程序的执行效率和性能。

<br/>
<img src='imgs/gui1.png' width='40%' />
<br/>
<img src='imgs/gui2.png' width='40%' />


（前端、后端、小程序、python 等定制化开发其他软件请联系：zcsupercn@foxmail.com）

- 2023 年 9 月 20 日


  ## 其他说明
  ### 2023年10月13号说明：
- 目前为止，骗子依旧拿我的代码继续骗钱。
- 昨天紧急更新了下，有聪明的朋友看见我新增了华为的抢购测试代码逻辑。本来我以为没改好，但是经过多个用户测试，确实能够参与抢购（图在下面）。但是我本人不做保证。
- 从今天的从九点钟到十点，我远程了11个人。**没有一个人看Github的教程**
**合着我自己照着我的教程给你们解决问题**
  我还有时间写代码吗？从现在开始，有任何问题看教程。如果教程有说明的，**不做任何回复**（安卓抓包教程正在写）

- 不建群，软件下午免费开放。已经很久不维护了。代码才是最新的。

- 华为抢购图：

  <img src='imgs/hw1.png' width='40%' />
  <img src='imgs/hw2.png' width='40%' />

### 此脚本分为两种运行模式

- Python 脚本即时运行模式

- Windows7 及以上 exe 运行模式






