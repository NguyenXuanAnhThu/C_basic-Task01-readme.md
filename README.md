## TÌM HIỂU VỀ MARKDOWN
[1. Markdown là gì?](Markdownlagi)

[2. Markdown được sử dụng để làm gì?](sudungMarkdown)

[3. Các cú pháp thường gặp](cuphap)

[4. Cài đặt Sublime Text và tìm kiếm, cài đặt các công cụ hỗ trợ Markdown (export HTML, markdown preview,...)](caidat)

<a name="Markdownlagi"><a/n>
# Markdown là gì?
  Markdown là ngôn ngữ đánh giá văn bản được tạo ra bởi John Gruber.
<a name="sudungMarkdown"><a/n>
# Markdown được sử dụng để làm gì?
  Markdown sử dụng cú pháp đơn giản và khá dễ hiểu để đánh dấu văn vản và văn bản được viết bằng ngôn ngữ Markdown có thể được chuyển đổi sang ngôn ngữ HTML. Ngược lại các văn bản viết bằng ngôn ngữ HTML cũng có thể chuyển đổi sang ngôn ngữ Markdown.
<a name="cuphap"><a/n>
# Các cú pháp thường gặp
 1. Tạo tiêu đề:
 
  # Tiêu đề 1<h1>
  ## Tiêu đề 2<h2>
  ### Tiêu đề 3<h3>
  #### Tiêu đề 4<h4>
  ##### Tiêu đề 5<h5>
  ###### Tiêu đề 6<h6>
 2. Chèn link, chèn hình ảnh:
 
  -Chèn link:
  
   *Cách 1: ` http://github.com `
   
   *Cách 2: ` [Github](http:/github.com) `
   
  -Chèn hình ảnh:
  
   ` <img src="link_anh_cua_ban"> `
   
 3. Ký tự in đậm, in nghiêng, gạch ngang:
  - **In đậm**:
  ` **từ cần in đậm** `
  - *In nghiêng*:
  ` *từ cần in nghiêng* `
  - ~~Gạch ngang~~:
  ` ~~từ cần gạch ngang~~ `
  
 4. Gạch đầu dòng:
 
 ~~~
 
  - Gạch đầu dòng thứ nhất
  <ul>
  <li>Thụt với đầu dòng 1</li>
  <li>Thụt với đầu dòng 1</li>
  </ul>
  - Gạch đầu dòng thứ hai
  <ul>
  <li>Thụt với đầu dòng 2</li>
  <li>Thụt với đầu dòng 2</li>
  </ul>
  
 ~~~
 6. Bảng:
  ~~~
  
   | Cột 1 Hàng 1 | Cột 2 | Cột 3 | Cột 4 |
   |--------------|-------|-------|-------|
   | Hàng 2 | 2x1 | 2x2 | 2x3 | 2x4 |      
   | Hàng 3 | 3x1 | 3x2 | 3x3 | 3x4 |      
   | Hàng 4 | 4x1 | 4x2 | 4x3 | 4x4 |      
   
  ~~~
