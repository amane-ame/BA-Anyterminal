# BA-Anyterminal

在任意 Terminal(Windows) 中以 GDI 点内存像素来播放 Bad Apple 。

使用了 `320 x 240, 60 fps` 的源。

1. 由于比较无聊，所以附送了音频；

2. 由于不想压缩，因此直接把原始 `binfile` 用 `7z` 压缩了，凑合着用吧。

![效果](https://i.loli.net/2018/11/22/5bf684e9f0e05.png)

`g++ BA.cpp -o BA -std=c++98 -lgdi32 -lwinmm`
