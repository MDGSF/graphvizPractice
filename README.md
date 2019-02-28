# graphvizPractice

dot -Tpng test1.dot -o test1.png

用 unflatten 处理过，布局更好看

unflatten test1.dot | vim -

unflatten test1.dot | dot -Tpng -o test1.png
