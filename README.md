# CMake Playground

`CMakeLists.txt` 공부 프로젝트.

## 개발 환경

- OS: Windows 11 Pro 24H2
- IDE: Visual Studio Code

## 프로젝트 구조

```
cmake-playground/
├── CMakeLists.txt
├── src/
│   └── main.cpp
└── README.md
```

## 시작하기

프로젝트 클론 및 빌드 단계:

1. 저장소 클론:

   ```powershell
   git clone https://github.com/jeongroseok/cmake-playground.git
   cd cmake-playground
   ```

2. 빌드 디렉토리 생성 및 빌드:

   ```powershell
   mkdir build
   cd build
   cmake ..
   make
   ```

3. 실행:
   ```powershell
   ./build/<Debug or Release or ...>/<CMakeLists.txt의 TARGET 값>.exe
   ```

## 경험을 통해 배운 것들

### clang 사용

Visual Studio Code의 clangd 확장 프로그램만 사용하고 기존 C++ 확장 프로그램은 비활성화하며, `.vscode/settings.json`에서 `clangd.path`를 활성 키트와 동일하게 설정해야한다.
