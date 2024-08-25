
DH Solutions – DH-09: HDSD gửi XML theo quyết định 4750
***
<div align='center'><h3>CÔNG TY TRÁCH NHIỆM HỮU HẠN 
  
  GIẢI PHÁP KỸ THUẬT SỐ DH</h3></div>

  <div align='center'>-----OO**0**OO-----</div>

####

</div>
<div align="center">
  <img src="https://github.com/dh-hos/To_Ho_Tro/blob/main/TEST/Logo.ico" alt="Simple Icons" width=70>
</div>

<h3 align='center'>PHẦN MỀM DHG.HOSPITAL</h3>

####

<h2 align='center'>HƯỚNG DẪN CẤU HÌNH PHẦN MỀM GỬI DỮ LIỆU XML 

THEO QUYẾT ĐỊNH 4750 CỔNG CHÍNH THÚC</h2>

####

<h3 align='center'>MỤC LỤC</h3>

####

<dl>
  
  <dt><h3><a href="#I">I.	Giới thiệu</a></h3></dt>
  
  <dt><h3><a href="#II">II.	Chuẩn bị dữ liệu phần mềm Admin</a></h3></dt>
  
  <dt><h3><a href="#III">III.	Chuẩn bị dữ liệu phần mềm Medicine</a></h3></dt>

  <dt><h3><a href="#IV">IV.	Gửi dữ liệu XML theo quyết định 4750 cổng chính thức BHXH</a></h3></dt>

   <dt><h3><a href="#V">V. Những lưu ý chức năng mới và ràng buộc nhập liệu</a></h3></dt>
  
</dl>

#

#

#

__I. Giới thiệu__

___I.1 Mục đích tài liệu___

