# Autonomous Power Interchange System (APIS)

## Introduction  
近年甚大化する自然災害の影響で、電力システムがダメージを受け、停電が発生するケースが増えている。  
従来の電力システムは火力発電所等の大型発電所から需要地まで長距離の送配電網により電力を供給しており、  
この送配電網が被害を受けると、電力の供給が被害を受けた地点で途絶えてしまう。  
そこで近年マイクログリッドと呼ばれる地産地消型の電力システムが注目されている。  
マイクログリッドは、分散電源を活用し、一定の地域で使用する電力を地域内で発電、配電することで、  
送配電距離を最小化し、自然災害等の障害の影響を最小化するレジリエンスの高い電力システムである。  

我々が提案するAPISはバッテリを分散設置することにより、マイクログリッドの特長であるレジリエンスを  
最大限に高めることができる。また、分散バッテリの協調制御により、分散電源の一つである再生可能エネルギーを  
主電源とした運用が可能となる、サステイナブルな電力システムである。  

## DCマイクログリッド　　
DC（直流）マイクログリッドは、系統とは分離されたDC電力網によりマイクログリッドを構築する。  
系統と分離することにより、系統との周波数同期や、解列・接続動作が不要となり、機械的慣性力を  
持つ発電源に依存しないマイクログリッドを構築することができる。  
特に、分散電源の代表格である太陽光パネルや蓄電池はDCで動作しており、制御の容易性および  
効率面でDCマイクログリッドに対する注目が高まっている。  
従来のDCマイクログリッドでは電圧制御 (ドループ制御) により発電と負荷のバランスを維持している。  
電圧制御では、発電源は高い電圧、負荷は低い電圧に設定することで、発電源から負荷への潮流を制御する。  
電圧制御はグリッドを安定化には有効であるが、発電源と負荷のバランスが取れていることが前提となる。  
例えば、太陽光発電が負荷より大きい場合には発電量が制限され、EV充電等の発電より大きな負荷が  
つながれると十分な電力が供給されない。  


 - [apis-main](https://github.com/oes-github/apis-main)
 - [apis-web](https://github.com/oes-github/apis-web)
 - [apis-main-controller](https://github.com/oes-github/apis-main-controller)
 - [apis-emulator](https://github.com/oes-github/apis-emulator)
 - [apis-dcdc_batt_comm](https://github.com/oes-github/apis-dcdc_batt_comm)
