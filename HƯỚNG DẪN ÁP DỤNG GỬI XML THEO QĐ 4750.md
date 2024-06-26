
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

THEO QUYẾT ĐỊNH 4750 CỔNG ĐÀO TẠO</h2>

####

<h3 align='center'>MỤC LỤC</h3>

####

<dl>
  
  <dt><h3><a href="#I">I.	Giới thiệu</a></h3></dt>
  
  <dt><h3><a href="#II">II.	Chuẩn bị dữ liệu phần mềm Admin</a></h3></dt>
  
  <dt><h3><a href="#III">III.	Chuẩn bị dữ liệu phần mềm Medicine</a></h3></dt>

  <dt><h3><a href="#IV">IV.	Gửi dữ liệu XML theo quyết định 4750 cổng đào tạo BHXH</a></h3></dt>

   <dt><h3><a href="#V">V. Những lưu ý chức năng mới và ràng buộc nhập liệu</a></h3></dt>
  
</dl>

#

#

#

__I. Giới thiệu__

___I.1 Mục đích tài liệu___

- Hướng dẫn chuẩn bị dữ liệu trên phần mềm và gửi XML 4750 lên cổng đào tạo bảo hiểm xã hội (https://daotaogdbhyt.baohiemxahoi.gov.vn) - Bước chuẩn bị cho gửi dữ liệu XML 4750 chính thức

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

___I.5 Link tải phần mềm mới___

- [Admin] (https://gofile.me/78TQg/47IND1Fyf)
- [Medicine] (https://gofile.me/78TQg/WLJ5FWtI2)
- [Register] (https://gofile.me/78TQg/I1wZ2Fzet)
- [Prescription] (https://gofile.me/78TQg/2RUIcgJyc)

__II. Chuẩn bị dữ liệu phần mềm Admin__

___II.1 Yêu cấu___

- Cập nhật tất cả các cấu trúc mới trên phần mềm Admin
- Sử dụng phần mềm Admin mới từ bảng HospitalAdmin.exe v.3.24.0617.4 trở về sau.

___II.2 Cập nhật tham số___

- Cập nhật số BHXH của thủ trưởng đơn vị (Mã số định danh y tế (mã số BHXH) của người đứng đầu cơ sở KBCB hoặc người được người đứng đầu cơ sở KBCB ủy quyền được ký và đóng dấu của cơ sở KBCB) cho tham số ma_ttdv.

- ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/e79bb635-5415-432a-b400-69a58d1a2290)

___II.3 Danh mục nhân viên - người dùng___

- Cập nhật Số BHXH và số chứng chỉ hành nghề cho nhân viên.

- ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/c691bbf3-63f6-45f5-a189-82edb91c26d6)

___II.4 Danh mục khoa___

- Cấu hình tài khoản trưởng khoa và mã khoa (ghi theo Phụ lục số 5 ban hành kèm theo Quyết định số 5937/QĐ-BYT ngày 30 tháng 12 năm 2021 của Bộ trưởng Bộ Y tế)

- ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/75d81420-8134-4fa2-9986-454fecf7ae3e)

___II.5 Danh mục quốc gia___

- Khai báo số liệu -> Con người -> Quốc gia: Cập nhật mã 4750 cho các quốc gia đơn vị có sử dụng (quy định tại Phụ lục 2 Thông tư số 07/2016/TT-BCA ngày 01 tháng 2 năm 2016 của Bộ trưởng Bộ Công an)

- ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/1c1a9fde-f163-48e6-82b3-1978127f99a6)

___II.6 Danh mục dân tộc___

- Khai báo số liệu -> Con người -> Dân tộc: Cập nhật mã QĐ4750 cho các dân tộc đơn vị có sử dụng (quy định tại danh mục các dân tộc Việt Nam ban hành kèm theo Quyết định số 121-TCTK/PPCĐ ngày 02/3/1979 của Tổng cục trưởng Tổng cục Thống kê). Tra cứu mã dân tộc tại đường [link] (http://tongdieutradanso.vn/danh-muc-cac-dan-toc-viet-nam.html)

- ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/88cf95e4-8e00-4e22-b904-78fefbb83219)

___II.7 Danh mục nghề nghiệp___

- Khai báo số liệu -> Con người -> Nghề nghiệp: Cập nhật mã quyết định 4750 cho các nghề nghiệp đơn vị có sử dụng (quy định tại Quyết định số 34/2020/QĐ-TTg ngày 26 tháng 11 năm 2020 của Thủ tướng Chính phủ). Tra cứu mã nghề nghiệp tại đường [link] (https://luatvietnam.vn/lao-dong/quyet-dinh-34-2020-qd-ttg-danh-muc-nghe-nghiep-viet-nam-194623-d1.html). Nghề nghiệp không có mã xác định  thì ghi mã 00000. Lưu ý: Chỉ sử dụng mã cấp 5

- ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/15e21d8f-6e16-4f24-9d9d-c6f3a5780e28)


___II.8 Danh mục địa phương___

- Khai báo số liệu -> Con người -> Địa phương: Cập nhật mã địa phương làm địa chỉ của bệnh nhân
  - Mã tỉnh: Chọn nút chỉnh (hình cây bút) trước tên tỉnh, nhập mã liên thông rồi lưu lại, ghi theo 02 ký tự cuối của mã đơn vị hành chính của tỉnh (quy định tại Phụ lục 1 Thông tư số 07/2016/TT-BCA ngày 01 tháng 2 năm 2016 của Bộ trưởng Bộ Công an)
 
  - ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/e88ea037-c049-4f7c-a638-f48238daa434)
 
  - Mã huyện: Chọn nút chỉnh (hình cây bút) trước tên huyện, nhập mã liên thông rồi lưu lại, ghi mã đơn vị hành chính cấp huyện theo Quyết định số 124/2004/QĐ-TTg ngày 08/7/2004 của Thủ tướng Chính phủ hoặc sử dụng mã đơn vị hành chính mới được cấp có thẩm quyền cấp
 
  - ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/39a3cc98-8be8-4795-a9e1-32024f994434)
 
  - Mã xã: Chọn xã muốn cập nhật mã -> chỉnh thông tin mã liên thông gửi dữ liệu rồi lưu lại (ghi mã đơn vị hành chính cấp xã theo Quyết định số 124/2004/QĐ-TTg ngày 08/7/2004 của Thủ tướng Chính phủ hoặc sử dụng mã đơn vị hành chính mới được cấp có thẩm quyền cấp
 
  - ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/499caa6c-7e1c-45ad-b7fb-302c2e3e29b3)


