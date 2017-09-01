
# 提交测评结果
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /evaluation/submitEvaluationAnswer

### 请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ 
 userNumber | 是 | 字符串 | 员工编号 | 
 answer | 是 | 字符串 | 答案json串 |  [{"questionId":"1","answer":"1"},{"questionId":"1","answer":"1"}]

### 请求示例
```javascript
{
	"code": 1,
	"message": "成功"
}

```
