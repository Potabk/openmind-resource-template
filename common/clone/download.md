下载该[module]

```bash
git lfs install
git clone [git_https_url]
```

如果您想跳过LFS大文件的下载（只保留LFS指针），

请在git clone命令前添加`GIT_LFS_SKIP_SMUDGE=1:`
```bash
git lfs install
GIT_LFS_SKIP_SMUDGE=1 git clone [git_https_url]
```