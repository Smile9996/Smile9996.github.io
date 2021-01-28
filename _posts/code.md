## ————***成功状态码***————

### 1

SUCCESS(1,"成功")

### 2

​    FILE_UPLOAD_SUCCESS(2,"文件上传成功")

## ————***未知错误：100-199***————

### 100

​    UNKNOWN_ERROR(100,"未知错误")

### 101    

​	OPERATION_FAILURE(101,"操作失败")

## ————***参数错误：1001-1999***————

### 1001

​    PARAM_IS_INVALID(1001,"参数无效")

### 1002

​    PARAM_IS_BLANK(1002,"参数为空")

### 1003

​    PARAM_TYPE_BIND_ERROR(1003,"参数类型错误")

### 1004

​    PARAM_NOT_COMPLETE(1004,"参数缺失")

### 1005

​    PARAM_ERROR(1005,"参数校验异常"),

## ————***用户错误：2001-2099***————

### 2001

​    USER_NOT_LOGGED_IN(2001,"用户未登录，访问的内容需要验证，请登录")

### 2002

​    USER_LOGIN_ERROR(2002,"账号不存在或者密码错误")

### 2003

​    USER_ACCOUNT_FORBIDDEN(2003,"账号已被禁用")

### 2004

​    USER_NOT_EXIST(2004,"用户不存在")

### 2005

​    USER_HAS_EXISTED(2005,"用户已存在")

### 2006

​    USER_REPEAT_SUBMIT(2006,"数据重复提交")

### 2007

​    USER_NO_ACCESS(2007,"用户无权限访问")

## ————***服务器错误：3001-3099***———— 

### 3001

​    TOKEN_CANT_CREATE(3001,"token创建异常")

### 3002

​    TOKEN_CANT_GENERATE_SIGNATURE(3002,"token签名生成异常")

### 3003

​    TOKEN_EXPIRED(3003,"token已过期失效")

### 3004

​    TOKEN_CANT_DECODE(3004,"token解码异常")

### 3005

​    TOKEN_MISMATCH_ALGORITHM(3005,"token解码算法不匹配")

### 3006

​    TOKEN_CANT_VERIFY_SIGNATURE(3006,"token签名验证异常")

### 3007

​    TOKEN_INVALID_CLAIM(3007,"token载荷失效")

### 3008

​    TOKEN_CANT_VERIFY(3008,"token验证异常")

### 3009

​    TOKEN_EXCEPTION(3009,"token异常")

### 3010

​    TOKEN_MISMATCH_AUDIENCE(3010,"token签发对象不匹配")

### 3011

​    IP_ADDRESS_ERROR(3011,"IP错误，访问失败")

### 3012

​    REQUEST_ERROR(3012,"请求错误")

### 3013

​    FILE_UPLOAD_IO_ERROR(3013,"文件删除IO流错误")

### 3014

​    FILE_UPLOAD_OSS_ERROR(3014,"文件上传OSS错误，未知错误")

### 3015

​    DATA_INTEGRITY_VIOLATION(3015,"违反数据完整性")

### 3016

​    NULL_POINT(3016,"空指针异常")

### 3017

​    TOKEN_IS_NULL(3017,"token为空")

### 3018

​    AUTHENTICATION_ERROR(3018,"身份验证异常")

### 3019

​    AUTHORIZATION_ERROR(3019,"身份授权异常")

### 3020

​    SERVLET_ERROR(3020,"Servlet异常")

### 3021

​    SHIRO_ERROR(3021,"Shiro内部异常")

### 3022

​    ASSERT_ERROR(3022,"断言异常，需结合具体情况判断异常")

### 3023

​    FILE_UPLOAD_FAILURE(3013,"文件上传失败")

## ————***数据库错误：4001-4099***————

### 4001

​    DB_INSERT_ERROR(4001,"数据库插入报错")
