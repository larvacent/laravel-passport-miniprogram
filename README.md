# laravel-passport-miniprogram

扩展Laravel Passport,支持小程序登录；

## 环境需求

- PHP >= 7.1.3

## Installation

```bash
composer require larva/laravel-passport-miniprogram -vv
```

## 使用

在你的User模型类实现 `findForPassportMiniProgramRequest` 方法接收小程序提交的登录信息。
