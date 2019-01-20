如何使用ReadTheDocs和RST文件格式
================================

About ReadTheDocs
-----------------

ReadTheDocs是一个生成文档web页面的工具。在ReadTheDocs官方网站上，可以注册账号（或者链接自己的GitHub）账号，以 xxx.readthedocs.io/ 的URL发布自己的内容。
或者可以自行搭建私有云服务器。

About RST
---------

RST全称reStructruedText，也就是用于编辑文档的这种文件格式。在编辑内容上和普通的txt或者复杂一点的Markdown没有什么区别，重要的是它支持一些方便生成文档的指令，例如插入代码，插入目录，Note，Tip等等。

.. tip::

    这是一个Tip。

.. note::

    这是一个note

* 使用C语言的code-block

.. code-block:: c

    #include <stdio.h>
    int main(){
        printf("Hello World\n");
        return 0;
    }

* 使用Python的code-block

.. code-block:: python

    import numpy as np
    arr = np.array(shape = (2,2))
    print(arr)

大标题示例
==========

中标题示例
----------

小标题示例 
**********