动态语言，即php的语言结构在运行期是可以改变的，比如我们在运行期require一个函数定义文件。从而导致语言的函数表动态的改变。
所谓脚本语言，即 php并不是独立运行的。要运行php我们需要php解析器。

PHP的执行是通过Zend engine(ZE, Zend引擎), ZE是用C编写的，大家都知道C是一个强类型语言，也就是说，在C中所有的变量在它被声明到最终销毁，都只能保存一种类型的数据。

