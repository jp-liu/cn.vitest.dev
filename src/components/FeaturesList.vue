<template>
  <ul
    class="features-list"
    dir="auto"
    flex="~ col gap-5 md:gap-3"
  >
    <ListItem>可以使用<a target="_blank" href="https://cn.vitejs.dev/"> Vite </a>的配置、转换器、解析器和插件。</ListItem>
    <ListItem>使用您的应用程序中的相同设置来进行测试！</ListItem>
    <ListItem><a href="https://twitter.com/antfu7/status/1468233216939245579" target="_blank">智能检测和即时浏览模式，像用于测试的 HMR ！</a></ListItem>
    <ListItem>可以用于 Vue、React、Lit 等的组件测试</ListItem>
    <ListItem>开箱即用的 TypeScript / JSX 支持</ListItem>
    <ListItem>优先 ESM ， 顶级的 await</ListItem>
    <ListItem>通过 <a href="https://github.com/Aslemammad/tinypool" target="_blank">tinypool</a> 使用 Worker 线程尽可能多地并发运行</ListItem>
    <ListItem>测试套件和测试的过滤、超时、并发</ListItem>
    <ListItem><a target="_blank" href="https://jestjs.io/zh-Hans/docs/snapshot-testing" rel="nofollow">Jest 快照测试</a></ListItem>
    <ListItem><a target="_blank" href="https://www.chaijs.com/" rel="nofollow">Chai </a> 内置断言 + <a href="https://jestjs.io/zh-Hans/docs/expect" rel="nofollow">Jest 预期</a>兼容的 API</ListItem>
    <ListItem>内置用于模拟的 <a target="_blank" href="https://github.com/Aslemammad/tinyspy" rel="nofollow">Tinyspy</a></ListItem>
    <ListItem>用于 DOM 模拟的 <a target="_blank" href="https://github.com/jsdom/jsdom">jsdom</a> 或 <a target="_blank" href="https://github.com/capricorn86/happy-dom">happy-dom</a></ListItem>
    <ListItem>通过 <a target="_blank" href="https://github.com/bcoe/c8">c8</a> 覆盖所有的代码</ListItem>
  </ul>
</template>

<style scoped>
.features-list li {
  list-style: none;
  display: flex;
  gap: 0.4rem;
}

.features-list {
  padding: 0;
}
</style>
