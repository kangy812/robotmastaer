# 电控组培训作业仓库

海南大学 南海鲨战队 · 电控组 · RoboMaster 2027 培训作业。

## 用途

存放 RoboMaster 2027 电控组培训各次作业的代码与文档，按作业分目录，通过 Git 提交到 GitHub。

## 目录约定（按需调整）

```
.
├── README.md
├── .gitignore
└── hw01/            # 第 1 次作业
    ├── src/
    └── README.md    # 本次作业说明、运行方式、遇到的问题
```

## 提交方式

```bash
git add .
git commit -m "hw01: 完成 LED 闪烁实验"
git push
```

## 注意

- 单文件上限 **100 MB**，录制视频请降低分辨率/帧率后再提交。
- 不提交编译产物、IDE 缓存和依赖目录（见 `.gitignore`）。
