# Front End Shared

ð¦ å¼ç®±å³ç¨ç `monorepo` é¡¹ç®æ¨¡ç

## å¿«éå¼å§

### åå»ºä¸ä¸ªæ°çé¡¹ç®

æ§è¡ `node ./scripts/create.js` æ `pnpm run create:pkg`

è¾å¥scopeï¼å¯é
```
ð¤ Input scope(@scope, optional): @scope
```

è¾å¥ååç§°
```
ð¤ Enter a new package name: pkg-ame
```

ç¡®è®¤åå»º
```
ð¤ Enter create @scope/pkg-ame pkg(y/n): 
```

### changeset add

æ§è¡ `pnpm changeset` æ·»å çæ¬è¯´æï¼çæçæ¬æä»¶

### changeset version

æ§è¡ `pnpm changeset version` æ¶è´¹çæ¬æä»¶ï¼ä¿®æ¹é¡¹ç®çæ¬ï¼çæCHANGELOG

### changeset tag

æ§è¡ `pnpm changeset tag` å `git push --follow-tags`ï¼åå»ºçæ¬æ ç­¾å¹¶åæ­¥å°è¿ç¨

### build

æ§è¡ `node ./scripts/build.js` æ `pnpm run build`ï¼èæ¬ä¼æ ¹æ®å½åçæ¬æ¯å¦å­å¨äºè¿ç¨ä»åºï¼æéæå

## publish

æ§è¡ `pnpm changeset publish` æéåå¸

## ç¸å³é¾æ¥

- [changesets](https://github.com/changesets/changesets)
- [pnpm workspaces](https://pnpm.io/workspaces)