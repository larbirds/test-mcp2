# test-mcp2

一个简单的Java项目，包含基本的Main类和单元测试。

## 项目结构

- `src/main/java/com/example/Main.java`: 主类
- `src/test/java/com/example/MainTest.java`: 单元测试类

## 构建和运行

使用Maven构建项目：

```bash
mvn clean install
```

运行项目：

```bash
mvn exec:java -Dexec.mainClass="com.example.Main"
```