___II.9 Danh mục nguyên nhân tai nạn___

- Khai báo số -> Tai nạn -> Nguyên nhân tai nạn: Cập nhật mã quyết định 4750 cho nguyên nhân tai nạn (phụ lục số 4 ban hành kèm theo Quyết định số 5937/QĐ-BYT ngày 30 tháng 12 năm 2021 của Bộ trưởng Bộ Y tế)

- ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/1eb993b4-e72a-418f-a055-a9dda839789d)

- ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/58b5a26e-e95a-408b-a28d-66d28f405515)


___II.10 Danh mục phương pháp vô cảm___

- Khai báo số liệu -> Điều trị -> Cập nhật mã quyết định 4750 cho phương pháp vô cảm (ghi mã phương pháp vô cảm được sử dụng trong phẫu thuật, thủ thuật, trong đó:- Mã "1": Gây mê; - Mã "2": Gây tê; - Mã "3": Châm tê;- Mã "4": các phương pháp vô cảm khác)

- ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/cefa0c0f-8540-4e4c-8bc8-99d1336e5e45)


___II.11 Danh mục kết qua điều trị___

- Khai báo số liệu -> Điều trị -> Cập nhật mã BYT cho kết quả điều trị (Ghi mã kết quả điều trị, trong đó:- Mã "1": Khỏi; - Mã "2": Đỡ; - Mã "3": Không thay đổi; - Mã "4": Nặng hơn; - Mã "5": Tử vong; - Mã "6": Tiên lượng nặng xin về; - Mã "7": Chưa xác định; - Mã "8": Tử vong ngoại viện)

- ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/9dcf1fc8-2940-427c-9d0b-e3d53996277d)


___II.12 Danh mục mã máy thực hiện CLS___

