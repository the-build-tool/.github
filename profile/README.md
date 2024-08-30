# 工具链

<https://rust-analyzer.github.io/>

```sh
brew install rustup-init

rustc -V 

rustc --explain E0423

cargo new <project_name>

```

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
- [ ] HMR

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


# Rollup

# Vite

> `monorepo`软件开发策略

```sh
npm i treer -g

```

前端交互解耦(FDD)