- Hướng dẫn chuẩn bị dữ liệu trên phần mềm và gửi XML 4750 lên cổng chính thức bảo hiểm xã hội (https://gdbhyt.baohiemxahoi.gov.vn)

___I.2 Đối tượng sử dụng___

- Tất cả các đơn vị có khám chữa bệnh bảo hiểm y tế

___I.3	Ký hiệu, viết tắt___

- KCB: Khám chữa bệnh
- BHYT: Bảo hiểm y tế
- DM: Danh mục
- BHXH: Bảo hiểm xã hội
- KBCB: Khám bệnh chữa bệnh
- CLS: Cận lâm sàng
- BYT: Bộ y tế
- VTYT: Vật tư y tế

___I.4	Lưu trữ___

- NAS DH

__II. Chuẩn bị dữ liệu phần mềm Admin__

___II.1 Yêu cấu___

- Cập nhật tất cả các cấu trúc mới trên phần mềm Admin
- Sử dụng phần mềm Admin mới từ bảng HospitalAdmin.exe v.3.24.0617.4 trở về sau.

___II.2 Cập nhật tham số___

- Cập nhật số BHXH của thủ trưởng đơn vị (Mã số định danh y tế (mã số BHXH) của người đứng đầu cơ sở KBCB hoặc người được người đứng đầu cơ sở KBCB ủy quyền được ký và đóng dấu của cơ sở KBCB) cho tham số ma_ttdv.

![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/e79bb635-5415-432a-b400-69a58d1a2290)

___II.3 Danh mục nhân viên - người dùng___

- Cập nhật Số BHXH và số chứng chỉ hành nghề cho nhân viên.

![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/c691bbf3-63f6-45f5-a189-82edb91c26d6)

___II.4 Danh mục khoa___

- Cấu hình tài khoản trưởng khoa và mã khoa (ghi theo Phụ lục số 5 ban hành kèm theo Quyết định số 5937/QĐ-BYT ngày 30 tháng 12 năm 2021 của Bộ trưởng Bộ Y tế)

![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/75d81420-8134-4fa2-9986-454fecf7ae3e)

___II.5 Danh mục quốc gia___

- Khai báo số liệu -> Con người -> Quốc gia: Cập nhật mã 4750 cho các quốc gia đơn vị có sử dụng (quy định tại Phụ lục 2 Thông tư số 07/2016/TT-BCA ngày 01 tháng 2 năm 2016 của Bộ trưởng Bộ Công an)

![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/1c1a9fde-f163-48e6-82b3-1978127f99a6)

___II.6 Danh mục dân tộc___

- Khai báo số liệu -> Con người -> Dân tộc: Cập nhật mã QĐ4750 cho các dân tộc đơn vị có sử dụng (quy định tại danh mục các dân tộc Việt Nam ban hành kèm theo Quyết định số 121-TCTK/PPCĐ ngày 02/3/1979 của Tổng cục trưởng Tổng cục Thống kê). Tra cứu mã dân tộc tại đường [link] (http://tongdieutradanso.vn/danh-muc-cac-dan-toc-viet-nam.html)

![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/88cf95e4-8e00-4e22-b904-78fefbb83219)

___II.7 Danh mục nghề nghiệp___

- Khai báo số liệu -> Con người -> Nghề nghiệp: Cập nhật mã quyết định 4750 cho các nghề nghiệp đơn vị có sử dụng (quy định tại Quyết định số 34/2020/QĐ-TTg ngày 26 tháng 11 năm 2020 của Thủ tướng Chính phủ). Tra cứu mã nghề nghiệp tại đường [link] (https://luatvietnam.vn/lao-dong/quyet-dinh-34-2020-qd-ttg-danh-muc-nghe-nghiep-viet-nam-194623-d1.html). Nghề nghiệp không có mã xác định  thì ghi mã 00000. Lưu ý: Chỉ sử dụng mã cấp 5

![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/15e21d8f-6e16-4f24-9d9d-c6f3a5780e28)


___II.8 Danh mục địa phương___

- Khai báo số liệu -> Con người -> Địa phương: Cập nhật mã địa phương làm địa chỉ của bệnh nhân
  - Mã tỉnh: Chọn nút chỉnh (hình cây bút) trước tên tỉnh, nhập mã liên thông rồi lưu lại, ghi theo 02 ký tự cuối của mã đơn vị hành chính của tỉnh (quy định tại Phụ lục 1 Thông tư số 07/2016/TT-BCA ngày 01 tháng 2 năm 2016 của Bộ trưởng Bộ Công an)
 
  ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/e88ea037-c049-4f7c-a638-f48238daa434)
 
  - Mã huyện: Chọn nút chỉnh (hình cây bút) trước tên huyện, nhập mã liên thông rồi lưu lại, ghi mã đơn vị hành chính cấp huyện theo Quyết định số 124/2004/QĐ-TTg ngày 08/7/2004 của Thủ tướng Chính phủ hoặc sử dụng mã đơn vị hành chính mới được cấp có thẩm quyền cấp
 
  ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/39a3cc98-8be8-4795-a9e1-32024f994434)
 
  - Mã xã: Chọn xã muốn cập nhật mã -> chỉnh thông tin mã liên thông gửi dữ liệu rồi lưu lại (ghi mã đơn vị hành chính cấp xã theo Quyết định số 124/2004/QĐ-TTg ngày 08/7/2004 của Thủ tướng Chính phủ hoặc sử dụng mã đơn vị hành chính mới được cấp có thẩm quyền cấp
 
  ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/499caa6c-7e1c-45ad-b7fb-302c2e3e29b3)


___II.9 Danh mục nguyên nhân tai nạn___

- Khai báo số -> Tai nạn -> Nguyên nhân tai nạn: Cập nhật mã quyết định 4750 cho nguyên nhân tai nạn (phụ lục số 4 ban hành kèm theo Quyết định số 5937/QĐ-BYT ngày 30 tháng 12 năm 2021 của Bộ trưởng Bộ Y tế)

![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/1eb993b4-e72a-418f-a055-a9dda839789d)

![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/58b5a26e-e95a-408b-a28d-66d28f405515)


___II.10 Danh mục phương pháp vô cảm___

- Khai báo số liệu -> Điều trị -> Cập nhật mã quyết định 4750 cho phương pháp vô cảm (ghi mã phương pháp vô cảm được sử dụng trong phẫu thuật, thủ thuật, trong đó:- Mã "1": Gây mê; - Mã "2": Gây tê; - Mã "3": Châm tê;- Mã "4": các phương pháp vô cảm khác)

![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/cefa0c0f-8540-4e4c-8bc8-99d1336e5e45)


___II.11 Danh mục kết qua điều trị___

- Khai báo số liệu -> Điều trị -> Cập nhật mã BYT cho kết quả điều trị (Ghi mã kết quả điều trị, trong đó:- Mã "1": Khỏi; - Mã "2": Đỡ; - Mã "3": Không thay đổi; - Mã "4": Nặng hơn; - Mã "5": Tử vong; - Mã "6": Tiên lượng nặng xin về; - Mã "7": Chưa xác định; - Mã "8": Tử vong ngoại viện)

![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/9dcf1fc8-2940-427c-9d0b-e3d53996277d)


___II.12 Danh mục mã máy thực hiện CLS___

- Khai báo số liệu -> Y tế -> Danh sách mã máy thực hiện CLS -> Cập nhật danh mục máy trả kết quả CLS mã máy BYT (XML4) (Ghi mã các máy thực hiện dịch vụ cận lâm sàng, phẫu thuật, thủ thuật (máy xét nghiệm, máy XQuang, máy siêu âm…), tạm thời được ghi theo nguyên tắc: XX.n.YYYYY.Z, trong đó:
  - XX hoặc XXX: Mã nhóm máy thực hiện, trong đó: Huyết học ghi mã "HH"; vi sinh ghi mã "VS"; sinh hóa ghi mã "SH"; siêu âm ghi mã "SA"; Xquang ghi mã "XQ"; chụp cắt lớp vi tính ghi mã "CL"; chụp MRI ghi mã "MRI"; máy thực hiện phẫu thuật ghi mã "PT"; máy thực hiện thủ thuật ghi mã "TT"; máy xét nghiệm đa chức năng thì ghi mã "DC"; máy xạ trị ghi mã "XT"; máy chụp SPECT ghi mã "SP"; máy chụp PET/CT ghi mã "PET"; máy xạ hình xương ghi mã "XH"; máy nội soi ghi mã "NS"; máy chụp mạch xoá nền DSA ghi mã "DSA"; máy điện tim ghi mã "ĐT",....(Đối với các máy chưa quy định mã nhóm máy (XX hoặc XXX) thì ghi các chữ cái đầu tiên theo phiên âm tiếng Việt của máy, tối đa không quá 03 ký tự đầu tiên).
  - n: Ký hiệu của nguồn kinh phí mua máy, trong đó:
    - Mã "1": ngân sách nhà nước;
    - Mã "2": xã hội hóa;
    - Mã "3": các nguồn khác;
  - YYYYY: Mã cơ sở KBCB;
  - Z: Số serial của máy (Ghi cả phần chữ và phần số). Trường hợp không có số serial của máy thì sử dụng mã quản lý của máy do cơ sở KBCB lập. Đối với hệ thống máy gồm nhiều máy thì ghi tất cả các serial của các máy, cách nhau bằng dấu chấm phẩy ";"

![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/77d9eea3-3cc7-4a6c-a1f1-048f18e3e84c)


___II.13 Danh mục ICD 9___

- Bảng mã ICD -> ICD 9 -> Thêm danh mục ICD 9 (danh mục ICD-9 CM do Bộ trưởng Bộ Y tế ban hành kèm theo Quyết định số 4440/QĐ-BYT ngày 27 tháng 10 năm 2020)

![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/7aa78223-78f0-442e-9b45-ce6df33d7870)


___II.14 Danh mục cận lâm sàng (thông tư 37)___

- Danh mục cận lâm sàng (thông tư 37) -> Cập nhật mã ICD-9 cho CLS phẫu thuật, thủ thuật theo danh mục ICD 9

![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/9cd3a95b-79cf-4a54-b590-a98ca3826c57)


___II.15 Cấu hình mã chỉ số, tên chỉ số, đơn vị đo CLS___

- Cập nhật thủ công

  - Danh mục CLS (thông tư 37) -> Cấu hình tên chỉ số, mã chỉ số theo Xml 4 (4210) -> Cập nhật thủ công -> Cập nhật mã chỉ số, tên chỉ số và đơn vị đo (bổ sung đơn vị đo) (Ghi mã chỉ số, tên chỉ số và đơn vị đo CLS xét nghiệm, chẩn đoán hình ảnh, thăm dò chức năng, theo Phụ lục số 11 ban hành kèm theo Quyết định số 7603/QĐ-BYT ngày 25 tháng 12 năm 2018 của Bộ trưởng Bộ Y tế. Trường hợp chưa có thì để trống
 
  ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/92d59b4d-2aa1-4b79-af07-f7fa32abb26c)

- Cập nhật từ file excel (phần mềm chưa hỗ trợ cập nhật đơn vị đo từ file excel)

  - Danh mục CLS (thông tư 37) -> Cấu hình tên chỉ số, mã chỉ số theo Xml 4 (4210) -> Nhập từ file Excel -> Xuất tập tin mẫu sau đó điền thông tin vào vào file excel mẫu (gridXNExcel.xlsx), sau đó chọn nút chọn tập tin -> Kiểm tra cấu trúc (nếu đúng cấu trúc) -> Cập nhật vào hệ thống
 
  ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/9c6569b9-9e30-4ed6-88bc-dfc5566c7f06)
 
  ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/4236da32-2b26-46b9-973c-3796164da5c2)
 
  ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/1fcb8fb0-e817-46ad-af54-36df0ffeb6b2)


___II.16 Danh mục địa phương 4750___

- Hướng dẫn cập nhật danh mục địa phương 4750 mới sử dụng HospitalAdmin.exe v.3.24.0621.1 trở về sau

