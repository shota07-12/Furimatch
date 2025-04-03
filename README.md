# Furimatch（フリマッチ）

## 概要
フリマアプリ風のLaravelアプリケーションです。

## 使用技術
- Laravel
- PHP
- SQLite
- HTML / CSS（JavaScriptは使用しない）

## セットアップ方法
```bash
git clone git@github.com:shota07-12/furimatch.git
cd furimatch
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve
```bash

## ログイン / 会員登録
- http://localhost:8000/register

- http://localhost:8000/login