# webpack-practice
## 1.模块化
### 优点：
   + 作用域封装
   + 重用性
   + 解除耦合
### 2. 模块化的演化
#### 1. AMD（异步模块定义）
         通过define函数引入
#### 2. commonjs（require）
        模块的依赖通过require函数引入
        
        *amd和commonjs都需要模块显式引入*
#### 3. es6 module
       import 导入
       export 导出
## 2. webpack的打包机制
### 1.webpack与立即执行函数的关系
      
### 2. webpack打包核心逻辑
     + 从入口文件开始
     + 将每一个依赖模块包装起来，放到数组进行调用
     + 实现模块加载的方法，并把它放到模块加载的函数中，确保模块之间可以互相调用
     + 把执行入口文件逻辑放在一个函数表达式中，并立即执行这个函数
## 3. webpack核心
 ### 1. 




 
