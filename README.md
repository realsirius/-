1，这是年轻人的第一个大语言模型，理论上只要能运行Windows10就能跑得动
有基于python和c++两种语言的不同版本，一个使用gpt-2（效果较好，但是依然很差劲），另一个基于2-gram模型。

2，如何使用（how to use),
c++版本
创建一个包含训练文本的文件（如training_text.txt）。
编译并运行上述C++程序
g++ -o text_generator text_generator.cpp
./text_generator
函数解释
tokenize函数：将输入字符串按空格分割成单词。
readFile函数：从文件中读取训练文本内容。
generateModel函数：构建2-gram模型，存储每个词及其后续词的列表。
generateText函数：根据2-gram模型从指定的起始词开始，生成指定长度的文本。
main函数：读取训练文本，分词，构建模型，并生成文本。

Q&A 
这个可以干什么？
answer；这个可以让你在垃圾电脑上体验大模型
这个是英语作文吗
answer；是的呢，这是满分作文，特级教师都看不懂那种
