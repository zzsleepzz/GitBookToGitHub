---
description: 设备管理
---

# 设备管理

设备管理

## 修改设备信息 PATCH （http）/device/:id

- 接口描述：修改设备信息

- 请求

    - Body参数

        - 数据类型：json
      
          |   参数   | 类型 | 是否必填 |  描述  | 范围 |   样例   |
          | :------: | :--: | :------: | :----: | :--: | :------: |
          | name | str     |    是    | 名称  |     | 设备1号 |          

    - 样例
    
      ```json
      {
          "name":"设备1号"
      }
      ```

- 响应

    - 样例
      
      ```json
      {
          "code": 0,
          "message": "修改成功",
          "data": nil
      }
      ```
