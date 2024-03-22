# JsonParser
Using C++17 standard

使用C++17标准的json解析器
使用variant 管理json数据类型 ，string_view进行代理模式明确只读语义，optional处理非侵入式异常处理机制。
通过递归下降对json字符串进行parser，解析后支持动态修改，并重新输出json格式，接口设计便捷，使用方便。
