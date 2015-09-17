12（或更小）~14英寸屏幕
    1）英文字体：
    名字：Arial monospaced for SAP
    大小：9px
   
    在vimrc中的配置如下：

    set guifont=Arial_monospaced_for_SAP:h9:cANSI

    
    优点：
        a）0 O o  1 l ; : 也是区别非常明显
        b）字体小且圆滑，支持cleartype,最重要的是它的比划只有一个像素，所以在小屏幕上看起来非常精致。而在12~14英寸屏幕上不使用Bitstream Vera Sans Mono的主要原因就在于，Bitstream Vera Sans Mono的比划太粗，在那么小的屏幕上显得很是臃肿。
    缺点：
        a）有个很大的问题就是，Arial monospaced for SAP这个字体中的*很靠上，而且()等符号和字母并没有持平，所以看起来很是别扭，所以笔者自己更改了一下，下面会放出下载（原版和修改版都有）