- Khai báo số liệu -> Con người -> Địa phương 4750

  - Bước 1: vào danh mục địa phương 4750 làm theo hướng dẫn để vào trang website tải danh mục địa phương mới [Link tải] (https://danhmuchanhchinh.gso.gov.vn/Default.aspx)
 
  ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/2718667d-ca02-4856-89d5-e0c2896bf665)
 
  ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/aee589a3-ba1c-4a47-8ab6-0f7369fdae09)
 
  - Bước 2: Chọn đơn vị hành chính Cấp tỉnh -> Check chọn Quận Huyện, Phường Xã -> Chọn nút Xuất Excel -> Lưu tập tin về máy.
 
  ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/09199acc-1a49-446a-9918-2b947dda3bd3)
 
  - Bước 3: Mở file excel Danh sách cấp tỉnh kèm theo quận huyện, phường xã vừa tải về -> Đổi tên sheet thành dmdiaphuong4750 sau đó đóng file này
 
  ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/f5ff2454-ab5a-42f8-9760-fc2169a01d44)
 
  - Bước 4: Cập nhật danh mục địa phương 4750 vào phần mềm:
    - Tại danh mục địa phương theo 4750 chọn nút Import Excel
    
    - Trên thư mục chọn file chỉnh Files of type thành Excel 2003 files (*.xls) sau đó tìm đường dẫn đến thư mục chứa tập tin cần import -> Chọn tập tin -> Chọn nút Open
   
    ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/596bd3ec-6a41-4442-952d-00d8df0f8d30)
   
  - Bước 5: Chọn Đồng ý cập nhật danh mục địa phương 4750 vào phần mềm
 
  ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/3af76694-a24d-4ca1-a2ff-9c35b2e1fdee)
 
  ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/5ba00664-195c-407d-90b3-f4a49822029e)




___II. Danh mục ___




__III. Chuẩn bị dữ liệu phần mềm Medicine__

___III.1 Yêu cầu___

- Cập nhật tất cả các cấu trúc mới trên phần mềm Admin
- Sử dụng phần mềm Medicine mới từ bảng HospitalMedicine.exe.v3.24.0625.0 trở về sau


___III.2 Danh mục thuốc___

- TT thầu 4750: Ghi thông tin thầu của thuốc theo thứ tự, gồm: Số quyết định phê duyệt kết quả lựa chọn nhà thầu; mã gói thầu; mã nhóm thầu (theo quy định tại Phụ lục số 6 ban hành kèm theo Quyết định số 5937/QĐ-BYT ngày 30 tháng 12 năm 2021 của Bộ trưởng Bộ Y tế); năm ban hành quyết định phê duyệt kết quả lựa chọn nhà thầu. Các thông tin này cách nhau bằng dấu chấm phẩy “;”. (Chi tiết xem hướng dẫn dữ liệu XML2 quyết định 130). Lưu ý:
  - Trường hợp có hai nhà thầu cùng trúng thầu một thuốc thì bổ sung mã gói thầu và số thứ tự nhà thầu trúng thầu của đơn vị đấu thầu, với định dạng Gi.YY, trong đó: "i" là số gói thầu, YY là số thứ tự của nhà thầu trúng thầu trong quyết định của cơ quan có thẩm quyền phê duyệt kết quả trúng thầu, cách nhau bằng dấu chấm phẩy “;”.
  - Trường hợp áp thầu thì bổ sung mã đơn vị ban hành quyết định. Trong đó: Trung tâm mua sắm tập trung (TTMSTT) quốc gia là mã "00"; trường hợp các tỉnh, thành phố đấu thầu tập trung thì lấy mã tỉnh, thành phố; trường hợp cơ sở KCB đấu thầu thì lấy mã cơ sở KCB), cách nhau bằng dấu chấm phẩy “;”.
  - Trường hợp thuốc tự bào chế, pha chế, chế biến thì ghi thông tin thầu như sau: Số quyết định;XXXX, trong đó số quyết định là số văn bản gửi cơ quan BHXH, XXXX là năm ban hành văn bản.
Ví dụ (4): Chế phẩm Cao thấp khớp do BV YHCT Trung ương tự bào chế năm 2023, BV YHCT TW có văn bản số 456/BVYHCTTW-BH gửi BHXH TP Hà Nội thì mã hoá thông tin thầu của chế phẩm như sau: 456/BVYHCTTW-BH;2023
  - Trường hợp do thiên tai, dịch bệnh phải chuyển thuốc đến cơ sở KBCB khác để điều trị cho người bệnh hoặc thuốc thanh toán ngoài giá dịch vụ cận lâm sàng chuyển thực hiện tại cơ sở KBCB khác thì ghi thông tin thầu của thuốc theo thông tin tại cơ sở KBCB chuyển thuốc hoặc nơi thực hiện dịch vụ cận lâm sàng. Cơ sở KBCB thống nhất với cơ quan BHXH nơi ký hợp đồng KBCB BHYT đối với danh mục thuốc này trước khi thực hiện trích chuyển dữ liệu điện tử.
  - Trường hợp thuốc đàm phán giá thì bổ sung mã của đơn vị thực hiện đàm phán giá là Trung tâm mua sắm tập trung thuốc quốc gia là mã "00".

- Mã phương pháp chế biến: Ghi mã phương pháp chế biến vị thuốc cổ truyền theo Bộ mã DMDC do Bộ trưởng Bộ Y tế ban hành (Phương pháp chế biến vị thuốc cổ truyền theo quy định tại Thông tư số 30/2017/TT-BYT của Bộ trưởng Bộ Y tế). Ghi chú: Trường hợp vị thuốc cổ truyền có nhiều phương pháp chế biến thì ghi đầy đủ các mã phương pháp chế biến, giữa các mã cách nhau bằng dấu chấm phẩy ";".

- Mã CSKCB: Chỉ ghi trong các trường hợp sau:
  -  Trường hợp do thiên tai, dịch bệnh phải chuyển thuốc đến cơ sở KBCB khác để điều trị cho người bệnh thì ghi C.XXXXX (XXXXX là mã cơ sở KBCB nơi chuyển thuốc đi)
  -  Trường hợp thuốc thanh toán ngoài giá dịch vụ cận lâm sàng chuyển thực hiện tại cơ sở KBCB khác thì ghi K.XXXXX (XXXXX là mã cơ sở KBCB nơi thực hiện dịch vụ cận lâm sàng)
  -  Trường hợp chế phẩm máu có sử dụng bộ dụng cụ gạn tách (kít tách tiểu cầu, bạch cầu...) hoặc xét nghiệm được thanh toán ngoài giá đơn vị máu, chế phẩm máu quy định tại tiết d khoản 10 Điều 3 Thông tư số 17/2020/TT-BYT ngày 12/11/2020 của Bộ Y tế thì ghi M.XXXXX (trong đó XXXXX là mã cơ sở KBCB của đơn vị cung cấp máu)
  -  Trường hợp cơ sở KCB sử dụng thuốc của hạng bệnh hạng cao hơn được kê đơn, chỉ định bằng hình thức hội chẩn từ xa theo quy định tại Thông tư số 20/2022/TT-BYT thì ghi HC.XXXXX (trong đó XXXXX là mã cơ sở KCB nơi thực hiện kê đơn, chỉ định thuốc)

![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/b36c6a3f-f4a8-410a-a352-0096d0816714)

