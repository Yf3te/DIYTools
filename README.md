# DIYTools

### DIYTools使用来管理自己工具的一个UI，通过它，我们可以省去频繁翻阅文件夹、打开cmd命令行的时间。对于文件夹结构比较复杂的我们而言，效果甚佳！
![image](https://github.com/user-attachments/assets/aec162bb-b93b-42aa-ada9-58d97a2b534c)
### 我们可以通过填写工具的名称、路径来模拟快捷打开cmd的UI界面
#### 目前只定义了24个工具栏供食用，应该也是绰绰有余
#### 添加（刷新）工具，填入工具名称、路径，然后点击添加工具，即可成功添加，相关工具的配置将保存在当前目录的tool_config.json文件中。
![image](https://github.com/user-attachments/assets/68994bef-d2c9-41f8-bcbb-15fa620536cf)

#### 对于不想用的工具也可以直接删掉，只需要填写左边工具栏中，工具名称，然后重启DIYTools，就会自动删除工具
![image](https://github.com/user-attachments/assets/77d0b58c-5122-4bf8-bf2a-d074b78c06ab)

#### 点击左侧的工具栏，即可跳转到工具界面
![image](https://github.com/user-attachments/assets/ac522526-ed3d-4985-9eaa-adde00a75b57)
执行命令如下
![image](https://github.com/user-attachments/assets/71ff95d1-8378-4dad-8dc8-e9210799d6ad)

#### 现在对工具页面进行说明：
-- 1、点击工具栏后，会把工具的文件名直接填入文本框中，此时可以像cmd一样，直接回车执行，也可以直接点击“执行”按钮

-- 2、也会对执行的命令进行记录，点击历史命令记录即可自动填充到命令栏中

-- 3、刷新按钮，刷新清空文本输出框及其历史记录

-- 4、对于一些需要把结果输出到工具目录下的文中时，我们可以直接点击“打开目录”按钮，实现快捷打开文件夹。


