## HÀM ##

----------
**I.HÀM, TỔ CHỨC CHƯƠNG TRÌNH THÀNH CÁC HÀM**\

**1.Tại sao phải sử dụng hàm**

Ví dụ: ta coi hàm **main** là tổng giám đốc, các hàm con là các nhân viên và mổi nhân viên thực hiện một nhiệm vụ khác nhau , các hàm con có thể lấy kết quả của nhau để thực hiện công việc sau đó báo cáo lại cho giám đốc. **hàm main ** khi cần kết quả của công việc nào thì có thể lấy kết quả của hàm con thực hiện công việc đó,

*Các lợi ích của việc sử dụng hàm *

Tiết kiệm code 

Tăng tốc độ thực thi của chương trình

Tăng hiệu quả của câu lệnh

Có khả năng sự dựng lại mã nguồn

**2.Các nguyên tắt xây dựng hàm**

Hàm sẽ có vai trò ngang nhau. Vậy ta không thể xây dụng hàm bên trong các hàm 

Chú ý :

- Tên hàm 

- Kiểu giá trị trả về của hàm 

- Đối hay tham số hình thức ( Hàm main gửi dữ liệu cho hàm con )

- Thân hàm ( Nội dung của hàm )

- Khai báo hàm tức khai báo prototype ( báo trước chho trình dịch cho ta sẽ dử dụng hàm gì)

- Lời gọi hàm 

- Tham số truyền vào 

**3. Cấu trúc tổng quan của chương trình**

*các khai báo # include*

*các khai báo define*

*Khai báo các đối tượng dữ liệu bên ngoài  //khai báo biến toàn cục (mảng , biến, cấu trúc..)*

*Khai báo nguyên mẫu của hàm*

*Hàm main*

**Xây dựng hàm được viết theo mẫu**

<Kiểu dữ liệu > tên_hàm ( Danh sách các đối số )

{

        Khai báo biến cục bộ 
return ;

}


kiểu dữ liệu có thể là kiểu void tức không có giá trị trả về

**gọi hàm**

tên _ hàm ( danh sách các đối số truyền bào );

**Nguyên tắt hoạt động**

Hàm main được gọi chạy đầu tiền . cho đên khi nào gặp lời gọi hàm con thì hàm main dừng lại thực hiện hàm con , đến khi thực hiện xong hàm con và có trả về giá trị cho hàm main hay không. sau đó hàm main sẽ tiết tục chạy cho tới khi đến cuối chương trình 


** II. HÀM CÓ ĐỐI LÀ CON TRỎ, HÀM CÓ CÓ GIÁ TRỊ TRẢ VỀ LÀ CON TRỎ**

**1.HÀM CÓ ĐỐI LÀ CON TRỎ**

*void chunhat (float a, float b, float *v, float *d)

Ví dụ: float a =5, b=10 v, d;


chunhat (float a, float b, &v, &d)

**2.Hàm có giá trị trả về là con trỏ**

< kiể dữ liệu > *teenham (< danh sách các đối số>)

