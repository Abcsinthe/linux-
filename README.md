# sys-info.sh

## 功能

`sys-info.sh` 是一个 Bash 脚本，用于收集当前系统的信息，包括：

- 当前用户
- 当前系统时间
- CPU 负载情况
- 磁盘使用情况
- 当前内存使用情况

所有输出结果将保存到 `system-report.txt` 文件中。

## 使用方法

1. 打开终端并导航到脚本所在的目录。
2. 确保脚本具有执行权限：

   ```bash
   chmod +x sys-info.sh



# create-users.sh

## 功能

`create-users.sh` 是一个 Bash 脚本，用于从 `user-list.txt` 文件中读取用户列表并创建相应的用户。如果用户已存在，脚本将跳过该用户的创建，并输出提示信息。

## 使用方法

1. **创建用户列表文件**

   确保存在一个名为 `user-list.txt` 的文件，文件中包含要创建的用户名，每行一个。例如：
   Bob
   Alice
   Caveil
   Davide
   2. **打开终端并导航到脚本所在的目录**。

3. **给予脚本执行权限**：

```bash
chmod +x create-users.sh
