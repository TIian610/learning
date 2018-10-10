### git结构

* 工作区 ---(add)---> 暂存区 ---(commit)---> 本地库

* 示意图

  ![](C:\Users\narli\Desktop\learning\Git\02.git工作结构+配置\images\git结构.png)

  


### git配置

* git在使用前要配置使用者的信息，包括用户名和邮箱，不允许不设置

* 两类配置

  | 分类         | 说明                                                         | 配置                                                         |
  | ------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
  | 系统级别配置 | 不同的仓库都使用这份配置                                     | git config --global user.name tom<br />git config --global user.email hello@outlook.com |
  | 仓库级别配置 | 只有当前仓库使用这份配置<br />当既有系统配置又有仓库配置时，以仓库配置为准 | git config user.name tom<br />git config user.email hello@outlook.com |

* 配置存放路径：**~/gitconfig**