- Khai báo số liệu -> Y tế -> Danh sách mã máy thực hiện CLS -> Cập nhật danh mục máy trả kết quả CLS mã máy BYT (XML4) (Ghi mã các máy thực hiện dịch vụ cận lâm sàng, phẫu thuật, thủ thuật (máy xét nghiệm, máy XQuang, máy siêu âm…), tạm thời được ghi theo nguyên tắc: XX.n.YYYYY.Z, trong đó:
  - XX hoặc XXX: Mã nhóm máy thực hiện, trong đó: Huyết học ghi mã "HH"; vi sinh ghi mã "VS"; sinh hóa ghi mã "SH"; siêu âm ghi mã "SA"; Xquang ghi mã "XQ"; chụp cắt lớp vi tính ghi mã "CL"; chụp MRI ghi mã "MRI"; máy thực hiện phẫu thuật ghi mã "PT"; máy thực hiện thủ thuật ghi mã "TT"; máy xét nghiệm đa chức năng thì ghi mã "DC"; máy xạ trị ghi mã "XT"; máy chụp SPECT ghi mã "SP"; máy chụp PET/CT ghi mã "PET"; máy xạ hình xương ghi mã "XH"; máy nội soi ghi mã "NS"; máy chụp mạch xoá nền DSA ghi mã "DSA"; máy điện tim ghi mã "ĐT",....(Đối với các máy chưa quy định mã nhóm máy (XX hoặc XXX) thì ghi các chữ cái đầu tiên theo phiên âm tiếng Việt của máy, tối đa không quá 03 ký tự đầu tiên).
  - n: Ký hiệu của nguồn kinh phí mua máy, trong đó:
    - Mã "1": ngân sách nhà nước;
    - Mã "2": xã hội hóa;
    - Mã "3": các nguồn khác;
  - YYYYY: Mã cơ sở KBCB;
  - Z: Số serial của máy (Ghi cả phần chữ và phần số). Trường hợp không có số serial của máy thì sử dụng mã quản lý của máy do cơ sở KBCB lập. Đối với hệ thống máy gồm nhiều máy thì ghi tất cả các serial của các máy, cách nhau bằng dấu chấm phẩy ";"

- ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/77d9eea3-3cc7-4a6c-a1f1-048f18e3e84c)


___II.13 Danh mục ICD 9___

- Bảng mã ICD -> ICD 9 -> Thêm danh mục ICD 9 (danh mục ICD-9 CM do Bộ trưởng Bộ Y tế ban hành kèm theo Quyết định số 4440/QĐ-BYT ngày 27 tháng 10 năm 2020)

- ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/7aa78223-78f0-442e-9b45-ce6df33d7870)


___II.14 Danh mục cận lâm sàng (thông tư 37)___

- Danh mục cận lâm sàng (thông tư 37) -> Cập nhật mã ICD-9 cho CLS phẫu thuật, thủ thuật theo danh mục ICD 9

- ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/9cd3a95b-79cf-4a54-b590-a98ca3826c57)


___II.15 Cấu hình mã chỉ số, tên chỉ số, đơn vị đo CLS___

- Cập nhật thủ công

  - Danh mục CLS (thông tư 37) -> Cấu hình tên chỉ số, mã chỉ số theo Xml 4 (4210) -> Cập nhật thủ công -> Cập nhật mã chỉ số, tên chỉ số và đơn vị đo (bổ sung đơn vị đo) (Ghi mã chỉ số, tên chỉ số và đơn vị đo CLS xét nghiệm, chẩn đoán hình ảnh, thăm dò chức năng, theo Phụ lục số 11 ban hành kèm theo Quyết định số 7603/QĐ-BYT ngày 25 tháng 12 năm 2018 của Bộ trưởng Bộ Y tế. Trường hợp chưa có thì để trống
 
  - ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/92d59b4d-2aa1-4b79-af07-f7fa32abb26c)

- Cập nhật từ file excel (phần mềm chưa hỗ trợ cập nhật đơn vị đo từ file excel)

  - Danh mục CLS (thông tư 37) -> Cấu hình tên chỉ số, mã chỉ số theo Xml 4 (4210) -> Nhập từ file Excel -> Xuất tập tin mẫu sau đó điền thông tin vào vào file excel mẫu (gridXNExcel.xlsx), sau đó chọn nút chọn tập tin -> Kiểm tra cấu trúc (nếu đúng cấu trúc) -> Cập nhật vào hệ thống
 
  - ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/9c6569b9-9e30-4ed6-88bc-dfc5566c7f06)
 
  - ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/4236da32-2b26-46b9-973c-3796164da5c2)
 
  - ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/1fcb8fb0-e817-46ad-af54-36df0ffeb6b2)


___II.16 Danh mục địa phương 4750___

- Hướng dẫn cập nhật danh mục địa phương 4750 mới sử dụng HospitalAdmin.exe v.3.24.0621.1 trở về sau

