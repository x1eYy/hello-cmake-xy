# CMake Hello World

一个最小的 CMake/C++ 示例项目。程序运行后输出：

```text
Hello, RoboMaster!
```

## 环境

- Ubuntu 22.04 LTS
- CMake 3.16 或更高版本
- 支持 C++17 的编译器（已在 GCC 11.4.0 下验证）

## 构建

在项目根目录执行：

```bash
cmake -S . -B build
cmake --build build
```

## 运行

```bash
./build/hello
```

预期输出：

```text
Hello, RoboMaster!
```

## Ubuntu 22.04 验证

以下截图展示了项目在 Ubuntu 22.04 LTS 上完成配置、构建并成功运行：

![Ubuntu 22.04 构建运行成功](images/success.png)
