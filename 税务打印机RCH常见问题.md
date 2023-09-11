---
title: 税务打印机RCH常见问题
description: 通过小屏幕/主机桌面弹窗判断
published: true
date: 2023-09-11T15:56:17.049Z
tags: 
editor: markdown
dateCreated: 2023-09-11T11:03:26.398Z
---

# RCH税务打印机常见问题

1.  常见操作键含义
2.  手动打Chiusura（日总结）&日总结图详解
3.  撤销小票
4.  改时间
5.  屏幕上显示：VERIFICA PERIODICA SCADUTA
6.  小屏幕上显示MEM. ESAURITO/DGFE ESAURITO等字样
7.  不打出Chiusura的情况下查看当天已经打出来的票据信息
8.  错误弹窗：ECR PRINTER ERRORE FORMATO DATI
9.  错误弹窗：ERRORE STATO PAGAMENTO FISCALE，小票机连接的显示金额的小屏幕上显示 MANCANO
10.  错误弹窗：ERRO.093 RT INATTIVA 或 ERRO.0078 或 ERR.07 FUN NON AMMESSA
11.  错误弹窗：ECR GLOBE ERRORE FORMATO DATI
12.  错误弹窗：APERTURA LAN IP CONNECTION REFUSED 或 NON CONNECTION（纸上打出来的）
13.  如果所有连接都正常，小票打不出来，弹框也没有
14.  小票不切纸
15.  小票上面不显示IVA值
16.  常见ERRORE（错误）列表
17.  待续

![](/rch-print-f-modalita-rt-comandi-da-tastiera.png)

RCH PRINTER F TASTIERA

![](/reg界面.png)

小屏幕显示REG为默认页面

## 问题1：一些常见按键的含义/组合按键

|     |     |
| --- | --- |
| 按键  | 含义  |
| CL  | 取消，清除。比如输错ip地址信息，按一下CL后可以重新输入 |
| CHIAVE | 指令按键的确认或者理解为打开这个指令的钥匙，要和contanti区分开 |
| CONTANTI | 确认键，可以理解为保存，翻下一页 |
| REPARTO | 左键或者上一页 |
| PREZZO REPARTO | 右键或者下一页 |
| STORNO | 退回，仅是一些操作界面的退回，不是上下页翻页，翻页选择REPARTO/PREZZO REPARTO |
| 1+CHIAVE | 屏幕出现Z/SRV时，按这个会回到REG界面 |
| 点     “.” | 多见于输入ip地址等页面，快速输入三次0可出现 |
|     |     |

## 问题2：怎么打Chiusura（日总结）

保持小屏幕显示为REG界面时（看上述图）

3+Chiave

