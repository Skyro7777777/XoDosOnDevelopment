# 🚀 XoDos on Development Repository  

**⚠️ This emulator is under active development.**  
A lightweight, extensible DOS emulator focused on retro computing and educational use. This repository is a **development fork** of the original XoDos project, created to facilitate community contributions, experimentation, and enhancements.  

---

## 📖 Overview  
XoDos emulates DOS environments to run legacy software on modern systems. Key features include:  
- **x86 instruction set simulation**  
- **Hardware abstraction layer** for peripherals  
- **Configurable memory management**  
- **Cross-platform support** (Windows/Linux/macOS)  

> 🔗 **Original Project**: Learn about XoDos's vision, design principles, and roadmap at the [main repository](https://github.com/xodiosx/XoDos).  

---

## 🛠 Development Setup  

### Prerequisites  
- GCC/Clang or Visual Studio 2022+  
- CMake 3.20+  
- NASM assembler  

### Build Instructions  
```bash  
git clone https://github.com/xodiosx/XoDos.git  
cd XoDos  
mkdir build && cd build  
cmake .. -DCMAKE_BUILD_TYPE=Release  
make -j4  # or use MSBuild on Windows  
