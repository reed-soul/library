# library
一个开源项目集锦，使用git submodule 管理，海纳百川，便于自己学习


## 加载子模块
```shell
git submodule add  git@github.com:vueuse/gesture.git f2e/vue-gesture

git submodule add  git@github.com:mrdoob/three.js.git llm/threejs

git submodule add  git@github.com:mikbry/awesome-webgpu.git web3d/awesome-webgpu
```

## 克隆父仓库时，需要加载子模块。可以使用以下命令
```shell
git clone --recursive <父仓库的远程仓库地址> <本地目录>

```