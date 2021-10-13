# General License Framework for NFT

## Introduction

本协议框架适用于 NFT 的发行与流转，发行方可以通过[基础协议](docs-cn/basic.md)和扩展协议来对 NFT 的持有人权利进行约束与授权。

## Presentation

本协议需要在 NFT 铸造时由创作者以 `json` 格式显式声明，内容与形式如下：

```json

{
    "repo": "url_for_repo",
    "version": "branch_version",
    "basic": "basic",
    "extended": [
        "D-N-SS-INF",
        "E-35%-Y2",
        "Ru-NB-INF",
        ...
    ]
}

```

上述声明含义为遵循代码库 `url_for_repo` 中版本号为 `branch_version` 的基础协议和扩展协议"[D-N-SS-INF](docs-cn/rights_of_derivative_work.md)"、"[E-35%-Y2](docs-cn/copyright_earning.md)"、"[Ru-NB-INF](docs-cn/rights_to_use_coypright.md)"。

## 协议列表

| Name        | Description  | Abbr. |
| ----------- | ------------ | --------- |
| [basic](docs-cn/basic.md)  | 基础权益 | **basic**   |
| [claimable_asset](docs-cn/claimable_asset.md) | 债权扩展 | **Ca** |
| [copyright_earning](docs-cn/copyright_earning.md) | 版权收益权扩展 | **E** |
| [extra_rights_to_dispose](docs-cn/extra_rights_to_dispose.md) | 附加处置权扩展 | **Rd** |
| [rights_of_dervivative_work](docs-cn/rights_of_derivative_work.md) | 二次创作权扩展 | **D** |
| [rights_to_use_copyright](./docs-cn/rights_to_use_coypright.md) | 版权使用权扩展 | **Ru** |
| [royalty](./docs-cn/royalty.md) | 版税 | **R** |
| ... | | |
