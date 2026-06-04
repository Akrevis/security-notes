# web-security-notes

记录自己打靶场、复现漏洞的学习笔记和 writeup，边学边补。

## 内容

- **vulnhub/** — VulnHub boot2root 靶机渗透记录
  - [GoldenEye:1](vulnhub/GoldenEye.md) — 源码信息泄露 → POP3 凭据链爆破 → Moodle 认证后 RCE（CVE-2013-3630）→ overlayfs 内核提权（CVE-2015-1328）→ getroot
  - [Lampião:1](vulnhub/lampiao.md) — Web 侦察 → CeWL+Hydra SSH 弱口令爆破 → 本地枚举 → DirtyCOW 内核提权（CVE-2016-5195）→ getroot

持续更新中。
