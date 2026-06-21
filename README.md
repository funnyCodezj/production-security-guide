# 生产环境安全防护操作指南

**Production Security Hardening Guide**

[![Version](https://img.shields.io/badge/version-v1.0-blue)](./guide.md)
[![License](https://img.shields.io/badge/license-MIT-green)](./LICENSE)
[![Last Updated](https://img.shields.io/badge/last%20updated-2026--06--21-lightgrey)](./guide.md)

本指南是一套Web/API 项目生产安全操作基线，覆盖从上线前检查到持续运营的全生命周期纵深防御体系。

---

## 目录

- [概述](#概述)
- [快速开始](#快速开始)
- [特点与亮点](#特点与亮点)
- [适用场景](#适用场景)
- [参考标准](#参考标准)
- [免责声明](#免责声明)

---

## 概述

本指南为部署在云服务器、虚拟机、容器平台或托管平台上的 Web/API 项目提供可验证、可恢复、可持续运营的安全防护基线。文档按阶段组织，涵盖资产识别、账号安全、密钥管理、服务器加固、网络安全、应用安全、数据库保护、备份恢复、监控告警、应急响应等 20+ 个领域。

> 完整文档请阅读 [`guide.md`](./guide.md)。

---

## 快速开始

```bash
git clone https://github.com/<your-username>/production-security-guide.git
```

打开 `guide.md`，按以下步骤推进：

1. **替换占位符**：将 `<DOMAIN>`、`<SERVER_IP>` 等替换为实际值
2. **确定安全等级**：基础级 / 生产级 / 高保障级
3. **按优先级执行**：先完成所有 P0（上线阻断项），再推进 P1、P2
4. **逐项留存证据**：配置变更、命令输出、测试结果、截图等
5. **定期复核**：参考文档中的每日/每周/每月/每季度检查清单

---

## 特点与亮点

- **三级优先级体系**：P0 上线阻断项 / P1 生产必需项 / P2 高保障增强项，明确执行顺序
- **全生命周期覆盖**：从资产识别、威胁建模到应急响应、持续运营，共 20 个阶段
- **证据驱动验收**：每项控制要求留存可验证证据，杜绝"已配置"式应付
- **AI 可执行模板**：提供分阶段 AI 执行提示词，支持自动化安全审计与加固
- **3-2-1 备份策略**：至少 3 份数据、2 种介质、1 份异地副本
- **100 分制评分体系**：量化安全成熟度，明确改进方向
- **中英双语引用标准**：对齐 OWASP ASVS、NIST SP 800-218、CIS Controls v8.1、中国个人信息保护法等

---

## 适用场景

| 场景 | 说明 |
|---|---|
| 初创团队项目上线 | 快速建立安全基线，避免常见漏洞 |
| 企业级 Web/API 系统 | 系统化安全加固，满足合规审计要求 |
| 云迁移安全评估 | 迁移前后安全检查清单 |
| 安全培训教材 | 作为团队安全意识与技术培训参考 |
| AI 辅助安全运维 | 配合 AI Agent 执行自动化安全审计与加固 |

---

## 参考标准

- [OWASP Application Security Verification Standard](https://owasp.org/www-project-application-security-verification-standard/)
- [OWASP Cheat Sheet Series](https://cheatsheetseries.owasp.org/)
- [NIST Secure Software Development Framework SP 800-218](https://csrc.nist.gov/pubs/sp/800/218/final)
- [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework)
- [CIS Critical Security Controls v8.1](https://www.cisecurity.org/controls/v8-1)
- [CISA Multifactor Authentication](https://www.cisa.gov/topics/cybersecurity-best-practices/multifactor-authentication)
- [CISA StopRansomware Guide](https://www.cisa.gov/stopransomware/ransomware-guide)
- [中华人民共和国个人信息保护法](https://www.cac.gov.cn/2021-08/20/c_1631050028355286.htm)
- [非经营性互联网信息服务备案管理办法](https://www.cac.gov.cn/2005-02/09/c_1112147171.htm)
- [数据出境安全评估申报指南](https://www.cac.gov.cn/2025-06/27/c_1752652339765002.htm)

---

## 免责声明

本指南不能保证系统"绝对安全"。它用于建立可验证、可恢复、可持续运营的纵深防御体系，不替代专业渗透测试、合规审查或等级保护测评。涉及个人信息、金融、医疗、跨境数据或特定行业合规时，应由法律或合规专业人员复核。

---

## License

[MIT](./LICENSE)
