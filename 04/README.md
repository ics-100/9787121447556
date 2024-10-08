# 第 4 章 汇编语言和汇编软件

|本期版本|上期版本|
|:---:|:---:|
`Tue Aug 20 17:48:37 CST 2024` | -

## 4.1 汇编语言程序

* 针对因特尔 x86 架构的处理器，就有 `AT&T` 和 `INTEL` 公司自己的风格
* 如果要指示一个数是十六进制，通常不采用在后面加 `H` 的做法，而是为它添加一个 `0x` 前缀
* 用汇编语言提供的符号书写的文本，叫做**汇编语言源程序**
* 将汇编语言源程序转换成机器指令，这个过程叫作**编译**
* 编译肯定还需要依靠一个软件，称为**编译器**，或编译软件

## 4.2 NASM编译器

* NASM的全称是 Netwide Assembler， 它是可免费使用的开源软件


### 4.2.2 代码的书写和编译过程

```bash
nasm -f bin exam.asm -o exam.bin
```

* 注释需要以英文字母的分号`;`开始

**4.2.3 用HexView观察编译后的机器代码**

* `hexdump`
* 如果该字节并非一个可以显示的字符，则显示一个替代的字符 `.`

## 4.3 配书文件包的下载和使用

* 本书第1版的文件包是 x86pkg1.rar
* 本版(也就是第2版)的文件包是x86pkg2.rar