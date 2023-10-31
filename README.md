## [Electron](https://www.electronjs.org/zh/docs/latest/)
###  1.什么是Electron
> Electron 是一个使用 JavaScript、HTML 和 CSS 构建桌面应用程序的框架。 嵌入 Chromium 和 Node.js 到 二进制的 Electron 允许您保持一个 JavaScript 代码代码库并创建 在 Windows 上运行的跨平台应用 macOS 和 Linux—— 不需要本地开发 经验。

- Electron 框架将 chromium和 Nodejs利用 C++ 等原生语言集成起来，提供了一整套基于 Web 的运行环境，并提供了与底层 OS 交互的便捷 API，目的就是为了让大家使用 Web 的技术栈去开发客户端原生应用，从而实现不同操作系统之间的跨平台开发。
- Electron 在实现架构上参考了 Chromium 的核心设计思想，通过主进程进行核心的调度启动，不同的 GUI 窗口独立渲染进程，并提供沙箱安全机制，做到进程间的隔离，进程与进程之间实现了 IPC 通信机制，对主进程提供 Node.js 运行时，封装上层 API，通过 C++ 提供具体系统组件、系统方法能力的实现。
- VSCode、Postman、微信开发者工具、美图云秀

### 2.优势
- 跨平台支持：首先便是跨平台，Electron 框架可在主流的操作系统（例如 Windows、Mac OS 和 Linux 等）上运行，可以有效地减少开发者在不同平台上开发应用程序的工作量和时间。一套代码多平台运行。
- 前端技术支持：通过使用 HTML、CSS 和 JavaScript 等前端技术栈进行开发，拥有大量的 UI 组件和模板，开发出来的桌面应用界面更加美观、交互体验更好。
- 本地能力支持：Electron 除了支持 Web API，而且还允许调用很多操作系统底层 API 来访问计算机的硬件设备，甚至可以自己用 C++、Go 来编写本地模块，可以完成很多 Web 应用无法做到的事情。
- 调试测试支持：Electron 框架开发的应用程序是基于 Chrome 内核的，可以直接使用 Chrome 内核的开发者工具进行调试和测试，提高了开发效率。