- Khai báo số liệu -> Con người -> Địa phương 4750

  - Bước 1: vào danh mục địa phương 4750 làm theo hướng dẫn để vào trang website tải danh mục địa phương mới [Link tải] (https://danhmuchanhchinh.gso.gov.vn/Default.aspx)
 
  - ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/2718667d-ca02-4856-89d5-e0c2896bf665)
 
  - ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/aee589a3-ba1c-4a47-8ab6-0f7369fdae09)
 
  - Bước 2: Chọn đơn vị hành chính Cấp tỉnh -> Check chọn Quận Huyện, Phường Xã -> Chọn nút Xuất Excel -> Lưu tập tin về máy.
 
  - ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/09199acc-1a49-446a-9918-2b947dda3bd3)
 
  - Bước 3: Mở file excel Danh sách cấp tỉnh kèm theo quận huyện, phường xã vừa tải về -> Đổi tên sheet thành dmdiaphuong4750 sau đó đóng file này
 
  - ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/f5ff2454-ab5a-42f8-9760-fc2169a01d44)
 
  - Bước 4: Cập nhật danh mục địa phương 4750 vào phần mềm:
    - Tại danh mục địa phương theo 4750 chọn nút Import Excel
    
    - Trên thư mục chọn file chỉnh Files of type thành Excel 2003 files (*.xls) sau đó tìm đường dẫn đến thư mục chứa tập tin cần import -> Chọn tập tin -> Chọn nút Open
   
    - ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/596bd3ec-6a41-4442-952d-00d8df0f8d30)
   
  - Bước 5: Chọn Đồng ý cập nhật danh mục địa phương 4750 vào phần mềm
 
  - ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/3af76694-a24d-4ca1-a2ff-9c35b2e1fdee)
 
  - ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/5ba00664-195c-407d-90b3-f4a49822029e)




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

- ![image](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/b36c6a3f-f4a8-410a-a352-0096d0816714)

- Dạng bào chế: Ghi dạng bào chế của thuốc (đối với thuốc hoá dược) hoặc dạng bào chế, chế biến của thuốc (đối với thuốc cổ truyền, thuốc dược liệu) theo thông tin được Cục Quản lý Dược hoặc Cục Quản lý Y, dược cổ truyền cấp giấy đăng ký lưu hành. Trường hợp thuốc do cơ sở KBCB tự bào chế, chế biến thì ghi dạng bào chế, chế biến của thuốc theo đúng hồ sơ được người đứng đầu cơ sở KBCB phê duyệt.

- ![image](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/da2f8c63-4452-4ac6-972c-96d41bc30f0c)


___III.2 Danh mục VTYT___

- TT Thầu 4750: Ghi thông tin thầu của VTYT theo thứ tự, gồm: Số quyết định phê duyệt kết quả lựa chọn nhà thầu; số gói thầu; mã nhóm thầu; năm ban hành quyết định phê duyệt kết quả lựa chọn nhà thầu. Các thông tin này cách nhau bằng dấu chấm phẩy “;”. Lưu ý:
  - Những VTYT đã được đấu thầu mua sắm hoặc đã được phê duyệt kế hoạch lựa chọn nhà thầu trước ngày 14/4/2023: Sử dụng mã nhóm thầu VTYT theo Phụ lục 7 ban hành kèm theo Quyết định số 5937/QĐ-BYT ngày 30/12/2021 của Bộ trưởng Bộ Y tế;
  - Những VTYT được đấu thầu mua sắm hoặc được phê duyệt kế hoạch lựa chọn nhà thầu kể từ ngày 14/4/2023: Tạm thời sử dụng mã nhóm thầu là "N0";
  - Trường hợp VTYT áp thầu thì Trường thông tin TT_THAU của VTYT ghi như sau: Số quyết định.Mã đơn vị ban hành quyết định;Gi;Ni;XXXX. Mã đơn vị ban hành quyết định trúng thầu của VTYT thực hiện như sau: TTMSTT quốc gia là mã "00"; trường hợp các tỉnh, thành phố đấu thầu tập trung thì sử dụng mã tỉnh, thành phố; trường hợp cơ sở KBCB đấu thầu thì sử dụng mã cơ sở KBCB; Gi là số gói thầu; Ni là số nhóm thầu; XXXX là năm ban hành quyết định).
  - Trường hợp VTYT tự sản xuất: Số quyết định trúng thầu thì ghi theo số văn bản gửi cơ quan BHXH, năm ban hành quyết định thì ghi năm ban hành văn bản
  - Trường hợp VTYT được phê duyệt kế hoạch lựa chọn nhà thầu trước ngày Thông tư số 14/2020/TT-BYT có hiệu lực thì trường TT_THAU ghi như sau: Số quyết định.Mã đơn vị ban hành quyết định;Gi;XXXX

