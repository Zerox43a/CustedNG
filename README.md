### custed2

### 设计原则

- **拥抱变化**: 以最小代价应对上游变更
- **跨平台**: 用 PlatformApi 封装平台接口, 保持对ios, andriod, web, osx (以及之后的 linux, etc) 的兼容性
- **性能**: 将运算量大的函数放入 isolate 中执行
- _More_