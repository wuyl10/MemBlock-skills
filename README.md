# MemBlock-skills

面向 RISC-V nanhu核内 设计、验证流程。每个 skill 是一个独立 repo，通过 git submodule 聚合在这里方便统一管理。

## 当前包含的 skill

| skill | 作用 |
| --- | --- |
| [hyptest-workflow](hyptest-workflow/) | 把测试意图落成可追踪的 hyptest case，含编译、运行、分层、反标 |
| [hyptest-failure-triage](hyptest-failure-triage/) | 把 selfcheck_fail / stuck / difftest mismatch 推进到分类结论和报告 |

每个 skill 的详细用法看各自目录下的 `README.md`（用户视角）和 `SKILL.md`（agent 执行规则）。