- ![image](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/06dc5823-e61f-49cf-bfba-44176ca948a3)


__IV. Gửi dữ liệu XML theo quyết định 4750 cổng đào tạo BHXH__

___IV.1 Cấu hình tài khoản và XML cần gửi cổng đào tạo___

- Cập nhật tài khoản và XML 4750 cần gửi cổng đào tạo BHXH: Vào cấu hình gửi tự động -> API Gửi dữ liệu -> Cấu hình tài khoản, mật khẩu cổng đào tạo 4750 của đơn vị và chọn các bảng XML cần gửi cổng hoặc cần xuất ra file XML -> Kiểm tra thử kết nối nếu phần mềm báo kết nối thành công là hoàn thành.

- ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/08c854f9-48a7-4f2a-a47d-4cbdc89e405b)

- ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/392bb894-ce46-4216-b2b3-bae044ddbba2)

- ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/5db42153-7051-45ec-9574-146da37fb4c3)


___IV.2 Gửi dữ liệu lên cổng đào tạo và xuất file XML 4750___

- Vào kiểm tra xuất XML -> Lấy dữ liệu danh sách bệnh nhân cần gửi XML -> Chọn hồ sơ bệnh nhân (có thể chọn nhiều hồ sơ bệnh nhân bằng chức năng chọn nhiều hồ sơ) -> Chọn chức năng Gửi XML theo QĐ130-cổng đào tạo hoặc Xuất XML 4750 tùy theo nhu cầu.

- ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/1600adee-e609-4186-b37b-0419f96e7566)

- ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/18bf0dd1-82a8-4e49-9f78-0d9adb3ef765)

- ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/1803b0eb-1ed2-49cd-b8c0-5e4fd3334472)


__V. Những lưu ý chức năng mới và ràng buộc nhập liệu__

___V.1 Nhận bệnh và hiệu chỉnh thông tin___

- Yêu cầu phần mềm Prescription.exe v.3.24.0620.8, Register.exe v.3.24.0620.0, Treatment.exe v.4.24.0620.0 trở về sau

- Phường, xã: Cần nhập đầy đủ 3 cấp tỉnh, huyện, xã để phần mềm lấy đủ thông tin mã tỉnh, mã huyện, mã xã gửi dữ liệu XML 4750 (bắt buộc)

- ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/7ec6cfee-63ae-4779-86f7-1e7814ef91e8)

- Ô CMND: Có thể nhập 1 trong các loại giấy tờ sau: số CMND 10 số, số CCCD 12 số, số hộ chiếu 8 ký tự (1 ký tự chữ in hoa + 7 số)

- ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/81e647c0-d841-4da7-8aa1-794ec91d00bf)

- Nhóm máu: bổ sung nhóm máu bệnh nhân vào phần chỉ số sinh hiệu ở nhận bệnh, hiệu chỉnh thông tin bệnh nhân (sử dụng Register, Prescription, Treatment, Admin từ ngày 21/06/2024 về sau)

- ![image](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/3e7e42f7-2d1f-408a-b888-ad99389cdc9b)

- ![image](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/a004af5e-772b-455b-a361-a5f3fcc6f4f5)


- Có thêm chức năng nhập giấy xác nhận lưu trú và thông tin giấy hẹn, giấy chuyển tuyến. Hướng dẫn chi tiết: [Hướng dẫn nhận bệnh có giấy xác nhận lưu trú - giấy hẹn và giấy chuyển tuyến] (https://gofile.me/78TQg/aAzEHMxdm)


___V.2 Cấp toa___

- Yêu cầu phần mềm Prescription.exe v.3.24.0620.8, Treatment.exe v.4.24.0620.0 trở về sau

- Bổ sung chức năng nhập số lượng thuốc 1 ngày sáng, trưa, chiều, tối khi cấp toa ngoại trú, BANT, nội trú

- ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/a7b67318-267a-422a-b54e-2c9cc4eb5d99)

- ![ảnh](https://github.com/dh-hos/To_Ho_Tro/assets/97272332/083bbca8-e475-4302-a73c-ce8e37fb47a3)






