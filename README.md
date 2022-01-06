# i至诚自动化打卡

## 源码开源，仅用于学习

### 无服务器使用（无脑，推荐），使用 GitHub Actions（流程很简单 只要加学号、省、市、区就行）

经过测试，大概在凌晨一点半的时候打卡成功

使用步骤:

- 点击右上角 `Star` 

 ![image-20211023223415973](https://img2020.cnblogs.com/blog/1535189/202110/1535189-20211024011444420-1054435861.png)

- 克隆这个仓库到你名下：点击右上角 `Fork` 

 ![image-20211023223437524](https://img2020.cnblogs.com/blog/1535189/202110/1535189-20211024011444220-574369804.png)

- 第一次使用需要确认：点击 `Actions` ，然后点击 `Enable workflow` 启用工作流

![屏幕截图 2021-10-24 012114](https://img2020.cnblogs.com/blog/1535189/202110/1535189-20211024012336869-1205037702.png)

![image-20211024012249533](https://img2020.cnblogs.com/blog/1535189/202110/1535189-20211024012336425-986933813.png)

- 在仓库设置里面, 设置 `secrets` 如下

  - `API_KEY`: 你的通知[server酱](http://sc.ftqq.com/3.version)的api key，填写之后可以在程序完成打卡之后通知到微信，如果不填写不影响使用(类似的操作)
  - `stuID`: 你的学号

    ![image-20211024004751004](https://img2020.cnblogs.com/blog/1535189/202110/1535189-20211024011443749-1912034824.png)
  -  `province`: 省
  
  ![D(K(@Y}7O G_78RZPJ_N4KX](https://user-images.githubusercontent.com/97134659/148385246-3daf1486-28c0-46f4-9477-70bfe8d7ea1a.png)
  -  `CITY`: 市
  
  ![V1GE{M89U5T 1`N8X3V{@_6](https://user-images.githubusercontent.com/97134659/148385474-c6937ec9-bf27-49fe-b06f-355c16bee75d.png)
  -  `REGION`: 区
  
  ![JPN_BCM(B9( R9D(HR_NWN9](https://user-images.githubusercontent.com/97134659/148385591-a922d148-f3f9-45cd-84b6-33efa5b7e80f.png)
  -  `stuIDs`: 批量打卡的学号（目前只支持单一地址，比如都在学校）
  
  ![批量打卡](https://images.cnblogs.com/cnblogs_com/Lin1031/1924181/o_211128122132_%E5%BE%AE%E4%BF%A1%E5%9B%BE%E7%89%87_20211128202040.png)

- 代码如果已经更改过的，需要保持代码的更新，同步即可

![image-20211024003508381](https://img2020.cnblogs.com/blog/1535189/202110/1535189-20211024011443314-1404804501.png)


