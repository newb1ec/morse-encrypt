# 隐藏字符加密

原理是利用零宽字符对加密文本进行转码，嵌入到普通文本当中，从而隐藏加密内容；表面看起来是一段普通文本，复制粘贴不会丢失

## 秘密传达消息

零宽字符在大部分应用都支持，pc版QQ会显示零宽字符，但移动端不显示

你可以将密文加密到普通文本中，然后邮件发送，表面上看起来是普通文本，只有对方复制明文进行解密后才能看出隐藏信息

## 为文章添加隐藏水印

你可以在你写的文章插入隐藏字符，将作者信息嵌入其中，当别人复制你的文章时，并不会发现这片文章已经被你悄悄打下水印
比如下面这段话，复制粘贴到 `https://morse.rovelast.com` 进行解密

```txt
春风再美也比上你的笑，‌‍‌​‍‍‍​‌‌‌‍​‌​‌‍‌‌​‌‍​‌‌‌​‍没见过你的人不会明了
```