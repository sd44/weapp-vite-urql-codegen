# weapp-vite + @urql/core + graphql codegen

+ `weapp-vite` 集成 `tailwindcss`, `tdesign` 的模板
+ `@urql/core` 作为小程序的 `graphql` 客户端
+ codegen 生成类型完整的 ts，见 `codegen.ts`


## 使用方式

### 实现代码
见 `src/utils/`. 含 `URLSearchParamsPolyfill`, `urql`, `codegen` 使用方法

### 开发

- `bun dev`

- `bun dev --open` 可以打包并直接启动微信开发者工具

### 构建

`bun build`

### 打开微信开发者工具

`bun open`

### 生成组件/页面

`bun g path/to/your/component`

## 文档地址

0. `weapp-vite`: https://vite.icebreaker.top/
1. `weapp-tailwindcss`: https://tw.icebreaker.top/