- Dạng bào chế: Ghi dạng bào chế của thuốc (đối với thuốc hoá dược) hoặc dạng bào chế, chế biến của thuốc (đối với thuốc cổ truyền, thuốc dược liệu) theo thông tin được Cục Quản lý Dược hoặc Cục Quản lý Y, dược cổ truyền cấp giấy đăng ký lưu hành. Trường hợp thuốc do cơ sở KBCB tự bào chế, chế biến thì ghi dạng bào chế, chế biến của thuốc theo đúng hồ sơ được người đứng đầu cơ sở KBCB phê duyệt.

![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/da2f8c63-4452-4ac6-972c-96d41bc30f0c)


___III.2 Danh mục VTYT___

- TT Thầu 4750: Ghi thông tin thầu của VTYT theo thứ tự, gồm: Số quyết định phê duyệt kết quả lựa chọn nhà thầu; số gói thầu; mã nhóm thầu; năm ban hành quyết định phê duyệt kết quả lựa chọn nhà thầu. Các thông tin này cách nhau bằng dấu chấm phẩy “;”. Lưu ý:
  - Những VTYT đã được đấu thầu mua sắm hoặc đã được phê duyệt kế hoạch lựa chọn nhà thầu trước ngày 14/4/2023: Sử dụng mã nhóm thầu VTYT theo Phụ lục 7 ban hành kèm theo Quyết định số 5937/QĐ-BYT ngày 30/12/2021 của Bộ trưởng Bộ Y tế;
  - Những VTYT được đấu thầu mua sắm hoặc được phê duyệt kế hoạch lựa chọn nhà thầu kể từ ngày 14/4/2023: Tạm thời sử dụng mã nhóm thầu là "N0";
  - Trường hợp VTYT áp thầu thì Trường thông tin TT_THAU của VTYT ghi như sau: Số quyết định.Mã đơn vị ban hành quyết định;Gi;Ni;XXXX. Mã đơn vị ban hành quyết định trúng thầu của VTYT thực hiện như sau: TTMSTT quốc gia là mã "00"; trường hợp các tỉnh, thành phố đấu thầu tập trung thì sử dụng mã tỉnh, thành phố; trường hợp cơ sở KBCB đấu thầu thì sử dụng mã cơ sở KBCB; Gi là số gói thầu; Ni là số nhóm thầu; XXXX là năm ban hành quyết định).
  - Trường hợp VTYT tự sản xuất: Số quyết định trúng thầu thì ghi theo số văn bản gửi cơ quan BHXH, năm ban hành quyết định thì ghi năm ban hành văn bản
  - Trường hợp VTYT được phê duyệt kế hoạch lựa chọn nhà thầu trước ngày Thông tư số 14/2020/TT-BYT có hiệu lực thì trường TT_THAU ghi như sau: Số quyết định.Mã đơn vị ban hành quyết định;Gi;XXXX

![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/06dc5823-e61f-49cf-bfba-44176ca948a3)


__IV. Gửi dữ liệu XML theo quyết định 4750 cổng chính thức BHXH__

___IV.1 Cấu hình tài khoản và dữ liệu XML cần gửi cổng chính thức BHXH___

- Cập nhật tài khoản và XML 4750 cần gửi cổng đào tạo BHXH: Vào cấu hình gửi tự động -> API Gửi dữ liệu -> Cấu hình tài khoản, mật khẩu cổng đào tạo 4750 của đơn vị và chọn các bảng XML cần gửi cổng hoặc cần xuất ra file XML -> Kiểm tra thử kết nối nếu phần mềm báo kết nối thành công là hoàn thành.

