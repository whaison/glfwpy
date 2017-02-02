glfwpy
======

最新のOpenGL（3.2+）をサポートするglfwのPythonのラッパー。この執筆時点でサポートされている最新のバージョン4.3です。

！[stanford bunny]（https://github.com/enthought/glfwpy/raw/master/screenshots/bunny.png "スタンフォードバニーはOpenGLを使ってレンダリングされました"）

サポートされているプラ​​ットフォーム：
--------------------
1. Windows
2. OSX
3. Linux
4. FreeBSD  - 今サポートされています！
5. Solaris  - 近日発売予定

要件：
-------------
1. Python：http://www.python.org
2. GLFW：http://www.glfw.org/
3. PyOpenGL from trunk：http://pyopengl.sourceforge.net/
4. Cython：http://www.cython.org

ドキュメンテーション：
--------------
1. glfwのドキュメントについては、http：//www.glfw.orgのglfwドキュメントを参照してください。
2. apiの使い方の例についてはexamplesフォルダを参照してください。

警告：
--------
1.イメージング関数（ユーザーはテクスチャをロードするためにPythonイメージングライブラリを使用することが期待されています）
2.スレッド関数（ユーザーはPythonスレッドライブラリを使用することが期待されます）
3. glfwGetProcAddress

コンベンション：
-----------
これはglfw apiのほぼ1：1ラップです。 glfw接頭辞は、Pythonバージョンの関数呼び出しと定数から削除されています。
Glfwpy ======ー

glfwpy
======

Pythonic wrappers for glfw that support modern opengl (3.2+). Version 4.3 which is the latest supported version as of this writing.

![stanford bunny](https://github.com/enthought/glfwpy/raw/master/screenshots/bunny.png "Stanford bunny rendered using opengl")

Supported Platforms:
--------------------
1. Windows
2. OSX
3. Linux
4. FreeBSD - Now supported!
5. Solaris - Coming soon

Requirements:
-------------
1. Python: http://www.python.org
2. GLFW: http://www.glfw.org/
3. PyOpenGL from trunk: http://pyopengl.sourceforge.net/
4. Cython: http://www.cython.org

Documentation:
--------------
1. Please refer to the glfw docs at http://www.glfw.org for glfw documentation
2. Please refer to examples folder for examples showing use of the api

Caveats:
--------
1. Imaging functions (Users are expected to use a python imaging library to load textures)
2. Threading functions (Users are expected to use the python threading library)
3. glfwGetProcAddress

Convention:
-----------
This is almost a 1:1 wrapping of the glfw api. The glfw prefix has been dropped from function calls and constants in the Python versions.
