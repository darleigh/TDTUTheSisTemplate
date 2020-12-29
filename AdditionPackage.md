# Gọi thư viện Package
Chúng ta có 2 các để gọi thư viện vào `TEX`:
  1. Thêm vào gói `lib.sty` mình đã viết sẵn để trông `clearly` hơn! (khuyên dùng)
  2. Thêm thẳng từ file `main.tex`: với những mẫu báo cáo dùng một lần.
  
Yah, chúng ta bắt đầu nào!/

---
## 1. Thêm gói `package` vào bên trong file `lib.sty`
Cách này dùng để tối ưu & tái sử dụng, nhìn lại gọn con mắt nữa. Các bạn chỉ cần mở file `lib.sty` nằm ở bên trong folder `library` là được.
1. Mở thư mục `lib`
![](https://scontent.xx.fbcdn.net/v/t1.15752-9/126816144_403465127358325_4090312606682937689_n.png?_nc_cat=106&ccb=2&_nc_sid=58c789&_nc_ohc=NIk-Ba51lhEAX-MoTm0&_nc_ad=z-m&_nc_cid=0&_nc_ht=scontent.xx&oh=7ab47ad9451590b3136067941a03cd44&oe=5FDCD7CB)
2. Mở `lib.sty`
![](https://scontent.xx.fbcdn.net/v/t1.15752-9/126844480_825448784906119_3612541100103478620_n.png?_nc_cat=105&ccb=2&_nc_sid=58c789&_nc_ohc=slOp474ixp8AX9DVOD6&_nc_ad=z-m&_nc_cid=0&_nc_ht=scontent.xx&oh=26a1f4344244727a2a85bbc76e19bc21&oe=5FDC7676)
3. Nhập tên gói `package` ở phía dưới.
![](https://scontent.xx.fbcdn.net/v/t1.15752-9/126616135_2793982420847890_5302460179283652744_n.png?_nc_cat=103&ccb=2&_nc_sid=58c789&_nc_ohc=kVyWMBt8VtgAX8Ie6mQ&_nc_oc=AQmmfnIkzeP2LktD0gt2aw2Uknnl94CBet5De-XW4XIw2aLQ2cORK02bEwveN4wAcmcK82Jyccp-GxthJCpYyGpM&_nc_ad=z-m&_nc_cid=0&_nc_ht=scontent.xx&oh=b5313c71d1a467fe8686fa23f66b2f2a&oe=5FDE4E59)
---
## 2. Thêm thẳng từ file `main.tex`.
Cách này rất đơn giản, bạn chỉ cần bỏ gói `\usepackage{<tên gói>}` ở trên `\begin{document}` là được.\
Ví dụ:
```tex
\usepackage{Times} %Font-family:Times New Roman.
\begin{document}
  Lorem ipsum dolor sit amet, consectetur adipiscing elit,
  sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
  Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
  Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
  Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
\end{document}
```

