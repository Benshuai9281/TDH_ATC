# MarkDown

## My memo

换行需要空一行

这样才能换行。

```c
int val;
val = 100;
printf( "%d\n", val );
```

1. **加粗**
   1. <b>jiacu</b>
      1. ??
         1. ???
2. *倾斜*
3. ***我全都要***

4.

- 第一点
  - 第二点
    - 第三点

- [X] todo
- [ ] todo
- [ ] todo

| 左寄せ(デフォルト) |            中央揃え            |                     右寄せ |
| ------------------ | :----------------------------: | -------------------------: |
| その１             | コロンでラインを挟むと中央揃え | 右側にコロンを書くと右寄せ |
| その２             |             実践編             |                     実践編 |
| その３             |             発展編             |                     発展編 |

> 引用しました
>> 引用の引用です
>>> さらに引用

と、このように引用を表すことができます

セクション１
***
セクション２
***
セクション３

[Googleへのリンク](https://google.co.jp)

---
title: Title of report
author: Tanuki Kitsune
date: 2017.1.1
...

# First section

This is an example report content.

## How to include images

Including png image:

![Example of png image\label{fig:png_sample}](images/example.png){ width=10cm }

Including pdf image:

![Example of pdf image\label{fig:pdf_sample}](images/example.pdf){ width=10cm }

You can use tex reference like Figure \ref{fig:png_sample} and \ref{fig:pdf_sample}

## Citation

You can cite an article like [@Krizhevsky2012]

## First sub-section

You can put a list of items using itemize:

- Monday
- Tuesday
- Wednesday
- Thursday
- Friday
- Saturday
- Sunday

Or, numbering:

1. Totato
2. Carrot
3. Onion

## Other expressions

- Italic*
- *Italic2*
- **bold**
- **bold2**

## Quotation

> Quotation

## URL

URL: [www.waseda.jp](https://www.waseda.jp)

## Table

Table:

|  A  |  B  |  C  |
| --- | --- | --- |
|  22  |  99  |  128  |

## Math expressions

Formula:

$$
\frac{\partial^2 p}{\partial t^2} = c^2 \nabla^2 p
$$

\begin{eqnarray}
  2x_1 + x_2 & = & 5 \\
    2x_2 & = & 2
\end{eqnarray}

## Source code

\```test.py
t = np.arange(0, np.pi*4)
plt.plot(t, np.sin(t))
\```
You can put source code
