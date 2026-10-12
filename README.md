# Arnold SKILLS

Arnold 的个人 Claude Code skill 库。

```
/plugin install arnold-skills --marketplace arnold117/Arnold-SKILLS
```

- [grill-wide](skills/grill-wide/SKILL.md)：先广后深地追问方案，按可逆性×影响只深挖关键分支，产出决策文件
- [implement-spec](skills/implement-spec/SKILL.md)：整批实现一份 spec，每票一个 worktree 并行，父会话负责合入和收尾
- [implement](skills/implement/SKILL.md)：按一张票写代码，先实现再用 lean-verify 验证，最后 code review
- [lean-verify](skills/lean-verify/SKILL.md)：实现后用最少的测试证明关键行为正确（v0，未经实战）
- [wayfinder](skills/wayfinder/SKILL.md)：把一个会话装不下的大事画成地图，拆成决定票，一次解决一张

Inspired by [Matt Pocock's skills](https://github.com/mattpocock/skills).
