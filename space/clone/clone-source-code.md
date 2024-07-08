下载该体验空间源码:

```bash
git lfs install
git clone [link]
```

如果你想跳过LFS大文件的下载（只保留LFS指针），
请在git clone命令前添加`GIT_LFS_SKIP_SMUDGE=1:`
```bash
git lfs install
GIT_LFS_SKIP_SMUDGE=1 git clone [link]
```