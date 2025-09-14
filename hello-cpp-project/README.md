# Hello C++ Project

This is a simple C++ project that demonstrates how to output "Hello, World!" to the console.

## Project Structure

```
hello-cpp-project
├── src
│   └── main.cpp
├── CMakeLists.txt
└── README.md
```

## Requirements

- CMake
- A C++ compiler that supports C++11 or later

## Building the Project

1. Open a terminal and navigate to the project directory.
2. Create a build directory:
   ```
   mkdir build
   cd build
   ```
3. Run CMake to configure the project:
   ```
   cmake ..
   ```
4. Build the project:
   ```
   make
   ```

## Running the Program

After building the project, you can run the program with the following command:
```
./hello-cpp-project
```

You should see the output:
```
Hello, World!
```