# Laravel Development

Inspect and debug the active Laravel app with Laravel Boost; requires PHP and Laravel Boost in the project.

Install the release archive through OpenAgent Integrations → Plugins. This is an independent adaptation.

## Setup

- PHP on PATH and laravel/boost installed in the active Laravel workspace.

Run /laravel-boost:setup. Package state and credentials belong in the active OpenAgent home at plugin-data/laravel-boost/. Never place secrets in plugin.json or commit them. Refresh the plugin after changing credentials.

## Verification

bun test tests

Bundled tests cover immutable artifacts, config conversion and service configuration and missing prerequisites. Runtime acceptance also verifies a real staged installation, slash-command catalog and integration_status. External account authentication, real provider operations and macOS permissions require the prerequisites above; package tests do not claim those credentials are available.

## 中文

使用 Laravel Boost 查看和调试当前 Laravel 应用，需要项目已安装 PHP 和 Laravel Boost。 安装发布包后运行 /laravel-boost:setup 查看配置要求。凭据和状态保存在当前 OpenAgent 数据目录的 plugin-data/laravel-boost/ 下，修改后刷新插件。

Upstream source and exact revision are recorded in provenance.json. Bundled source remains available for inspection.
