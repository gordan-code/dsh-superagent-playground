# dsh-superagent-playground

Test repository for dsh-superagent.

## Usage example

dsh-superagent watches this repository. To give the agent a task, open an
issue and mention its account:

> @lucasgoong Add a usage example to the README.

The agent then:

1. replies in the issue thread to confirm the request;
2. works on the change in the background and opens a pull request;
3. posts the pull request link in the same thread for review.

Review the pull request as usual and merge it when it looks right. The agent
does not merge pull requests on its own.

## 怎么运行

安装依赖并构建 dsh-superagent：

```bash
# 安装依赖
pnpm install

# 构建
pnpm build
```
