# 报价单制作插件

用于将软件、信息化系统、平台、网站、小程序、App 和实施服务需求整理成正式 Excel 报价单。

插件会控制报价条目的颗粒度：避免“用户管理”“数据管理”等空泛描述，也避免把新增、编辑、删除、查看等常规操作拆成大量重复条目。输出沿用插件内置的固定报价模板。

## 安装

在终端运行：

```bash
codex plugin marketplace add https://github.com/Lz020316/quotation-maker
codex plugin add quotation-maker@quotation-maker
```

安装后新建一个 Codex 任务，然后直接提出报价需求，或明确调用：

```text
使用 $quotation-maker:create-quotation，根据下面的项目需求制作正式报价单。
```

## 包含内容

- 固定 Excel 报价单模板
- 需求澄清流程
- 报价条目拆分与合并规则
- 人天、单价、税率和总价检查要求
- 模板格式与打印布局保护要求

## 使用说明

当需求信息会显著影响范围或价格时，插件会先提出关键问题。用户要求先出概算时，插件会明确列出假设和未包含范围，不会擅自补齐高影响需求。
