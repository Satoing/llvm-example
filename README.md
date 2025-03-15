## llvm-example
a collection of examples showing how to use clang and llvm

## 基于Clang开发示例	功能
1. clang-astvisitor：遍历AST 输出文件的全部Struct/Union/Class声明Decl 和 子结构Decl
2. clang-declname：遍历AST 输出文件的全局变量声明VarDecl 包括头文件中的VarDecl
3. clang-diagnostic：自定义输Diagnostic诊断信息，包括文件名 行列号 代码总的错误数
4. clang-funccomment：遍历AST 为源代码中函数和if/else语句增加注释comment信息
5. clang-funcname：遍历AST 输出函数名
6. clang-funcrewrite：遍历AST 修改源代码中函数的执行逻辑
7. clang-interpreter：遍历AST 解释执行AST，实现了一个AST解释执行器
8. clang-preprocessor：输出文件中的token流，并处理了include头文件场景，用于展示与处理器preprocessor的使用
