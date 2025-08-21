# 🎓 42 Core Curriculum - Mastering System Programming

<div align="center">

[![42 School](https://img.shields.io/badge/42-School-000000?style=for-the-badge&logo=42&logoColor=white)](https://42.fr/)
[![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=white)](https://en.wikipedia.org/wiki/C_(programming_language))
[![Unix](https://img.shields.io/badge/Unix-System-FCC624?style=for-the-badge&logo=linux&logoColor=black)](https://en.wikipedia.org/wiki/Unix)
[![Norminette](https://img.shields.io/badge/Norminette-✅_Passing-success?style=for-the-badge)](https://github.com/42School/norminette)
[![Grade](https://img.shields.io/badge/Average_Grade-100%2F100-brightgreen?style=for-the-badge)]()

*"The journey of a thousand programs begins with a single 'Hello, World!'"*

</div>

---

## 🎯 The 42 Journey

Welcome to my **42 Core Curriculum** - a comprehensive collection of system programming projects that chronicle the transformation from novice to systems architect. This repository represents hundreds of hours of coding, debugging, peer learning, and algorithmic problem-solving in the unique 42 School environment.

> *"At 42, you don't just learn to code - you learn to think like a computer scientist"*

## 🚀 The 42 Philosophy

### 🌟 Peer-to-Peer Learning
- **No Teachers** - Knowledge flows through collaboration and discovery
- **Project-Based** - Every concept learned through practical implementation
- **Peer Evaluation** - Students evaluate and learn from each other's code
- **Self-Directed** - Independent research and problem-solving skills

### 🔧 Technical Excellence
- **Systems Thinking** - Deep understanding of how computers work
- **Memory Mastery** - Manual memory management and leak prevention
- **Algorithm Design** - Optimization and computational complexity
- **Unix Mastery** - System calls, processes, and inter-process communication

---

## 🏗️ Core Curriculum Architecture

### 📚 Circle 0: Foundation
> *"Every expert was once a beginner"*

| Project | Status | Grade | Description | Core Concepts |
|---------|--------|-------|-------------|---------------|
| [**libft**](./libft/) | ✅ | **100/100** | Custom C library implementation | String manipulation, memory management, linked lists |

**🎯 Learning Focus:** C fundamentals, memory allocation, function implementation

---

### 🔧 Circle 1: System Interfaces
> *"Understanding the tools that build the digital world"*

| Project | Status | Grade | Description | Core Concepts |
|---------|--------|-------|-------------|---------------|
| [**ft_printf**](./ft_printf/) | ✅ | **100/100** | Printf function recreation | Variadic functions, format specifiers, buffer management |
| [**get_next_line**](./get_next_line/) | ✅ | **100/100** | Line-by-line file reader | File I/O, static variables, buffer optimization |

**🎯 Learning Focus:** System I/O, file descriptors, efficient data processing

---

### 🧮 Circle 2: Algorithms & Graphics  
> *"Where logic meets visual mathematics"*

| Project | Status | Grade | Description | Core Concepts |
|---------|--------|-------|-------------|---------------|
| [**push_swap**](./push_swap/) | ✅ | **100/100** | Sorting algorithm optimizer | Algorithm design, complexity analysis, stack operations |
| [**pipex**](./pipex/) | ✅ | **100/100** | Unix pipe recreation | Process management, fork/exec, file descriptors |
| [**fractol**](./fractol/) | ✅ | **100/100** | Interactive fractal explorer | Graphics programming, mathematical visualization, event handling |

**🎯 Learning Focus:** Process lifecycle, inter-process communication, algorithmic optimization, graphics programming

---

### 🐚 Circle 3: Shell Systems
> *"Building the interface between human and machine"*

| Project | Status | Grade | Description | Core Concepts |
|---------|--------|-------|-------------|---------------|
| [**minishell**](./minishell/) | ✅ | **100/100** | Bash shell recreation | Parser design, signal handling, command execution |

**🎯 Learning Focus:** Shell internals, parser implementation, signal handling

---

## 🌟 Project Showcase

### 🐚 Featured Project: Minishell
```bash
minishell$ echo "Hello, 42!" | grep "42" | wc -w
1
minishell$ export PATH="/bin:/usr/bin" && ls *.c | head -5
main.c lexer.c parser.c execute.c builtin.c
```

### 🌀 Featured Project: Fractol
```c
// Mandelbrot set iteration
z = complex_square(z) + c;
if (complex_magnitude(z) > 2.0)
    return iterations;
```

### 🔗 Featured Project: Pipex
```bash
# Equivalent functionality
< input.txt grep "pattern" | sort > output.txt
./pipex input.txt "grep pattern" "sort" output.txt
```

---

## 💻 Technical Stack Mastery

### 🔧 Core Technologies
| Technology | Proficiency | Usage |
|------------|-------------|--------|
| **C Programming** | ⭐⭐⭐⭐⭐ | All projects - systems-level programming |
| **Unix System Calls** | ⭐⭐⭐⭐⭐ | Process management, I/O operations |
| **Shell Scripting** | ⭐⭐⭐⭐⭐ | Automation and testing |
| **Makefile** | ⭐⭐⭐⭐⭐ | Build automation and dependency management |
| **Git** | ⭐⭐⭐⭐⭐ | Version control and collaboration |

### 🛠️ Development Tools
- **Debuggers:** GDB, LLDB - Advanced debugging and memory inspection
- **Profiling:** Valgrind - Memory leak detection and performance analysis
- **Graphics:** MLX42 - Low-level graphics programming
- **Libraries:** Readline - Interactive command-line interfaces

### 📏 Standards & Best Practices
- **42 Norm** - Strict coding standards enforcement
- **POSIX Compliance** - Cross-platform compatibility
- **Memory Safety** - Zero leaks, proper resource management
- **Error Handling** - Robust error detection and recovery

---

## 🚀 Quick Start Guide

### ⚡ Clone & Build Everything

```bash
# Clone the complete curriculum
git clone --recursive https://github.com/danielgessner/42_CoreCurriculum.git
cd 42_CoreCurriculum

# Build all projects
for project in libft ft_printf get_next_line push_swap pipex fractol minishell; do
    echo "Building $project..."
    cd $project && make && cd ..
done
```

### 🎮 Try Each Project

```bash
# Test libft
cd libft && make test

# Experience fractol
cd fractol && ./fractol mandelbrot

# Use your own shell
cd minishell && ./minishell

# Sort numbers optimally  
cd push_swap && ./push_swap 4 2 1 3

# Process with pipes
cd pipex && ./pipex input.txt "cat" "wc -l" output.txt
```

---

## 🧪 Quality Assurance

### ✅ Testing Standards
- **Memory Leak Testing** with Valgrind
- **Norminette Compliance** - 100% passing rate
- **Peer Code Reviews** - Collaborative quality assurance
- **Edge Case Testing** - Robust error handling verification

### 📊 Project Statistics
```
Total Lines of Code:     15,000+
Functions Written:       200+
Projects Completed:      7/13 Projects
Memory Leaks:           0
Norminette Errors:      0
Average Grade:          100/100
Current Progress:        Circle 3 (Core)
```

### 🛡️ Code Quality Metrics
- **Modularity:** Clean separation of concerns
- **Readability:** Self-documenting code with consistent style
- **Efficiency:** Optimized algorithms and memory usage
- **Maintainability:** Well-structured, extensible codebase

---

## 🎓 Learning Outcomes

### 🧠 Systems Programming Mastery
- **Process Management:** Fork, exec, wait, signal handling
- **Memory Management:** Manual allocation, leak prevention, optimization
- **File Systems:** Low-level I/O, file descriptors, permissions
- **Inter-Process Communication:** Pipes, signals, shared resources

### 🔧 Software Engineering Skills
- **Algorithm Design:** Complexity analysis, optimization strategies
- **Parser Implementation:** Lexical analysis, syntax trees, interpreters
- **Graphics Programming:** Pixel manipulation, event handling, mathematics
- **Error Handling:** Robust error detection, recovery, and reporting

### 🎯 Professional Development
- **Code Review:** Peer evaluation and collaborative improvement
- **Documentation:** Clear, comprehensive project documentation
- **Testing:** Comprehensive test suites and quality assurance
- **Version Control:** Advanced Git workflows and collaboration

---

## 🌟 Real-World Applications

This curriculum prepares developers for:

- 🔧 **Systems Engineering** - Operating systems, embedded systems
- 🐧 **DevOps Engineering** - Infrastructure automation, containerization
- 🔒 **Security Engineering** - Vulnerability analysis, secure coding
- 📊 **High-Performance Computing** - Optimization, parallel processing
- 🌐 **Backend Development** - Server systems, API development
- 🎮 **Game Development** - Engine programming, performance optimization

---

## 📈 Project Evolution Timeline

```
Foundation → System I/O → Algorithms & Graphics → Shell Systems
    ↓            ↓              ↓                    ↓
  libft    → ft_printf → push_swap/pipex/fractol → minishell
             get_next_line          
    
Level: Beginner → Intermediate → Advanced → Expert
```

---

## 🎯 Skills Development Matrix

| Skill Category | Projects | Level Achieved |
|----------------|----------|----------------|
| **Memory Management** | libft, all projects | Expert ⭐⭐⭐⭐⭐ |
| **Algorithm Design** | push_swap, minishell | Advanced ⭐⭐⭐⭐ |
| **System Calls** | pipex, minishell | Advanced ⭐⭐⭐⭐ |
| **Graphics Programming** | fractol | Intermediate ⭐⭐⭐ |
| **Parser Design** | minishell | Advanced ⭐⭐⭐⭐ |
| **Process Management** | pipex, minishell | Advanced ⭐⭐⭐⭐ |

---

## 🏆 Achievement Highlights

### 🎯 Perfect Scores
- **100% Norminette Compliance** across all projects
- **Zero Memory Leaks** in production code
- **100/100 Average Grade** - consistent excellence
- **Peer Recognition** through code reviews and collaboration

### 🚀 Technical Milestones
- **15,000+ Lines** of production C code
- **200+ Functions** implemented from scratch  
- **7 Major Projects** completed successfully
- **Advanced Algorithms** designed and optimized

### 🌟 Personal Growth
- **Self-Directed Learning** - Independent problem-solving
- **Peer Collaboration** - Effective team programming
- **Technical Communication** - Clear documentation and code reviews
- **Continuous Improvement** - Iterative refinement and optimization

---

<div align="center">

**Made with ❤️ at 42 Heilbronn**

*Where passionate learners become exceptional developers*

---

*"The beautiful thing about learning is that no one can take it away from you" - B.B. King*

**Current Status:** Core Curriculum In Progress 🚀  
**Next Phase:** Completing Remaining Projects 📚

</div>