![ảnh](https://github.com/user-attachments/assets/556d2e49-6185-49ba-90be-63f6bea67533)

![ảnh](https://github.com/user-attachments/assets/a9c52730-2891-4ab5-9bdb-3ec5e2a200a1)

___IV.2 Gửi dữ liệu lên cổng đào tạo và xuất file XML 4750___

- Cập nhật tài khoản, API cổng chính thức BHXH và dữ liệu XML 4750 cần gửi cổng chính thức BHXH: Vào cấu hình gửi tự động -> Tab API Gửi dữ liệu -> Cấu hình tài khoản, mật khẩu, link API cổng chính thức BHXH và chọn các bảng XML cần gửi cổng hoặc cần xuất ra file XML -> Lưu lại thông tin ->  Hoàn thành cấu hình gửi dữ liệu XML.

![ảnh](https://github.com/user-attachments/assets/5f213ccc-baa4-488a-be2b-30720723adf1)

![ảnh](https://github.com/user-attachments/assets/4f1bc854-7ebf-4f7b-9057-64a87fc5c3f2)

  - Gửi hoặc xuất từng hồ sơ.
 
![ảnh](https://github.com/user-attachments/assets/2cf0ee56-cc33-49bb-8fd7-8865e3b0a93f)

  - Gửi hoặc xuất nhiều hồ sơ.
 
![ảnh](https://github.com/user-attachments/assets/d239de9f-28bb-4500-8d0d-064c89b5d0e0)

- Xem dữ liệu XML 4750.

![ảnh](https://github.com/user-attachments/assets/fd04d5b9-6527-4382-8e94-15906be082b0)

![ảnh](https://github.com/user-attachments/assets/2dfd74fe-bc46-4650-b2a3-0bbd978775f3)



__V. Những lưu ý chức năng mới và ràng buộc nhập liệu__

___V.1 Nhận bệnh và hiệu chỉnh thông tin___

- Yêu cầu phần mềm Prescription.exe v.3.24.0620.8, Register.exe v.3.24.0620.0, Treatment.exe v.4.24.0620.0 trở về sau

- Phường, xã: Cần nhập đầy đủ 3 cấp tỉnh, huyện, xã để phần mềm lấy đủ thông tin mã tỉnh, mã huyện, mã xã gửi dữ liệu XML 4750 (bắt buộc)

![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/7ec6cfee-63ae-4779-86f7-1e7814ef91e8)

- Ô CMND: Có thể nhập 1 trong các loại giấy tờ sau: số CMND 10 số, số CCCD 12 số, số hộ chiếu 8 ký tự (1 ký tự chữ in hoa + 7 số)

![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/81e647c0-d841-4da7-8aa1-794ec91d00bf)

- Nhóm máu: bổ sung nhóm máu bệnh nhân vào phần chỉ số sinh hiệu ở nhận bệnh, hiệu chỉnh thông tin bệnh nhân (sử dụng Register, Prescription, Treatment, Admin từ ngày 21/06/2024 về sau)

![image](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/3e7e42f7-2d1f-408a-b888-ad99389cdc9b)

![image](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/a004af5e-772b-455b-a361-a5f3fcc6f4f5)


- Hướng dẫn nhận bệnh đối với bệnh nhân có giấy hẹn hoặc giấy chuyển tuyến

  - Bước 1: Chuẩn bị file ảnh GH-GCT. Chụp ảnh hoặc Scan GH-GCT và lưu vào thư mục trên máy tính. Lưu ý: File ảnh GH-GCT phải thuộc một trong các định dạng file sau: .bmp, .jpg, .jpeg, .png.
 

  ![002](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/3c714657-31f5-4ef0-9289-c63d78292429)


  - Bước 2: Tại phần mềm Register chọn chức năng Đăng ký KCB hoặc chức năng Nhận bệnh trên phần mềm Prescription.
 

  ![003](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/053af7d6-af31-4582-a75f-24e24d616e90)


  - Bước 3: Nhập thông tin đăng ký KCB của bệnh nhân, khi phần mềm xuất hiện thông báo “Bệnh nhân trái tuyến, có GIẤY CHUYỂN VIỆN không?” thì chọn “Có”.
 

  ![004](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/86177eba-51e3-4ba3-992f-98257d4b1977)


  - Bước 4: Chọn Tab “Chuyển tuyến” và nhập thông tin giấy chuyển tuyến của bệnh nhân (bắt buộc phải có mã Nơi giới thiệu).
 

  ![005](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/b72a5b02-f9ed-4fb8-a582-2fcb0151abaa)


  - Bước 5: Chọn trạng thái chuyển tuyến của bệnh nhân tại menu chọn T.thái.
 

  ![006](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/aa96406b-190d-4f60-bde3-56e39ad78d4b)
  ![007](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/c61e3a96-30bc-475a-b599-15ddf27c965e)


  - Bước 6 (thực hiện khi cần lưu file giấy chuyển tuyến hoặc giấy hẹn, nếu không thực hiện Bước 8): Bấm nút “Chọn giấy” ở Tab Chuyển tuyến (bắt buộc nhập mã Nơi giới thiệu trước).
 

  ![008](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/543b8a04-3ee3-43c4-87b9-b920492c98a7)
  - Bước 7: Khi phần mềm mở thư mục Open thì tìm đường dẫn đến file ảnh GH-GCT đã lưu ở Bước 1 và chọn file ảnh cần lưu. Bấm nút “Open”.
 

  ![009](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/72dcb1af-955c-4e84-8be6-ab48e1980ea5)
  ![010](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/3115e804-4a2c-42bc-9bd5-6c2a85c51e99)
  
  - Bước 8: Lưu lại thông tin đăng ký KCB của bệnh nhân, hoàn thành đăng ký thông tin KCB.
 

  ![011](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/3e51aa95-4ae0-4996-9259-ce5dfbb263cd) 


- Hướng dẫn nhận bệnh đối với bệnh nhân ngoại tỉnh có giấy xác nhận lưu trú tại địa phương

  - Bước 1: Chuẩn bị file ảnh GXNLT. Chụp ảnh hoặc Scan GXNLT và lưu vào thư mục trên máy tính. Lưu ý: File ảnh GXNLT phải thuộc một trong các định dạng file sau: .bmp, .jpg, .jpeg, .png.
 

  ![012](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/86315657-9c80-4a94-805b-c9d384bda2ea)

  - Bước 2: Tại phần mềm Register chọn chức năng Đăng ký KCB hoặc chức năng Nhận bệnh trên phần mềm Prescription.


  ![013](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/817b613e-3764-460f-94fb-013981ea628c)

  - Bước 3: Nhập thông tin đăng ký KCB của bệnh nhân.


  ![014](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/69ae0db9-3c5e-4b71-a507-fa66692e5aa1)

  - Bước 4: Chọn Tab “Thông tin thêm”. Check vào ô “Giấy xác nhận lưu trú” và bấm nút “Chọn giấy”.


  ![015](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/d6a647a9-2931-426d-b8b2-e56524dc4d54)

  - Bước 5: Khi phần mềm mở thư mục Open thì tìm đường dẫn đến file ảnh GXNLT đã lưu ở Bước 1 và chọn file ảnh cần lưu. Bấm nút “Open”.


  ![016](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/33dede73-6f63-4659-950e-e0a13502ae75)

  ![017](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/a90686ef-c795-472c-a76a-de07450da9fb)

  - Bước 6: Lưu lại thông tin đăng ký KCB của bệnh nhân, hoàn thành đăng ký thông tin KCB.


  ![018](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/db19409c-bd68-4e67-b1d2-1d17341c875d)


- Chức năng nhập bệnh đối với bệnh nhân nhận thuốc Lao theo hẹn không khám bệnh (sử dụng Register, Prescription từ ngày 21/08/2024 hoặc mới hơn.

  - Bước 1: Vào Đăng ký KCB -> đăng ký thông tin bệnh nhân.
  
  ![ảnh](https://github.com/user-attachments/assets/7529c228-d65d-4135-8061-0987f332a2ab)
  
  - Bước 2: Vào Tab Khám lao -> Check Bệnh nhân khám Lao và điền nơi cấp giấy xác nhận Lao, ngày cấp giấy xác nhận Lao.

  ![ảnh](https://github.com/user-attachments/assets/7aae8436-7005-4f39-80dd-324280ff4414)

  - Bước 3: Lưu thông tin đăng ký KCB của bệnh nhân và hoàn thành đăng ký thông tin KCB.
 
  ![ảnh](https://github.com/user-attachments/assets/2728045a-5d1e-45ab-b36f-f07c78ce05d5)

___V.2 Cấp toa___

-	Yêu cầu phần mềm Prescription.exe v. 3.24.0812.2, Treatment.exe v. 4.24.0812.0 trở về sau.

-	Bổ sung chức năng nhập liều dùng thuốc nhập số lượng thuốc sáng, trưa, chiều, tối khi cấp toa ngoại trú, BANT, nội trú. 
  - Prescription: Có thể nhập số lượng sáng, trưa, chiều, tối để phần mềm tự tạo liều dùng hoặc nhập trực tiếp liều dùng vào ô liều dùng, tạo danh sách liều dùng để chọn. Nếu số lượng thuốc không đủ để cấp theo số ngày uống của cả toa thì phải tự nhập liều dùng. Ví dụ: toa thuốc 30 ngày nhưng có thuốc sử dụng trong 30 ngày, có thuốc chỉ sử dụng trong 7 ngày thì thuốc sử dụng trong 30 ngày nhập liều dùng vào sáng, trưa, chiều, tối còn thuốc sử dụng trong 7 ngày phải nhập trực tiếp vào ô liều dùng hoặc liều dùng trên danh sách.

  ![ảnh](https://github.com/user-attachments/assets/3863ce3b-0344-454b-9a6b-4e3662d891db)
  ![ảnh](https://github.com/user-attachments/assets/87861627-8e36-4c20-8a1e-f2a7b784c9be)

  - Treatment: Có thể nhập số lượng sáng, trưa, chiều, tối để phần mềm tự tạo liều dùng.

  ![ảnh](https://github.com/user-attachments/assets/835236e8-794d-4caf-9021-fdef108dbd88)


___V.3 Cập nhật danh mục thuốc, VTYT bằng file excel___
-	Cập nhật Thông tin thầu 4750, phương pháp chế biến, dạng bào chế
-	Admin -> Tiện ích -> Thao tác danh mục thuốc

![ảnh](https://github.com/user-attachments/assets/d5d12001-2349-4d1a-82f6-1cfed4d9e8d7)

-	Chọn Tab Danh mục thuốc -> Chọn Lấy dữ liệu -> Chọn Danh mục thuộc kho BHYT

![ảnh](https://github.com/user-attachments/assets/1473c7c3-cd52-4619-824b-f56eafdeff1e)
 
-	Chọn Tab Danh mục thuốc nếu có thuốc -> Chọn Xuất Excel -> Lưu file excel

![ảnh](https://github.com/user-attachments/assets/d2ed61f9-f2cb-4f8a-94fa-2a25445c2a79)
 
-	Mở file excel vừa lưu cập nhật thông tin các cột tt_thau4750, dangbc, ma_pp_chebien theo hướng dẫn 4750 -> Lưu file vửa cập nhật và đóng file.

![ảnh](https://github.com/user-attachments/assets/f88f47cf-dd85-4064-855a-1ad4fdd7750b)
 
-	Tại chức năng Thao tác danh mục thuốc -> Chọn Tab Cập nhật danh mục thuốc -> Chọn nút Chọn tập tin và chọn file excel đã chỉnh sửa -> Chọn Lấy dữ liệu từ tập tin

![ảnh](https://github.com/user-attachments/assets/9f2db62a-e666-4073-8eed-5764da7b910a)
 
-	Khi phần mềm lấy được danh mục từ file excel -> Chọn Cập nhật dữ liệu theo mã hàng hoá (mahh) -> Có thông báo thì đồng ý cập nhật -> Hoàn thành cập nhật danh mục thuốc, VTYT

![ảnh](https://github.com/user-attachments/assets/03a2ae49-b637-4797-9f81-8819c48d77d6)

![ảnh](https://github.com/user-attachments/assets/7b0de144-3e21-409d-83b6-c5ea247a4a05)


 
___V.4 Cập nhật danh mục ICD9___
Bước 1: Anh chị đăng nhập vào module DHG.Hospital Admin → [Bảng mã ICD] →[Nhập ICD theo QĐ 3970/7603,ICD-9] (Như hình dưới)

![ảnh](https://github.com/user-attachments/assets/ef01207d-f375-4386-a5ca-f8f8a487e2e4)

Bước 2: Anh chị vào [Nút Hỗ trợ thao tác]→ [Danh mục ICD-9-Tải về] . Tải file ICD-9 lưu trên máy tính (Như hình dưới)

![ảnh](https://github.com/user-attachments/assets/234b167d-10f0-4157-ae03-8c5e859a7b1c)

Bước 3: Anh chị chọn vào nút […]→ Chọn file ICD-9 vừa tải về và Open→ Bấm vào hình mũi tên xổ xuống chọn dmicd9→ Chọn sheet (Như hình dưới)

![ảnh](https://github.com/user-attachments/assets/08882ea0-f87c-4f72-82e2-2b5979441c89)

Bước 4: Anh chị chọn vào nút [Hỗ trợ thao tác]→[Danh mục ICD-9-Import Excel đang chọn

![ảnh](https://github.com/user-attachments/assets/f50f9609-5bc3-4e72-995a-3cf267f0b123)

Bấm vào nút [Đồng ý] để xác nhận

![ảnh](https://github.com/user-attachments/assets/2301119d-5d2f-4655-bab7-f4d10e9558e5)

Sau khi thêm vào xong Anh chị vào [Bảng mã ICD]→ [ICD9] để xem lại Danh mục ICD-9 vừa thêm vào
(như hình dưới)

![ảnh](https://github.com/user-attachments/assets/44314008-344f-446f-b779-a4f43426fefe)



___V.5 Đồng bộ danh mục ICD-9 vào danh mục cận lâm sàng theo mã BYT (macls_byt)___

![ảnh](https://github.com/user-attachments/assets/d4310aeb-9f6a-4d1e-8327-971d482f9ac4)

Mã ICD-9 sau khi đồng bộ với danh mục cận lâm sàng như hình dưới

![ảnh](https://github.com/user-attachments/assets/10b45fce-aa32-4812-91a6-4e111e699449)



___V.6 Cấu hình mẫu số mặc định phiếu nghĩ ốm trên XML11___

- Cấu hình thông tin mặc định cột MAU_SO trên XML11: Giấy nghỉ hưởng BHXH (cấu hình theo ảnh hướng dẫn bên dưới). Lưu ý: cấu hình xong phải tắt Admin mở lại.

![ảnh](https://github.com/user-attachments/assets/36f027c1-e793-429c-9a99-6a637bfdf339)

![ảnh](https://github.com/user-attachments/assets/a7b02a62-f077-4c2b-a942-7aad1d7abb53)

![ảnh](https://github.com/user-attachments/assets/c22ab634-04ad-4c9e-ba35-6ddbb9183961)

- Trường hợp không cầu hình mẫu số mặc định (mẫu số mặc định rõng) thì MAU_SO XML11 lấy số Quyển nghỉ ốm, ngược lại nếu có cấu hình mẫu số mặc định thì lấy theo cấu hình.

![ảnh](https://github.com/user-attachments/assets/f6fc359d-d35f-4fcd-8f28-ad21e2afff28)

![ảnh](https://github.com/user-attachments/assets/8ebf2e2f-0efa-4697-be8d-d9613015f7e2)

![ảnh](https://github.com/user-attachments/assets/7a701f72-115d-4ad4-99c8-a6d3e0c2de2e)



___V.7 Cấu hình cách lấy đơn giá bệnh viện của CLS trên XML3___

- Cấu hình chức năng lấy DON_GIA_BV theo DON_GIA_BH của CLS trên XML3: Áp dụng đối với các CLS BH làm DV có thu chênh lệch giá (cấu hình theo ảnh hướng dẫn bên dưới).

![ảnh](https://github.com/user-attachments/assets/2a8da366-e223-4aa7-81a5-c2785386a28e)

![ảnh](https://github.com/user-attachments/assets/ef8749f5-f7aa-48d2-ab43-419b50f1df5c)

- Nếu chọn sử dụng thì DON_GIA_BV lấy theo DON_GIA_BH, ngược lại nếu không sử dụng chức năng này thì DON_GIA_BV bằng đơn giá DV của CLS.

![ảnh](https://github.com/user-attachments/assets/63dd7d87-c2a8-4898-9404-a308abd8f9bc)

![ảnh](https://github.com/user-attachments/assets/72482e8a-420c-4a21-a5fb-e0b103e42bc7)

![ảnh](https://github.com/user-attachments/assets/586f0f95-3f3c-4065-b27b-8c05c1a99551)



___V.8 Chức năng cập nhật diễn biến và tóm tắt kết quả CLS hỗ trợ dữ liệu QT_BENHLY, TOMTAT_KQ trên XML8 cho các bệnh nhân nội trú, BANT đã ra viện___

- Đối với bệnh nhân BANT đã ra viện: Prescription vào kết thúc điều trị (thực hiện theo ảnh hướng dẫn bên dưới) nhập diễn biến và tóm tắt kết quả CLS rồi Lưu lại.

![ảnh](https://github.com/user-attachments/assets/6d840c74-e4d3-4b61-838e-71120e9ffa91)

![ảnh](https://github.com/user-attachments/assets/a7e79608-7bc8-465b-b327-7dd073146f2c)

![ảnh](https://github.com/user-attachments/assets/16f07653-fbdd-40d0-9df0-6834c68fe748)

- Đối với bệnh nhân nội trú đã ra viện: Treatment vào danh sách ra viện (thực hiện theo ảnh hướng dẫn bên dưới) nhập diễn biến và tóm tắt kết quả CLS rồi Lưu lại.

![ảnh](https://github.com/user-attachments/assets/7f2fb959-7701-41a6-893a-74701fbd051c)

![ảnh](https://github.com/user-attachments/assets/f3a9d74a-943b-4162-a2e7-d86755154504)



___V.9 Cấu hình mã xăng dầu CLS chuyển viện hỗ trợ XML3___

- Cấu hình MA_XANG_DAU XML3 cho CLS chuyển viện theo phụ lục 5 Quyết định 824/QĐ-BYT năm 2023

![ảnh](https://github.com/user-attachments/assets/f19cd6b8-e678-459e-a975-ab5f6e93bfc5)

- Cách 1: Cấu hình mã xăng dầu có từng CLS chuyển viện: vào danh mục CLS thông tư 37, chọn tab Mã xăng dầu XML03, chọn từng CLS rồi cập nhật mã xăng dầu theo qui định.

![ảnh](https://github.com/user-attachments/assets/8651877b-6ec0-48f8-a709-3dfed61cdf82)

- Cách 2: Cấu hình tham số ma_xang_dau : Nếu CLS chuyển viện không cấu hình mã xăng dầu thì sẽ lấy mã xăng dầu từ tham số này.

![ảnh](https://github.com/user-attachments/assets/fd00e496-bf73-476f-b81e-d84e5912a42f)

![ảnh](https://github.com/user-attachments/assets/70fd5a08-8e51-4177-82e1-9f38ecd420ba)



___V.10 Hướng dẫn cách cấu hình người thực hiện CLS và trả kết quả Diagnose, Laboratory tách người thực hiện và người đọc kết quả___

- Mục đích là tách người thực hiện CLS và người đọc kết quả hỗ trợ XML3 thông tin NGUOI_THUC_HIEN, XML4 thông tin MA_BS_DOC_KQ.

- Cấu hình nhân viên có quyền thực hiện CLS (cấu hình theo ảnh hướng dẫn bên dưới). Nếu nhân viên có quyền thực hiện CLS thì check Được thực hiện CLS.

![ảnh](https://github.com/user-attachments/assets/2192291a-72a1-4e69-b493-9033dfa135a6)

- Hướng dẫn sử dụng Diagnose và Laboratory mới tách người thực hiện và người đọc kết quả CLS. (Laboratory tương tự như Diagnose)

  - Nếu đăng nhập phần mềm bằng tài khoản có quyền trả đọc kết quả và quyền thực hiện CLS thì có thể trả kết quả. Nhân viên thực hiện và nhân viên trả kết quả là cùng một người.

  - Nếu tài khoản không có quyền thực hiện CLS thì khi trả kết quả phần mềm bắt buộc chọn thêm tài khoản nhân viên có quyền thực hiện. Có thể vào tiện ích, chọn nhân viên thực hiện để thay đổi tài khoản.
 
  - Nếu có nhiều tài khoản thì chỉ có 1 tài khoản chỉ được có 1 quyền đọc kết quả. Nếu chọn thêm 1 tài khoản có cả 2 quyền thì có thể bỏ check 1 quyền của tài khoản đó. Có thể xóa tài khoản trực thêm lại để thay đổi quyền.
 
  - Khi trả kết quả CLS thì có thể chọn lại tài khoản thực hiện 
 
![ảnh](https://github.com/user-attachments/assets/acd73627-adf1-4195-8b88-23e7f19dc2bf)

![ảnh](https://github.com/user-attachments/assets/5788682f-ece2-4f58-8b7c-b7aafa3c0e4a)

![ảnh](https://github.com/user-attachments/assets/f3a853a5-288e-412d-add9-c6ff6dc7049a)

![ảnh](https://github.com/user-attachments/assets/d0a79c42-e3f7-4778-9523-0f62927ace0d)

 

___V.11 Hướng dẫn cấu hình tham số ràng buộc nhập sinh hiệu tùy chọn___

- Tham số ktsinhhieu.customize : Kiểm tra thông tin sinh hiệu bệnh nhận BHYT tùy chọn (Các chỉ số: chieucao|cannang|vongnguc|vongdau|huyetap|nhietdo|mach|nhiptho|hb|fio2|nhommau cách nhau [|], ví dụ: chieucao|cannang - là bắt buộc nhập chiều cao, cân nặng).
- Lưu ý khi sử dụng tham số này thì phải cấu hình tham số ktsinhhieu = 0.
- Tham số dùng để ràng buộc người dùng bắt buộc nhập thông tin sinh hiệu trước khi khám bệnh trên phần mềm Prescription, nếu thông tin sinh hiệu cấu hình trên tham số bị trống thì phần mềm cảnh báo không cho khám bệnh. Các thông tin sinh hiệu này hỗ trợ XML4750.

![ảnh](https://github.com/user-attachments/assets/3dd4676e-4e83-4e63-a54d-e37b6f2c47b5)
![ảnh](https://github.com/user-attachments/assets/7eb3ceab-b11d-478f-b018-0c5ddb2d2868)



___V.12 Hướng dẫn cấu hình tham số giới hạn số lượng ICD___

- Tham số ma_benh_kt.soluong : Số lượng mã bệnh ICD10 phụ tối đa cho 1 lần khám, chữa bệnh. Hỗ trợ giới hạn số lượng ICD10 để gửi dữ liệu XML4750 bảng 1 thông tin trường ma_benh_kt (hiện tại bảo hiểm chỉ cho phép tối đa 12 ICD phụ). Khi số lượng ICD10 phụ vượt quá số lượng cấu hình thì phần mềm sẽ cảnh báo.
- Phần mềm áp dụng tham số Prescription, Treatment.
- Ví dụ: Cấu hình tham số ma_benh_kt.soluong = 5. Giới hạn không quá 5 ICD10 phụ trong bệnh kèm theo.

![ảnh](https://github.com/user-attachments/assets/beca8bd3-3f46-40fa-a622-011a02b685c1)

![ảnh](https://github.com/user-attachments/assets/15db3563-05ef-4d12-8cd2-7236664fe1f8)

![ảnh](https://github.com/user-attachments/assets/5ddc32aa-2b3f-4dc1-a062-b7e791966388)



___V.13 Hướng dẫn cấu hình tham số cấu hình phân loại phẫu thuật trên danh mục CLS___

- Tham số phanloaipt.thuchien : Cho phép thực hiện Phẫu thuật/Thủ thuật (áp dụng đối với kho TT hoặc PT) mà không cần phân loại PT. Giá trị:
  - 0 (hoặc null): Chỉ thực hiện TT/PT đối với các cận lâm sàng có cấu hình [Phân loại PT].
  - 1: Cho phép thực hiện TT/PT bao gồm các TT/PT có hoặc không có cấu hình [Phân loại PT].

- Tham số phanloaipt.baocao : Thể hiện Phẫu thuật/Thủ thuật lên Sổ Thủ thuật/Phẫu thuật. Giá trị:
  - 0 (hoặc null): Chỉ thể hiện TT/PT đối với các cận lâm sàng có cấu hình [Phân loại PT].
  - 1: Thể hiện TT/PT lên sổ TT/PT, bao gồm các TT/PT có hoặc không có cấu hình [Phân loại PT].

- Phần mềm sử dụng Prescription, Treatment, Reports.

- Mặc định 2 tham số có giá trị bằng 0 hoặc rỗng. Chỉ khi CLS thủ thuật, phẫu thuật có cấu hình ___`Loại PT`___ trên danh mục CLS mới có thể lập được phiếu PT-TT và thống kê lên sổ phẫu thuật, sổ thủ thuật như khi chưa có tham số.

- Nếu cấu hình 2 tham số này bằng 1 thì các cần CLS thuộc loại thủ thuật, phẫu thuật không cần cấu hình ___`Loại PT`___ vẫn có thể lập phiếu PT-TT và được thống kê lên sổ phẫu thuật và sổ thủ thuật. Do 1 số CLS loại thủ thuật, phẫu thuật không có xếp loại phẫu thuật, thủ thuật.

![344440419-883a03fc-e823-416e-8ae2-89d0bdaacf78](https://github.com/user-attachments/assets/ce700f01-e5f0-4b1f-8de6-306953e6c902)

![ảnh](https://github.com/user-attachments/assets/56588875-659d-4f52-874f-0b1fa96dca73)

![ảnh](https://github.com/user-attachments/assets/803c3eff-e815-47fc-bb42-0a62e9f8b3ee)



___V.14 Hướng dẫn cấu hình ràng buộc thời gian thực hiện, thời gian trả kết quả CLS___

- Phần mềm ấp dụng Prescription, Treatment, Diagnose. (Cập nhật Script trên Admin và phần mềm có hỗ trợ chức năng này)

- Tham số ha.canhbaovuotthoigian : Cảnh báo khi đã vượt quá [Thời gian thực hiện y lệnh]/[Thời gian trả kết quả]/[Thời gian bắt đầu]/[Thời gian kết thúc] khi thực hiện Chẩn đoán hình ảnh/Thăm dò chức năng/Thủ thuật/Phẫu thuật. Giá trị: 0: Cảnh báo và KHÔNG cho phép lưu kết quả. 1: Cảnh báo và CHO PHÉP lưu kết quả.

- Tham số ha.sophuttraketqua : Số phút tối thiểu kể từ [thời điểm thực hiện y lệnh]/[thời điểm bắt đầu] đến [thời điểm trả kết quả]/[thời điểm kết thúc] áp dụng đối với thực hiện Chẩn đoán hình ảnh/Thăm dò chức năng/Thủ thuật/Phẫu thuật. Lưu ý: giá trị 0 hoặc rỗng là không giới hạn.

- Tham số ha.sophuttoithieu : Số phút tối thiểu kể từ [thời điểm chỉ dịnh cận lâm sàng] đến [thời điểm thực hiện y lệnh]/[thời điểm bắt đầu] áp dụng đối với thực hiện Chẩn đoán hình ảnh/Thăm dò chức năng/Thủ thuật/Phẫu thuật. Lưu ý: giá trị 0 hoặc rỗng là không giới hạn.

- Cấu hình số phút tối thiểu kể từ [thời điểm thực hiện y lệnh]/[thời điểm bắt đầu] đến [thời điểm trả kết quả]/[thời điểm kết thúc] áp dụng đối với thực hiện Chẩn đoán hình ảnh/Thăm dò chức năng/Thủ thuật/Phẫu thuật cho từng loại CLS. (Thực hiện theo ảnh hướng dẫn bên dưới)

![image](https://github.com/user-attachments/assets/73a3e2c8-4374-40c5-a3bc-ca50d2ac1d91)

![image](https://github.com/user-attachments/assets/99761e39-3424-4e5b-b371-19a0aa075961)

- Cấu hình số phút tối thiểu kể từ [thời điểm thực hiện y lệnh]/[thời điểm bắt đầu] đến [thời điểm trả kết quả]/[thời điểm kết thúc] áp dụng đối với thực hiện Chẩn đoán hình ảnh/Thăm dò chức năng/Thủ thuật/Phẫu thuật cho từng CLS cụ thể. (Thực hiện theo ảnh hướng dẫn bên dưới)

![image](https://github.com/user-attachments/assets/8687790f-44c1-4d60-ad28-375e6888089e)

- Lưu ý: Thứ tự ưu tiên áp dụng ràng buộc số phút thực hiện y lệnh và số phút trả kết quả: Sô phút cấu hình cho từng CLS trên danh mục CLS => Sô phút cấu hình cho từng loại CLS => Sô phút cấu hình trên 2 tham số ha.sophuttraketqua và ha.sophuttoithieu. Xét điều kiện nếu CLS không có cấu hình số phút thì kiểm tra số phút trên loại CLS, nếu loại CLS không có cấu hình số phút thì xét đến số phút cấu hình trên 2 tham số ha.sophuttraketqua và ha.sophuttoithieu. Khi lưu kết quả CLS nếu vi phạm điều kiện ràng buộc thì xét đến tham số ha.canhbaovuotthoigian xem có cho phép lưu kết quả hay không.

- Ví dụ: Treatment lập phiếu phẫu thuật - thủ thuật khi vi phạm cấu hình số phút thực hiện y lệnh và số phút trả kết quả:

  - Tham số ha.canhbaovuotthoigian = 0 : Cảnh báo và KHÔNG cho phép lưu kết quả.
 
![image](https://github.com/user-attachments/assets/a60d71d4-0a33-4ad5-86b2-6f8a486f83e4)

![image](https://github.com/user-attachments/assets/97abe677-d697-46da-9ec9-10847042c866)

  - Tham số ha.canhbaovuotthoigian = 1 : Cảnh báo và CHO PHÉP lưu kết quả.

![image](https://github.com/user-attachments/assets/e996b90c-70e2-4d56-8dd7-474db055cc9e)

![image](https://github.com/user-attachments/assets/955ccd41-125d-488a-a489-9acb055df461)


- Ví dụ: Diagnose trả kết quả CĐHA khi vi phạm cấu hình số phút thực hiện y lệnh và số phút trả kết quả:

  - Tham số ha.canhbaovuotthoigian = 0 : Cảnh báo và KHÔNG cho phép lưu kết quả.
 
![image](https://github.com/user-attachments/assets/edf9388b-e630-4164-abb6-b7f60d161c32)

![image](https://github.com/user-attachments/assets/26a376df-5870-4ef9-894d-419a57d9b884)

  - Tham số ha.canhbaovuotthoigian = 1 : Cảnh báo và CHO PHÉP lưu kết quả.

![image](https://github.com/user-attachments/assets/e0abef71-07f6-4f9c-8575-e5ade8cb06bc)

![image](https://github.com/user-attachments/assets/da4f6d51-553b-4b8e-adf5-00ac2764c0d4)

![image](https://github.com/user-attachments/assets/64b33098-7f88-488e-b0cc-1a16a4acc48a)



___Hết___












