# 岩石模量计算平台
Slope Calculator for Rock Mech

## 使用说明

### 计算文件准备

Step.1 文件路径不能出现中文  

Step.2 将文件存成CSV格式  

Step.3 CSV文件列数为2~4，第一行为列名；文件数据应保证不存在缺项行或NULL值。示例如下：  

<img width="368" alt="image" src="https://user-images.githubusercontent.com/73735669/221839810-9d57cd41-71ff-4672-af36-4ea7753a18ee.png">    

Step.4 文件最后一列为【应力】

### 软件操作说明

打开软件，出现以下界面：  

<img width="516" alt="image" src="https://user-images.githubusercontent.com/73735669/221837115-fe435ac4-0c45-46a3-ab93-49d40f79ad6e.png">  

点击右上角的<用户手册>可以查看操作说明：  

<img width="270" alt="image" src="https://user-images.githubusercontent.com/73735669/221837990-bee01e59-c179-4356-af37-b572a64940a9.png"> 

点击<选择文件>按钮，选择文件：  

<img width="516" alt="image" src="https://user-images.githubusercontent.com/73735669/221840273-7a9a2e2a-b737-4d3d-86e5-afd48e582160.png">  

若未选择成功，或对应文件出现问题，会弹出文字提示，这时请重新选择或将计算文件重新保存:   

<img width="516" alt="image" src="https://user-images.githubusercontent.com/73735669/221840701-01d5a4ac-c20f-4c25-8069-5ae6961be8c9.png">  

在对应的位置输入<取样间隔>和<取样范围>，取样间隔值对应M，表示每隔M-1个值计算一次模量，例如M=5，则取样值为[0,5,10,15...]；取样范围值对应interv，表示取样区间为[x-interv,x+interv]。输入完成之后点击<确认提交>。   

<img width="516" alt="image" src="https://user-images.githubusercontent.com/73735669/221842243-28d65f10-a9ce-4139-82fd-cae8141a34a6.png">  

根据实际计算文件的列数选择<源数据列数>：  

<img width="516" alt="image" src="https://user-images.githubusercontent.com/73735669/221842567-fc3016d6-7999-443b-9c94-41ffb6b5c188.png">   

确认所有输入信息正确后，点击<开始计算>按钮，等待数秒后，等待弹出<计算成功！>表明计算结束。  

<img width="516" alt="image" src="https://user-images.githubusercontent.com/73735669/221843270-4bc5dcd4-f494-4804-818a-7d98f535327a.png">   

### 输出文件说明

输出文件与输入文件相同，文件名带有output字样为输出文件，例如：   

<img width="195" alt="image" src="https://user-images.githubusercontent.com/73735669/221844178-2b225937-2617-43ea-b7b7-83c17c2e09fb.png">   

输出文件列对应项与源文件相同。例如，源文件输入列分别为：【轴向应变】，【环向应变】，【体积应变】和【应力】，则输出列分别为【轴向模量】，【环向模量】和【体积模量】。  








## 作者介绍
本科2020级，力学软件专业搬砖工   

四川大学深地科学与工程教育部重点实验室 刘迪   

Email: di_liu9@outlook.com
