# LOVE 恋爱小记

## 安装依赖
### ```npm  install```

## 启动项目
### ```npm  start```



## 项目详细流程
### 流程图：https://tsfopbhjjj.feishu.cn/docx/doxcnuNfaYf2m5tPnhubAXJQ9QZ

## 数据库设计（表格）
### https://tsfopbhjjj.feishu.cn/sheets/shtcnr8wXxHFm6E24Rak05YxrJe



各页面必要元素
- 登入
  - 邮箱（先验证邮箱格式）
  - 密码（是否在6-10位：必须包含大小写和数字）
- 注册
  - 昵称 （1<=8位）
  - 邮箱（先验证邮箱格式）
  - 密码（在6-10位：必须包含大小写和数字）
  - 确认密码（确认密码是否和上面一致）
  - 实名认证+人脸识别（认证成功之后完成注册）
- 恋爱小记
  - 用卡片的形式展示所有已填的小记
- 添加小记
  - 封面（照片）
  - 标题（必填>10个字）
  - 内容（内容>10个字）
  - 时间（现在的时间）
- 添加伴侣
  - 方式一：扫码
  - 方式二：搜索邮箱
    - 申请列表
      - 缴费500元
    - 邮箱搜索


开发要求
1. 前端使用React脚手架一律使用function组件，禁止使用class 组件
2. 变量命名要有意义，使用驼峰命名法
3. 为保证代码缩进统一，需在VsCode上下载插件Prettier - Code formatter 进行格式化
4. 注意结构化思维，避免把很多个方法写在一个函数上面，也增加了debug的效率
5. 前端主要使用组件库 mui.com ,如需引入别的组件勿全局引用，请选择按需引入
6. 提交时创建一个自己的分支，提交合并代码时请谨慎，可以勿删去别人的代码，建议把vscode升级到最新版本
7. idea?请添加！
