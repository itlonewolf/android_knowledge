# If your project uses WebView with JS, uncomment the following
# and specify the fully qualified class name to the JavaScript interface
# class:
#
#-keepclassmembers class fqcn.of.javascript.interface.for.webview {
# public *;
#}

如果你的工程使用了WebView中的JS，解除下面的注释，并且指定JavaScript接口类的全名。
（也就是是忽略js部分，不进行混淆，方法是解除注释，将fqcn.of.javascript.interface.for.webview替换为与JS绑定的类名。）
#
#-keepclassmembers class fqcn.of.javascript.interface.for.webview {
# public *;
#}

#如，

-keepclassmembers class cn.lvye.hd.activity.Fragment.BBSFragment$*
-keepclassmembers class cn.lvye.hd.activity.Fragment.BBSFragment$*{*;}
#此例子中还含有了对内部类的keep
