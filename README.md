# hello-world

Hi，Everyone. I am a middle school teacher and I want to develope a program to help me collect, sort and analyze students' files. With this program, I can improve students' performance in class and exams. I will learn to code in Python step by step to do so. Thank you.
# Day3
再次阅读环境相关教程，我理解的是刚安装的VScode是在默认的global这个环境中运行了，长时间，容易堆积很多clusters，影响电脑工作效率，因此要选择一个虚拟或conda环境以便区室化。conda比virtual好在任何电脑上任何conda环境下一个project的不同部分可以选择同类conda环境运行。
我Day2的出错问题要么是终端运行自选环境导致的，要么是在integrated终端不会自动激活环境导致。
默认设置环境，要在Preference: Open User Settings里设。每次打开VScode要重选一次conda环境，可能因为没设为默认。
计算机只会干我们明确说明的事，所以格式很重要，字符、数字、变量要能够区分。
编程无非事拆解一个事情的步骤，分步编程，然后用一些逻辑运算将各部分联系。
一个复杂的计算器设计思路：（1）依据计算的优先级，先剥离括号，即找出最里面的括号，先进行计算；（2）在剥离的第一个括号内先区分乘除并运算，再加减，这样得到的值取代这个括号；（3）依次剥离依次运算。这个过程中需要计算器通过切片方式找最内括号（左括号有多少个之后遇到第一个右括号），用正则表达式把运算符和数字分开，每一镉括号的运算都是一次循环（需要考虑第二次循环可能出现的变化，如++ --因去除括号而在一起的情况）等。
多手打熟悉编程语言，往往出错在于格式不规范。
