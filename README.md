# cube-form

Generate forms visually through the schema

通过统一的schema配置和可视化界面，生成表单

## 架构原型：
https://codesandbox.io/s/blissful-resonance-bgpfn?file=/src/form.tsx

## 已实现特性：
* 列表式配置
* 支持根据其他字段动态改变fields重渲染
* 每个field里的属性支持字段提示
* 支持实际数据类型的转换，比如string -> number
* 配置异步校验
* 嵌套对象和数组


## 待实现特性：
* [ ] 异步数据源以及keyPath、valuePath配置
* [ ] 其他字段变化时，控制当前字段的禁用：disableWhen
* [ ] 新建、更新模式下，是否隐藏、禁用
* [ ] Form.Submit、Form.Reset组件是否需要
* [ ] 可视化配置界面，需要列出每个组件的可配置项，比如Select包括单、多选模式，是否能搜索等。