200+Contanti(此条口令为打当天的Chiusura，如果是有多张未打出，比如显示NON CONNECTION,则需要按422+Contanti）

此时会出2张纸，观察下小屏幕的显示，如果回到REG界面，就不用管，如果显示为Z，则需要按 1 + Chiave 回到REG界面

![](/esempio_di_stampa.png)

ESEMPIO DI STAMPA

## 问题3：改时间

1.  先打一个CHIUSURA(日总结）
2.  在屏幕处于REG界面时，按4+CHIAVE,然后按PREZZO REPARTO到屏幕上出现DATA/ORA,按Contanti
3.  然后按照日GIORNO、月MESE、年ANNO、小时ORE、分钟MINUTI，分别填写正确的数字，每一页写完，按Contanti
4.  分钟（MINUTI）按完Contanti后，屏幕上会重新出现DATA/ORA，想要退出到REG界面的话，按STORNO退出，直到屏幕上出现SRV/Z时，按1+CHIAVE

***注意**，如果输入完DATA/ORA后，屏幕显示了DATA AVANTI(OK/ANNULLA)，则代表，上一次Chiusura的日期大于3天，可以通过REPARTO/PREZZO REPARTO选择OK/ANNULLA，进行保存或者取消本次设定的时间。*

## 问题4：**VERIFICA PERIODICA SCADUTA**

![](/年检.png)

**VERIFICA PERIODICA SCADUTA/年检**

需要进行年检，可以联系老外直接操作，我们的合作方的联系方式为：

Gallorini: 0284638 42/43

ADPE: 3468141169

或者让他们自行联系附近RCH运营点

## 问题5：MEM. ESAURITO/DGFE ESAURITO

出现原因：小票的内存空间不足，需要更换内存卡

联系上述运营商购买，建议不要直接从Amazon购买，有可能会出现购买的不能使用。

更换方式如图，注意内存卡的正反面：

![](/dgfe.png)

DGFE

## 问题6：如何撤销小票

意大利语教程直接看Link

[https://www.youtube.com/watch?v=G5uvHCmFt0E](https://www.youtube.com/watch?v=G5uvHCmFt0E)

中文看下面操作：

1.  按一下键盘上面的SHIFT按键，此时屏幕上也会出现SHIFT字样，
2.  然后按下chiave旁边的红色按键 ANNULLO (ANN-SCO.),此时屏幕上会出现ANNULLAMENTO? SI/NO ,通过REPARTO(左）/PREZZO REPARTO（右）按键，调整括号到SI，按下Contanti
3.  此时屏幕会出现MATRICOLA RT:(一串字母+数字)，这里是确认是当前税务打印机信息，不用管，直接按CONTANTI
4.  屏幕上会出现NUM.AZZERAMENTO:(数字），此时需要拿出我们需要取消的税票，查看税票下方的8位数字，将前面的数字填写在这里，按下Contanti
5.  屏幕上会出现NUM.SCONTRINO:(数字），此时需要拿出我们需要取消的税票，查看税票下方的8位数字，将后面的数字填写在这里，按下Contanti （见下图）
6.  然后分别确认一下日、月、年的填写，按Contanti进行确认
7.  屏幕上会显示步骤4-步骤6的全部数据，也就是要取消的税票的数据，通过REPARTO/PREZZO REPARTO左右调整为SI，后点Contanti
8.  屏幕上会显示ANNULLAMENTO EURO +小票金额，并弹出一张写有ANNULLO SCOTRINO的小票，则代表成功

![](/annullo_scontrino_rch.png)

ANNULLO SCONTRINO NUMERO

## 问题7：读取票据信息

键盘上按"X"，然后按REPARTO，到屏幕上出现LETTURA GIORNALIERA，按Contanti

## 问题8：电脑弹出ECR PRINTER ERRORE FORMATO DATI

![](/ecr_printer_errore_formato_dati.png)

ECR PRINTER ERRORE FORMATO DATI

错误原因：说明菜品中出现了特殊字符，将菜品中特殊字符修改后，此弹窗关闭，再打一次税票

特殊字符包含：中文字体，中文的标点符号（句号。冒号：逗号，分隔符号‘’等），

以及意大利的重音符号：ò à ù è é ç ° § ì

注意：制作菜单时，检查一下这些字符

## 问题9：ERRORE STATO PAGAMENTO FISCALE/MANCANO

![](/mancano.png)

ERRORE STATO PAGAMENTO FISCALE/MANCANO

电脑弹出ERRORE STATO PAGAMENTO FISCALE，小票机连接的显示金额的小屏幕上显示**MANCANO**

错误原因：说明还有小票未打出来

解决方案：

先把弹窗关闭，再将配套的小键盘插入小票机，按一下Contanti，小票就可以出来了，然后再请商家打一张0.01€的小票，试验小票机是否已恢复正常

## 问题10：ERRO 093 RT INATTIVA 或 Errore 0078 或 ERR.07 FUN NON AMMESSA

原因：前一天或很多天没有打出日总结（或打了日总结，但发送失败）

解决方案：将日总结打出来，参考第一条

## 问题11：ECR GLOBE ERRORE FORMATO DATI

![](/globe_errore.png)

GLOBE ERRORE FORMATO DATI

原因：打印机出现错误（打印错误或 打印格式错误）

解决方案：到我的电脑-用户-里面进行更改

## 问题12：APERTURA LAN IP CONNECTION REFUSED 或 NON CONNECTION（纸上打出来的）

原因：小票机网线连接出现问题，需要重置一下连接

解决方案：

1.  确认网线已插入完好，重启小票机
2.  打一下日总结，如果日总结失败并出现non connection

non connection解决方案：

1.  插入配套的小键盘按5+Chiave，
2.  显示金额的小屏幕上出现PASSWORD，输入555  contanti，然后一直按PREZZO REPARTO 按到 Connettività，
3.  然后一下Contanti，然后按2下PREZZO REPARTO，出现Ethernet，按一下CONTANTI，
4.  输入ip地址：10.10.10.8 (注意，这里如果不是这个ip地址，说明之前这个商家也不是这个ip地址，没有关系，原本是什么就是什么，不用修改）
5.  然后按contanti，确认是否是255.255.255.0，如果是，就一直按CONTANTI ，直到出现DNS，设置为10.10.10.1，然后一直CONTANTI 【此处几乎不用修改，都是Contanti一直按下去】
6.  直到小屏幕显示INVIO IN CORSO（正在发送中）
7.  等待一会，会打出来一张可能巨长的纸，屏幕上显示INVIATO CORRETTAMENTE，就说明已经设置成功（可能纸上面大部分会显示INVIATO CORRETTAMENTO,但是个别一两行还是NON CONNECTION,不用管，忽略它）

*一些特殊商家的处理：*

sushi ho bergamo （这家是一个特殊情况）

1、每次打chiusura

第一步，先把税务打印机的网线插到商家外网的modem上面

第二步，把税务打印机的键盘插上去，需要将IP更改为以下数据：

IP ：192.168.178.66（打印机ip，网段是商家自家外网ip）

Subnet Mask ：255.255.255.0

Gateway ：192.168.178.1

DNS : 8.8.8.8

然后按contanti,按四五下之后，变成了STRADA,连着按3遍STORNO,小屏幕上面显示为：SRV,然后按下1+chiave,回到REG界面，

就按一下3+chiave ,422+contanti,然后等待屏幕变成Inviato correttamente就说明发送成功了

等一切都弄完，也打出来纸了，就看一下小屏幕上面，显示的是Z还是REG，如果是reg就不用任何操作，如果是Z，就需要按一下1+chiave,会到REG界面。

## 问题13：如果所有连接都正常，小票打不出来，弹框也没有

解决方案：

打开任务管理器Gestione attività – 详细信息Dettagli ，然后找到MULTIDRIVER\_APP，结束其任务 Termina attività

![](/结束multidriver_app.png)

## 问题14：小票不切纸

1. 只有新商家会出现的问题 每张小票都不切纸：

    5 CHIAVE – 555 CONTANTI – 按PREZZO REPARTO按到OPZIONI FIDELITY 然后按 CONTANTI

    选择NO – CONTANTI – STORNO – 1 CHIAVE

2. 平时其他商家不切纸 就让他们连上键盘按下 CONTANTI

注：都不行的话，可以联系我们长期合作的RCH相关负责人

Gallorini: 0284638 42/43

ADPE: 3468141169

## 问题15：小票不显示iva值

![](/scorporo_iva.png)

SCORPORO IVA

1.  先打CHIUSURA，按4+CHIAVE,然后一直按PREZZO REPARTO，按到屏幕上显示-PROGRAMMAZIONE-SCORPORO IVA，按一下Contanti
2.  按过出现SCORPORO IVA?  通过调整REPARTO/PREZZO REPARTO，选择SI后按下Contanti即可，退出还是按STORNO到屏幕上出现Z/SRV后按1+CHIAVE

## 问题16：常见所有的ERRORE列表

![](/errore1.png)

![](/errore2.png)

![](/errore3.png)

## 待续