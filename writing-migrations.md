# 迁移脚本

Phinx 使用迁移脚本来管理数据库。 每个迁移脚本都是一个 PHP 类。首选使用 Phinx API 来写迁移脚本，但是纯 SQL 语句也是支持的。

## 创建迁移脚本

### 生成一个迁移脚本框架

让我们从创建一个新的 Phinx 迁移脚本开始。使用 `create`
