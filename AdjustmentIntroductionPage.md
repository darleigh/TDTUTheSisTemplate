# Thay đổi nội dung của TRANG BÌA.
Mình sẽ hướng dẫn 2 cách:
  1. Thay đổi từ file `main.tex` (khuyên dùng).
  2. Thay đổi từ bên trong file `intro.tex`
  
---
## 1. Thay đổi từ file `main.tex`
Thay đổi tên tác giả, giảng viên hướng dẫn,...
1. Các bạn mở file `main.tex`.
![](https://scontent.xx.fbcdn.net/v/t1.15752-9/123218994_355920365666542_2084297664279230021_n.png?_nc_cat=102&ccb=2&_nc_sid=58c789&_nc_ohc=IZsDUsV-wMQAX9iEhGx&_nc_ad=z-m&_nc_cid=0&_nc_ht=scontent.xx&oh=a02235a601fa750820b748e50471f2cf&oe=5FC10F7D)
2. Tìm dòng `\newcommand{\tacgia}{Tác giả}` hoặc tương tự,\
thay đổi tên của người viết vào chỗ `•••` `\newcommand{\tacgia}{•••}`\
Ví dụ:
```tex
\newcommand{\gvhd}{Giảng viên hướng dẫn}
\newcommand{\tacgia}{Nguyễn Dương}
\newcommand{\mstacgia}{517020123}
```
![Thay đổi nội dung trên trang intro.tex](https://scontent.xx.fbcdn.net/v/t1.15752-9/123064046_1453626421506509_4380638689436494755_n.png?_nc_cat=106&ccb=2&_nc_sid=58c789&_nc_ohc=j1NkuaPLrzwAX-ihiPJ&_nc_ad=z-m&_nc_cid=0&_nc_ht=scontent.xx&oh=47a55e1fd3f3086b0083be9d0840f86e&oe=5FC36FD4)

---
## 2. Thay đổi từ bên trong file `intro.tex`
![](https://upload.wikimedia.org/wikipedia/commons/a/aa/Logo_Google_2013_Official.svg)
