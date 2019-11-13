## gitpod-mono-desktop
repository of develop mono based WinForm application on gitpod project

Using this repo. with gitpod, you can use noVNC session.
Try to compile HelloWorldForm.cs, 

  csc HelloWorldForm.cs -r:System.Windows.Forms.dll

The compiler will create “HelloWorldForm.exe”, which you can run using:

  mono HelloWorldForm.exe
  
and , you can see than within noVNC screen via 6080 Exposed port.

<Japanse>
 このリポジトリをgitpodで利用することで、noVNCセッションも利用できるワークスペースになります。
 リポジトリ内のHelloWorldForm.csをコンパイルし、
 mono HelloWorldForm.exeで実行した後に、6080のExposeをブラウザで参照することで
 noVNC上でWinFormの画面が表示されるのが確認できます。
</Japannese>
