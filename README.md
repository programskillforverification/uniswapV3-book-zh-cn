# Uniswap V3 Book中文版

中文/[English](https://github.com/Jeiwan/uniswapv3-book)

本书将引导读者如何开发一个完整的高级的去中心化应用。在本书中，我们将搭建一个去中心化交易所，[Uniswap V3](https://uniswap.org/) 的克隆



## 为什么是Uniswap？
- 它的底层数学原理非常简单，`x * y = k`，然而却十分有效
- 它是一个在简单公式基础上搭建的较为复杂的去中心化应用
- 它是去中心化且经过时间检验的。学习这个在生产环境中运行了数年并且处理了价值几十亿美元交易的应用将会大大提高你的开发水平。


## 本地部署

如何本地部署该书:
1. 安装 [Rust](https://www.rust-lang.org/).
2. 安装 [mdBook](https://github.com/rust-lang/mdBook)
3. Clone the repo:
  ```shell
  $ git clone https://github.com/programskillforverification/uniswapV3-book-zh-cn.git
  $ cd uniswapV3-book-zh-cn
  ```
4. 运行:
  ```shell
  $ mdbook serve --open
  ```
5. 访问 http://localhost:3000/ (或者在你命令行输出中展示的URL)

