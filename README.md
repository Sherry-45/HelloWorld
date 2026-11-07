# HelloWorld

一个用于演示 Git 中央仓库协作流程的 Java 入门项目。

## 运行

```powershell
javac HelloWorld.java
java HelloWorld
```

预期输出：

```text
Hello, World! (updated in workspace-a and workspace-b)
Version: 1.0.0
```

## 分支合并演示

功能分支 `feature/branch-merge-demo` 包含版本信息和文档更新两笔提交。

该分支在推送至中央仓库后，通过非快进合并进入 `main`，从而在提交历史中
保留独立的功能分支记录和合并提交。
