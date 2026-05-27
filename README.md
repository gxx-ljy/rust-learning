# rust-learning

## 安装rust
[https://rust-lang.org/zh-CN/tools/install/](https://rust-lang.org/zh-CN/tools/install/)


## 查看版本
```bash
rustc --version
cargo --version
```


## hello world

1. **创建新项目**（二进制程序，默认）：
   ```powershell
   cargo new hello_world
   cd hello_world
   ```

2. **查看生成的 `src/main.rs`**（已经包含 hello world）：
   ```rust
   fn main() {
       println!("Hello, world!");
   }
   ```

3. **编译并运行**：
   ```powershell
   cargo run
   ```

   你会看到：
   ```
   Compiling hello_world v0.1.0 (...)
    Finished `dev` profile [unoptimized + debuginfo] target(s)
     Running `target\debug\hello_world.exe`
   Hello, world!
   ```

## cargo init

```bash
cargo init test-init
cd ..
```

效果一样