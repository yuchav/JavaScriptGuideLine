# JavaScript Code GuideLine
==============================

 1. 全局不允许使用'strict'模式
 2. 使用jQuery框架及其插件
 3. 使用Bootstrap框架
 4. 使用Required.js管理依赖
 5. 使用分号作为结尾
 6. 模块化编程,使用闭包和自执行函数
 7. 所有的循环体和判断体都用{}包起来
 8. for-in循环体中必须用hasOwnProperty方法检查成员是否为自身成员。避免来自原型链上的污染
 9. 变量声明应放在function的最上面。避免使用未声明的变量
 10. 不要使用with, void, eval
 11. 构造器的首字母大写。如function Dialog (config) {statement;}
 12. 对象的属性或方法名采用小驼峰式
 13. 私有变量名用下划线开头。如："_current", "_defaultConfig"
 14. 常量名全部大写，单词间用下划线分隔
 15. 语句中的必要空格和缩进
