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

- 在仓库设置里面, 设置 `Actions` 如下
  ![image](https://user-images.githubusercontent.com/97134659/185920098-8e62db39-11d0-4404-92ce-f36177b70e9f.png)



  - `API_KEY`: 你的通知[server酱](http://sc.ftqq.com/3.version)的api key，填写之后可以在程序完成打卡之后通知到微信，如果不填写不影响使用(类似的操作)
    ![image](https://user-images.githubusercontent.com/97134659/160978550-d8dd63e0-5faa-4cb5-b623-8deb6a927f4e.png)

 

  -  `STUDENTS`: 批量打卡的学号、地址（用空格分隔）
    ![image](https://user-images.githubusercontent.com/97134659/185920366-a01401a9-df28-46a5-a7a3-15490a54d0b8.png)


   -  `A_NAMES`: 批量打卡的姓名
   ![image](https://user-images.githubusercontent.com/97134659/185920450-98c06de6-4ffb-45df-bc0a-527102738e42.png)


  

- 代码如果已经更改过的，需要保持代码的更新，同步即可
  ![2TI 3ZMMX)YS1 Q`U`O$4}1](https://user-images.githubusercontent.com/97134659/160979763-5446ebf1-7ce7-4021-9b22-4c127df83f05.png)
  ![L2C_A@SDJMNE~5_3F4H(S%E](https://user-images.githubusercontent.com/97134659/160979805-b186f81f-b526-4622-8256-f8585f8938d9.png)


