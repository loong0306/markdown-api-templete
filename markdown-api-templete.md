## XXX系统对外API接口文档

### 1.1 版本历史
| 日期 | 版本号 | 作者 | 备注 |
| ------------ | ----------- | ----------- | ----------- |
| TIME | VERSION | AUTHER | - |

#### 1.2 接口依赖与服务注册
```xml
<dependency>
    <groupId></groupId>
    <artifactId></artifactId>
    <version></version>
</dependency>
```
```xml
CONFIG: XXX
```
#### 1.3 接口统一返回格式
- 正常返回
```xml
{
  "code": 200,
  "message": "操作成功",
  "result": 某种类型的数据，如：字符串、数字、布尔值、集合等
}
```
- 校验参数错误返回
```xml
{
  "code": 100,
  "message": "参数非法 + 具体错误信息说"
}
```
- 错误返回
```xml
{
  "code": 500,
  "message": "错误信息"
}
```
#### 1.4 全局状态码说明
| 状态码 | 说明 |
| :-------- | :-------- |
| - | - |
| - | - |

* * *

### (1) 接口名称
#### 接口说明：XXXXX

- **URL：**
> [/api/x/xx/xxx](#)

- **支持格式：**
> JSON

- **Method：** 
> GET / POST / PUT / DELETE

- **Request：**
<code>ObjectName</code>

| 请求参数 | 参数类型 | 参数名称 | 备注 |
| :-------- | :-------- | :------ | ------ |
| - | - | - | - |
| - | - | - | - |

- **Response：**
<code>ObjectName</code>

| 返回参数 | 参数类型 | 参数名称 | 备注 |
| :-------- | :-------- | :------ | ------ |
| - | - | - | - |
| - | - | - | - |
