# DeleteAccessKey {#reference_xlw_fcn_xdb .reference}

## 接口描述 {#section_whn_4tk_xdb .section}

删除RAM子用户的AccessKey

## 请求参数 {#section_k2y_ptk_xdb .section}

**Action**

-   类型：String
-   必须：是
-   描述：操作接口名，系统规定参数，取值：DeleteAccessKey

**UserAccessKeyId**

-   类型：String
-   必须：是
-   描述：指定要删除的AccessKeyId

**UserName**

-   类型：String
-   必须：否
-   描述：指定用户名

## 返回参数 {#section_vnl_h5k_xdb .section}

只有公共返回参数，详见[公共参数](intl.zh-CN/API参考/API 参考（RAM）/调用方式/公共参数.md)

## 需要的权限 {#section_g22_rtk_xdb .section}

**Action**

```
ram:DeleteAccessKey
```

**Resource**

```
acs:ram:*:${AccountId}:user/${UserName}
```

## 错误信息 {#section_wyy_rll_xdb .section}

**InvalidParameter.UserName.InvalidChars**

-   HTTP Status：400
-   Error Message：The parameter - "UserName" contains invalid chars.

**InvalidParameter.UserName.Length**

-   HTTP Status：400
-   Error Message：The parameter - "UserName" beyond the length limit.

**EntityNotExist.User**

-   HTTP Status：404
-   Error Message：The user does not exist.

**EntityNotExist.User.AccessKey**

-   HTTP Status：404
-   Error Message：The user access key does not exist.

## 操作示例 {#section_pwp_vtk_xdb .section}

**请求示例**

```
https://ram.aliyuncs.com/?Action=DeleteAccessKey
&UserName=zhangqiang
&UserAccessKeyId=0wNEpMMlzy7szvai
&<公共请求参数>
```

**返回示例**

-   XML格式

    ```
    <DeleteAccessKeyResponse>
        <RequestId>04F0F334-1335-436C-A1D7-6C044FE73368</RequestId>
    </DeleteAccessKeyResponse>
    ```

-   JSON格式

    ```
    {
        "RequestId": "04F0F334-1335-436C-A1D7-6C044FE73368"
    }
    ```


