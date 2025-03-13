# 工具链

<https://rust-analyzer.github.io/>

```sh
brew install rustup-init

rustc -V 

rustc --explain E0423

cargo new <project_name>

```

> 类型兼容性

```rs
const PI:f64 = 3.141_592_653_59;


fn main() {
  let username:&str = "soetas";
  let mut stars:usize = 789;

  let is_male:bool = false;
  let is_male:&str = "yes";

  static LICENSE:&'static str = "BSD";

  let language = String::from("rust");
  let account:(&str, &str) = ("soetas", "3228891558@qq.com");
  let (username, email) = account;

  let status_code = 500;
  let status_text = match status_code {
      200 => "Ok",
      201 => "Created",
      302 => "Found",
      404 => "Not Found",
      500 => "Internal Server Error",
      _ => "Other"
  };

  let colors = vec!["pink", "orange", "skyblue", ];
  let languages:[&str;3] = ["rust", "go", "python",];

  for i in 0..=10 {
      println!("{}", i);
  }
  
  for color in colors.iter() {
      println!("{}", color);
  }

  loop {
    
  }


  // macro  
  println!("");
  

}

```

> 第一性原则


# Webpack

> 增量构建

**自动化测试、构建和部署**

- [ ] 源码压缩混淆
- [ ] JS版本兼容性
- [ ] Source Map（`[inline-|hidden-|eval-][nosources-][cheap-[module-]]source-map`）
- [ ] 持久化缓存
- [ ] 并行构建
- [ ] 缓存优化二次构建
- [ ] 模块热替换(HMR)和热加载
- [ ] 代码分离
- [ ] 预获取和预加载

```js
if(module.hot) {
  module.hot.accept('', ()=>{

  })
}

```


```html
<link rel="prefetch" as="script" href="http://localhost:8080/share.bundle.js">


```

```sh
curl 

wget

npm i speed-measure-webpack-plugin thread-loader webpack-bundle-analyzer -D

npm i node-gyp -g

git diff --name-only

```

构建产物优化:

- 代码分割（code split）
- polyfill
- 分包
- 移除死代码（tree shaking）
- 资源压缩
- 外链CDN
- 公共模块构建

> Module Federation

[雅虎军规](https://chenoge.github.io/2018/07/03/%E9%9B%85%E8%99%8E%E5%89%8D%E7%AB%AF%E4%BC%98%E5%8C%96%E7%9A%8435%E6%9D%A1%E5%86%9B%E8%A7%84/)

```html
<script cross-origin="false" src=""></script>

```

> `chunkhash`和`contenthash`

<https://terser.org/>

> UMD模块化解决方案

<https://webpack.github.io/analyse>


# Rollup

# Vite

> `monorepo`软件开发策略

```sh
npm i treer -g

```

前端交互解耦(FDD)

=====================================================
# Parsers

- [babel]()
- [acorn]()
- [uglify-js]()

# Transformer

- [babel]()

# Test Runner

- [mocha]()
- [jest]()
- [tape]()
- [ava]()

# Minifier

# Resolver

# Linter

- [eslint]()

# Formatter

- [prettier]()
- [eslint]()

# Bundlers

- [webpack]()
- [vite]()
- [rollup]()

# Monorepo tool


# Linter

## eslint

# Formatter

## prettier

# Refactor

1. [代码整洁之道](https://gitee.com/GARRYCODE/Clean-Code-Collection-Books/raw/master/clean%20code-%E4%BB%A3%E7%A0%81%E6%95%B4%E6%B4%81%E4%B9%8B%E9%81%93(%E4%B8%AD%E6%96%87%E5%AE%8C%E6%95%B4%E7%89%88-%E5%B8%A6%E4%B9%A6%E7%AD%BE).pdf)
2. [重构](https://book-refactoring2.ifmicro.com/ebook/refactoring2.pdf)
3. [Vue.js设计与实现](https://gitee.com/mewcoder/fe-book/raw/master/Vue.js%E8%AE%BE%E8%AE%A1%E4%B8%8E%E5%AE%9E%E7%8E%B0.pdf)

# CodeReview

# Git Hooks

## husky

## lint-staged

<https://voidzero.dev/>




