﻿
git clone https://github.com/ngzHappy/qt_quick_book.git
git submodule init
git submodule update
git submodule foreach git pull

#简单文件拷贝器
git submodule add https://github.com/ngzqqb/sstd_copy_qml

#文件内容嵌入C++
git submodule add https://github.com/nanguazhude/sstd_qml_moc

#cplusplus 基础支持
git submodule add https://github.com/nanguazhude/sstd_library

#cgal 基础支持
git submodule add https://github.com/ngzqqb/sstd_cgal

#qt quick 基础支持
git submodule add https://github.com/ngzHappy/sstd_qt_qml_quick_library

#简单文件格式化
git submodule add https://github.com/ngzqqb/sstd_clean_code

#latex 基础支持
git submodule add https://github.com/ngzHappy/latex_book

#创建默认项目
git submodule add https://github.com/ngzqqb/sstd_create_default_project

#第一章
git submodule add https://github.com/ngzqqb/chapter01
git submodule add https://github.com/nanguazhude/sstd_introduce_qmake

#第二章
git submodule add https://github.com/ngzqqb/chapter02

#第三章
git submodule add https://github.com/ngzqqb/chapter03

#第四章
git submodule add https://github.com/ngzqqb/chapter04

#第五章
git submodule add https://github.com/ngzqqb/chapter05

#第六章
git submodule add https://github.com/ngzqqb/chapter06

#第七章
git submodule add https://github.com/ngzqqb/chapter07

#第八章
git submodule add https://github.com/ngzqqb/chapter08

#第九章
git submodule add https://github.com/ngzqqb/chapter09

#第十章
git submodule add https://github.com/ngzqqb/chapter10

#Windows平台下测试使用，创建Qt dll link到当前目录
git submodule add https://github.com/ngzqqb/sstd_create_windows_qt_dll_link

#Windows 平台下批量生成MSCV项目
git submodule add https://github.com/nanguazhude/creak_the_book_msvc_build_bat
