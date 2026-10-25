# ✈️ Java Aircraft War | Java 飞机大战

**A Java-based 2D arcade game project exploring object-oriented design, event-driven programming, game logic, and software testing.**

**一个基于 Java 的 2D 飞机大战项目，围绕面向对象设计、事件驱动编程、游戏逻辑与软件测试展开实践。**

[English](#english) · [简体中文](#简体中文) · [Features](#features) · [Architecture](#architecture) · [Getting Started](#getting-started)

---

<a id="english"></a>
## 🇬🇧 English

### Overview

Java Aircraft War is a Java learning and engineering project built around a classic 2D arcade shooter. The project provides a practical environment for exploring how object-oriented programming concepts can be applied to an interactive application, from game entities and user input to rendering and gameplay logic.

Beyond the game itself, the repository also includes separate Swing and JUnit demonstration modules, providing additional opportunities to explore Java GUI development and automated testing.

The main goal is to develop a clearer understanding of the complete application lifecycle: **input → state update → game logic → rendering → verification**.

### Key Areas

- **Object-Oriented Programming:** Model game entities and organise application responsibilities through classes and interfaces where appropriate.
- **Event-Driven Interaction:** Handle user input and connect interaction events with application behaviour.
- **Game Logic:** Structure gameplay rules, entity state changes, and interactions between game objects.
- **GUI Development:** Explore Java Swing components and graphical application development.
- **Software Testing:** Use JUnit demonstrations to understand unit testing and test-driven development fundamentals.

### Technical Stack

| Technology | Purpose |
|---|---|
| Java | Core programming language |
| Java Swing / AWT | Desktop GUI and graphics APIs, where used |
| JUnit | Unit testing and test organisation |
| IntelliJ IDEA | Development environment, if using the included project configuration |

### Repository Structure

```text
JAVA_AircraftWar_Base/
├── AircraftWar-base/   # Main aircraft war project
├── JunitDemo/          # JUnit testing examples
├── SwingDemo/          # Java Swing demonstrations
└── README.md
```

### Architecture and Design Considerations

The project provides a foundation for exploring several important software engineering concepts:

**1. Separation of Responsibilities**

Keep game state, entity behaviour, input handling, and rendering logically separated where the existing implementation supports it. This makes the code easier to understand, test, and extend.

**2. Interactive Application Lifecycle**

Understand how input events affect game state, how gameplay logic updates that state, and how the graphical interface reflects the latest state.

**3. Maintainable Object-Oriented Design**

Use clear class responsibilities, appropriate encapsulation, and reusable abstractions to avoid tightly coupling unrelated parts of the application.

**4. Testing and Verification**

Use focused unit tests for logic that can be tested independently, while distinguishing these tests from end-to-end verification of the interactive game.

### Getting Started

**Prerequisites**

- A compatible JDK installed.
- An IDE such as IntelliJ IDEA, or a configured Java build environment.
- JUnit dependencies configured if running the testing examples.

**Run the project**

1. Clone the repository:

   ```bash
   git clone https://github.com/VincentLucifer/JAVA_AircraftWar_Base.git
   cd JAVA_AircraftWar_Base
   ```

2. Open the project in your Java IDE.
3. Locate the main application entry point in `AircraftWar-base`.
4. Configure the required JDK and dependencies.
5. Run the main class to launch the application.

The exact run configuration depends on the project structure and dependency setup.

### Learning Outcomes

This project is intended to strengthen practical understanding of:

- Java classes, interfaces, inheritance, and encapsulation.
- GUI event handling and interactive application development.
- Game-state modelling and application control flow.
- Unit testing and basic software verification.
- Code organisation and maintainability.

### Future Improvements

Potential directions for further development include:

- Introducing a clearly defined game loop and separating update and rendering logic.
- Improving entity lifecycle management and collision-detection logic.
- Adding structured game states, such as menus, active gameplay, pause, and game over.
- Expanding unit test coverage for core game rules.
- Adding build automation and continuous integration.
- Documenting design decisions and measuring performance where relevant.

These are proposed extensions, not claims about functionality already implemented.

---

<a id="简体中文"></a>
## 🇨🇳 简体中文

### 项目简介

Java Aircraft War 是一个基于 Java 的经典 2D 飞机射击游戏项目，旨在通过实际开发理解面向对象编程、GUI 事件处理、游戏逻辑组织和软件测试等核心概念。

除主游戏模块外，仓库还包含独立的 Swing 和 JUnit 示例模块，可用于进一步探索 Java 图形界面开发与自动化测试。

项目关注的不只是游戏功能本身，还包括交互式应用的完整执行流程：

**用户输入 → 状态更新 → 游戏逻辑处理 → 图形渲染 → 功能验证**

### 核心技术方向

- **面向对象设计：** 使用类、接口、封装和适当的抽象组织游戏实体及应用逻辑。
- **事件驱动编程：** 理解用户输入事件如何触发应用行为与状态变化。
- **游戏逻辑建模：** 组织游戏对象、状态更新及对象之间的交互规则。
- **GUI 开发：** 通过 Java Swing 相关示例理解桌面图形界面的开发方式。
- **软件测试：** 通过 JUnit 示例学习单元测试、测试组织与基本验证方法。

### 技术栈

| 技术 | 用途 |
|---|---|
| Java | 核心开发语言 |
| Java Swing / AWT | 桌面 GUI 与图形接口，以实际代码为准 |
| JUnit | 单元测试与测试组织 |
| IntelliJ IDEA | 开发环境，以实际项目配置为准 |

### 项目目录

```text
JAVA_AircraftWar_Base/
├── AircraftWar-base/   # 飞机大战主项目
├── JunitDemo/          # JUnit 测试示例
├── SwingDemo/          # Swing 图形界面示例
└── README.md
```

### 架构与设计思路

**1. 职责分离**

尽可能将游戏状态、实体行为、输入处理和图形渲染划分为清晰的职责模块，降低模块间不必要的耦合。

**2. 交互式应用执行流程**

理解输入事件如何影响游戏状态、游戏逻辑如何推进状态变化，以及界面如何呈现更新后的结果。

**3. 可维护的面向对象设计**

通过明确的类职责、合理的封装和可复用的抽象，提升代码的可读性、可维护性与扩展能力。

**4. 测试与验证**

对能够独立验证的逻辑编写单元测试，并区分单元测试与完整交互流程的功能测试。

### 环境配置与运行

**环境要求**

- 安装兼容版本的 JDK。
- 使用 IntelliJ IDEA 等 Java IDE，或配置好的 Java 构建环境。
- 如需运行测试示例，确保已配置对应的 JUnit 依赖。

**运行步骤**

1. 克隆仓库：

   ```bash
   git clone https://github.com/VincentLucifer/JAVA_AircraftWar_Base.git
   cd JAVA_AircraftWar_Base
   ```

2. 使用 Java IDE 打开项目。
3. 在 `AircraftWar-base` 中定位主程序入口。
4. 配置 JDK、项目依赖及运行参数。
5. 运行主类，启动应用。

具体运行配置取决于项目现有的目录结构和依赖管理方式。

### 项目学习收获

通过该项目，可以系统实践以下内容：

- Java 类、接口、继承与封装。
- GUI 事件处理与交互式应用开发。
- 游戏状态建模与程序控制流程。
- 单元测试与基础软件验证。
- 代码结构组织与可维护性设计。

### 后续改进方向

- 建立职责明确的游戏循环，分离逻辑更新与画面渲染。
- 优化游戏实体的生命周期管理与碰撞检测。
- 引入菜单、游戏中、暂停和结束等结构化游戏状态。
- 扩展核心游戏规则的单元测试覆盖率。
- 添加自动化构建和持续集成流程。
- 记录关键设计决策，并在需要时进行性能测试。

以上为可进一步实现的改进方向，不代表当前版本已经具备这些功能。

---

## License | 许可证

Please refer to the repository's existing license and applicable third-party asset licenses before redistributing the project.

如需重新分发本项目，请先确认仓库现有许可证及第三方素材的使用许可。
