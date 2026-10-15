# 一起A了吧

手机端优先的本地 AA 记账与结算工具，支持家庭、成员、费用录入、分摊结算和账本备份。

## 运行

安装 Node.js 20.19+ 或 22.12+，然后在项目根目录执行：

```bash
npm ci
npm run dev
```

## 功能

- 多活动账本、家庭和成员管理。
- 费用新增、编辑、删除、搜索和筛选。
- 按家庭、人数或指定参与人分摊，支持充值赠送折算。
- 结算建议、分类汇总和可复制账单。
- JSON 导入导出、IndexedDB 本地保存及 PWA 离线应用壳。

## 验证与构建

```bash
npm test
npm run build
```

GitHub Pages 可使用仓库内的 `.github/workflows/pages.yml` 部署。PWA 安装需要 HTTPS 或 localhost。

账本保存在当前浏览器中，请定期导出备份。更换设备或清除浏览器数据前，先保存 JSON 备份。

---

**班底 Zecrew** · 北京韶聪泽明智能科技有限责任公司

[官网](https://zecrew.shaocongzeming.com)
