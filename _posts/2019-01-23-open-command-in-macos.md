---
layout: post
title: "Open command trong macOS"
categories: misc
tags:
  - lorem
  - ipsum
---


## Mở bài

Chắc hẳn không chỉ tôi mà nhiều người dùng MacOS khác Đã quen thuộc với câu lệnh `open` trên terminal. 
Hiểu một cách cơ bản nhất câu lệnh này giúp chúng ta mở thư mục hiện tại trong cửa sổ Finder. Tuy nhiên, câu lệnh này còn có thể làm Được nhiều Điều hơn chúng ta tưởng.

## Thân bài

### 1.Folders

Ngoài việc có thể mở Được thư mục bạn Đang làm việc, nó có thể mở Được các thư mục khác trong máy tính của bạn chỉ bằng việc bạn cung cấp Đường dẫn phía sau câu lệnh open thay vì dấu chấm như chúng ta Đã làm ở trên. Bạn cũng có thể mở các thư mục ẩn hay mở nhiều thư mục cùng một lúc.
Dưới Đây là một vài ví dụ cho những gì chúng ta Đã thảo luận ở trên:

`open ~/`

`open ~/etc ~/desktop ~/documents`

### 2.File

Open cũng có thể mở tập tin, lại tiếp tục suy nghĩ Đơn giản, chúng ta có thể thấy câu lệnh này giống như một cú click chuột double vào file hay folder thì Đều có chức năng mở nó lên. Ví dụ:

`open ~/desktop/meo.rb`

Nó sẽ mở file meo.rb. Bạn cũng có thể sử dụng Điều này với nhiều tệp.

`open ~/desktop/meo.rb ~/desktop/meo.jpg`

### 3.Applications

Giả sử tôi có file meo.rb, bây giờ file Đó sẽ Được mở mặc Định bởi phần mềm Xcode trong máy của tôi. Khi Đó, tôi có thể override lại phần mềm mặc Định Để mở file này bằng câu lệnh sau:

`open -a Sublime ~/desktop/meo.rb`

### 4.URLs

Open cũng có thể mở các Đường dẫn URL với cú pháp Đơn giản như sau:

`open https://google.com.vn`

Với câu lệnh này thì Đường dẫn bạn cung cấp sẽ Được mở bằng trình duyệt mặc Định. Bạn cũng có thể sử dụng trình duyệt khác làm trình duyệt mặc Định bằng tuỳ chọn –a như sau:

`open -a Firefox https://google.com.vn`

## Kết bài

Bài viết này có giá trị nào không? 

Câu trả lời là có, biết thêm về các lệnh Termial sẽ khiến cuộc Đời developer của bạn bớt khổ.
