# 设置编译器
CXX = g++

# 设置编译标志
CXXFLAGS = -std=c++14 -Wall -O3 -mpopcnt -march=native -g -Wextra

# 设置头文件路径
INCLUDES = -I./core

# 设置源文件
SRCS = main.cpp

# 设置输出文件名
OUTPUT = main

# 编译规则
all:
	$(CXX) $(CXXFLAGS) $(INCLUDES) $(SRCS) -o $(OUTPUT)

# 清理规则
clean:
	rm -f $(OUTPUT)