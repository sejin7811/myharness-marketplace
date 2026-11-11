# myharness-marketplace

로컬 플러그인 마켓플레이스. Claude Code에서:

```
/plugin marketplace add <이 폴더 경로>
/plugin install myharness@myharness-marketplace
```

포함: agents(verifier, cleaner), hooks(guard: rm -rf · 강제 삭제 · force push 차단), skills(round-close).
guard Hook은 `python` 이 PATH에 있어야 한다.
