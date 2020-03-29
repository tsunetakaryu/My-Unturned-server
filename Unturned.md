# Unturned 服务器相关

## WorkshopDownloadConfig.json 模组依赖

配置模组依赖：

在 `"File_IDs"` 中填入所需的模组对应工坊 ID，如需多个模组，可使用英文半角逗号进行分隔。

配置完成后，启动服务器时会检查这些依赖并尝试下载。

下载完成后的模组存放于

> *server_root_folder*\Workshop\Steam\content\304930\

这个路径。



## 备份存档

存档的路径为

> *server_root_folder*\Players\

可用 *TortoiseGit* 进行管理，配合 *FlashFXP* 上传或下载来自 FTP 服务器的内容。