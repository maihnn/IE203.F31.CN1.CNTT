1.   
2. 

\---------------------------------------------------------------------------

3. **Phân tích định lượng quy trình Quản lý mua sắm vaccine**  
   1. **Thời gian**

Giả định sau:

* Một ngày làm việc bằng 8 giờ.  
* Thời gian chờ báo giá: 24 giờ làm việc.  
* Thời gian giao vaccine: 40 giờ làm việc.  
* Thời gian chờ hóa đơn: 8 giờ làm việc.  
* Thời gian chờ thanh toán: 16 giờ làm việc.  
* Các hoạt động song song sau khi xác nhận đơn hàng được tính theo nhánh hoàn thành lâu hơn.

![][image1] 

***Thời gian trung bình chu kỳ:***

Thời gian chu kỳ được tính từ khi đến kỳ dự báo nhu cầu vaccine đến khi hoàn tất đánh giá nhà cung cấp. Thời gian này bao gồm thời gian các bộ phận trực tiếp xử lý, thời gian chờ phê duyệt, chờ nhà cung cấp phản hồi, vận chuyển vaccine, điều chỉnh chứng từ và thanh toán.

* Thời gian xử lý bắt buộc ngoài đoạn song song:  
   4 \+ 3 \+ 2 \+ 1 \+ 0,5 \+ 0,25 \+ 3 \+ 1 \+ 4 \+ 0,25 \+ 2 \+ 1 \+ 1 \+ 1 \+ 0,5 \+ 0,5 \+ 1 \= 26 giờ

* Thời gian chờ bắt buộc:  
   4 \+ 24 \+ 8 \+ 8 \+ 16 \= 60 giờ

* Thời gian chuẩn bị giao nhận được thực hiện song song:  
   Max\[(1 \+ 40); 2\] \= 41 giờ

   Trong đó:  
  * Nhánh theo dõi và chờ giao vaccine: 1 \+ 40 \= 41 giờ.  
  * Nhánh chuẩn bị điều kiện tiếp nhận: 2 giờ.

* Thời gian xử lý ngoại lệ dự kiến:  
   0,15 × 2 \+ 0,10 × 1 \+ 0,20 × (0,25 \+ 8\) \+ 0,30 × (2 \+ 8\) \+ 0,20 × (0,5 \+ 16\) \+ 0,05 × (0,25 \+ 16 \+ 1\) \+ 0,10 × (0,25 \+ 8\) \= 0,3 \+ 0,1 \+ 1,65 \+ 3 \+ 3,3 \+ 0,8625 \+ 0,825 \= 10,0375 giờ

* Trong đó:  
  * Dữ liệu dự báo chưa đầy đủ: 0,15 × 2 \= 0,3 giờ.  
  * Yêu cầu đặt hàng cần điều chỉnh: 0,10 × 1 \= 0,1 giờ.  
  * Báo giá cần bổ sung: 0,20 × (0,25 \+ 8\) \= 1,65 giờ.  
  * Điều khoản cần đàm phán lại: 0,30 × (2 \+ 8\) \= 3 giờ.  
  * Giao hàng có nguy cơ chậm: 0,20 × (0,5 \+ 16\) \= 3,3 giờ.  
  * Vaccine không đạt yêu cầu: 0,05 × (0,25 \+ 16 \+ 1\) \= 0,8625 giờ.  
  * Hóa đơn không khớp: 0,10 × (0,25 \+ 8\) \= 0,825 giờ.

- **Thời gian trung bình chu kỳ:** 26 \+ 60 \+ Max\[(1 \+ 40); 2\] \+ 0,15 × 2 \+ 0,10 × 1 \+ 0,20 × (0,25 \+ 8\) \+ 0,30 × (2 \+ 8\) \+ 0,20 × (0,5 \+ 16\) \+ 0,05 × (0,25 \+ 16 \+ 1\) \+ 0,10 × (0,25 \+ 8\) \= 137,0375 giờ \= 17,13 ngày làm việc

***Thời gian trung bình xử lý:***

Thời gian xử lý chỉ tính thời gian các bộ phận trực tiếp thực hiện công việc, không bao gồm:

* Chờ phê duyệt yêu cầu đặt hàng.  
* Chờ nhà cung cấp gửi hoặc bổ sung báo giá.  
* Chờ nhà cung cấp cập nhật điều khoản.  
* Chờ xác nhận đơn hàng.  
* Thời gian vận chuyển vaccine.  
* Thời gian phát sinh do giao hàng chậm.  
* Chờ vaccine thay thế.  
* Chờ hóa đơn và hóa đơn điều chỉnh.  
* Chờ đến thời điểm thanh toán.

Đối với đoạn công việc song song, thời gian xử lý được tính theo nhánh lâu hơn: Max(1; 2\) \= 2 giờ

Thời gian xử lý lại chủ động dự kiến:

* Bổ sung dữ liệu dự báo: 0,15 × 2 \= 0,3 giờ.  
* Điều chỉnh yêu cầu đặt hàng: 0,10 × 1 \= 0,1 giờ.  
* Gửi yêu cầu bổ sung báo giá: 0,20 × 0,25 \= 0,05 giờ.  
* Đàm phán lại điều khoản: 0,30 × 2 \= 0,6 giờ.  
* Điều phối lại lịch giao: 0,20 × 0,5 \= 0,1 giờ.  
* Yêu cầu đổi và kiểm tra vaccine thay thế:  
   0,05 × (0,25 \+ 1\) \= 0,0625 giờ.  
* Yêu cầu điều chỉnh hóa đơn: 0,10 × 0,25 \= 0,025 giờ.

Tổng thời gian xử lý lại chủ động: 0,3 \+ 0,1 \+ 0,05 \+ 0,6 \+ 0,1 \+ 0,0625 \+ 0,025 \= 1,2375 giờ

- **Thời gian trung bình xử lý:** 26 \+ Max(1; 2\) \+ 0,15 × 2 \+ 0,10 × 1 \+ 0,20 × 0,25 \+ 0,30 × 2 \+ 0,20 × 0,5 \+ 0,05 × (0,25 \+ 1\) \+ 0,10 × 0,25 \= 29,2375 giờ \= 3,65 ngày làm việc

***Hiệu suất thời gian:***

Hiệu suất thời gian \= Thời gian xử lý/Thời gian chu kỳ × 100% \= 29,2375/137,0375 × 100% \= 21,34%

→ Thời gian xử lý chủ động chiếm khoảng 21,34% tổng thời gian chu kỳ. Thời gian còn lại chủ yếu là thời gian chờ: 137,0375 − 29,2375 \= 107,8 giờ \= 13,48 ngày làm việc  
(Hiệu suất thấp chủ yếu do thời gian chờ báo giá, đàm phán, xác nhận đơn hàng, vận chuyển vaccine, điều chỉnh hồ sơ và thanh toán.)

***Khắc phục:***

* Kết nối dữ liệu tiêu thụ, tồn kho và kế hoạch tiêm chủng để tự động hỗ trợ dự báo nhu cầu.  
* Chuẩn hóa yêu cầu đặt hàng và hồ sơ báo giá nhằm hạn chế việc bổ sung, điều chỉnh nhiều lần.  
* Thiết lập thời hạn phê duyệt và gửi cảnh báo khi yêu cầu mua sắm sắp quá hạn.  
* Quy định thời hạn phản hồi báo giá, xác nhận đơn hàng và cập nhật điều khoản đối với nhà cung cấp.  
* Ký thỏa thuận khung với các nhà cung cấp thường xuyên để rút ngắn thời gian đàm phán.  
* Theo dõi tiến độ giao hàng theo thời gian thực và cảnh báo sớm nguy cơ chậm.  
* Yêu cầu nhà cung cấp gửi trước chứng từ và dữ liệu nhiệt độ trước khi vaccine đến kho.  
* Tự động đối chiếu ba bên giữa đơn đặt hàng, phiếu nhập kho và hóa đơn.  
* Duy trì nhà cung cấp dự phòng và mức tồn kho an toàn để hạn chế ảnh hưởng khi giao hàng chậm.  
* Không rút ngắn thời gian kiểm tra chất lượng, dây chuyền lạnh và nghiệm thu vaccine.

  2. **Chất lượng**

Chất lượng của quy trình được đánh giá theo hai khía cạnh:

* **Chất lượng bên ngoài:** phản ánh kết quả mà các đơn vị sử dụng vaccine nhận được, gồm vaccine được giao đúng hạn, đúng chủng loại, đạt chất lượng và có chứng từ hợp lệ.  
* **Chất lượng nội bộ:** phản ánh khả năng thực hiện đúng ngay lần đầu tại các điểm kiểm soát, hạn chế việc bổ sung dữ liệu, điều chỉnh yêu cầu, đàm phán lại, đổi vaccine hoặc sửa hóa đơn.

| Nhóm chất lượng | Chỉ tiêu | Ý nghĩa |
| ----- | ----- | ----- |
| Bên ngoài | Tỷ lệ hoàn tất mua sắm | Tỷ lệ đơn hàng hoàn thành giao nhận, nhập kho và thanh toán |
| Bên ngoài | Tỷ lệ giao hàng đúng tiến độ | Đánh giá khả năng đáp ứng thời gian của nhà cung cấp |
| Bên ngoài | Tỷ lệ vaccine đạt ngay lần giao đầu | Đánh giá chất lượng vaccine và chứng từ giao hàng |
| Bên ngoài | Tỷ lệ cung ứng đạt đầy đủ ngay lần đầu | Tỷ lệ đơn hàng vừa đúng hạn, vaccine đạt và hóa đơn chính xác |
| Nội bộ | Tỷ lệ đạt ngay lần đầu | Tỷ lệ chu kỳ không phải xử lý lại tại bất kỳ điểm kiểm soát nào |
| Nội bộ | Tỷ lệ phải xử lý lại | Tỷ lệ chu kỳ phát sinh ít nhất một nội dung phải khắc phục |
| Nội bộ | Mật độ sai lệch | Số lượt sai lệch dự kiến trên một chu kỳ mua sắm |
| Nội bộ | Tỷ lệ báo giá đầy đủ | Đánh giá chất lượng hồ sơ báo giá của nhà cung cấp |
| Nội bộ | Tỷ lệ hóa đơn khớp chứng từ | Đánh giá độ chính xác của hồ sơ thanh toán |

  1. **Chất lượng bên ngoài**

Các trường hợp chưa đạt đều phải được khắc phục trước khi quy trình tiếp tục:

* Dữ liệu chưa đầy đủ phải được bổ sung.  
* Yêu cầu đặt hàng chưa phù hợp phải được điều chỉnh.  
* Báo giá chưa đầy đủ phải được bổ sung.  
* Điều khoản chưa đạt phải được đàm phán lại.  
* Vaccine không đạt phải được đổi và kiểm tra lại.  
* Hóa đơn không khớp phải được điều chỉnh.

Vì vậy:

* Tỷ lệ hoàn tất quy trình theo thiết kế: 100%.  
* Tỷ lệ vaccine được nghiệm thu trước khi nhập kho theo thiết kế: 100%.  
* Tỷ lệ hóa đơn được đối chiếu trước khi thanh toán theo thiết kế: 100%.  
* Tình trạng giao hàng  
* Giao hàng đúng tiến độ: 80%.  
* Có nguy cơ chậm và phải điều phối lại: 20%.  
* Chất lượng vaccine và chứng từ  
* Vaccine và chứng từ đạt ngay lần giao đầu: 95%.  
* Vaccine hoặc chứng từ không đạt, phải đổi và kiểm tra lại: 5%.  
* Chất lượng hóa đơn  
* Hóa đơn khớp chứng từ ngay lần đầu: 90%.  
* Hóa đơn phải điều chỉnh: 10%.

Giả định ba tiêu chí độc lập, tỷ lệ đơn hàng vừa được giao đúng hạn, vaccine đạt ngay lần đầu và hóa đơn chính xác là: 80% × 95% × 90% \= 68,4%

Suy ra:

* Tỷ lệ cung ứng đạt đầy đủ ngay lần đầu: 68,4%.  
* Tỷ lệ phát sinh ít nhất một sai lệch về giao hàng, vaccine hoặc hóa đơn: 100% − 68,4% \= 31,6%  
* Riêng tỷ lệ đơn hàng vừa đúng tiến độ vừa có vaccine đạt ngay lần giao đầu: 80% × 95% \= 76%  
* Tỷ lệ phải xử lý chậm giao hoặc đổi vaccine: 100% − 76% \= 24%

  2. **Chất lượng nội bộ**

Tỷ lệ đạt ngay lần đầu tại các điểm kiểm soát được giả định như sau:

| Điểm kiểm soát | Tỷ lệ đạt lần đầu | Tỷ lệ phải xử lý lại |
| ----- | :---: | :---: |
| Dữ liệu dự báo đầy đủ | 85% | 15% |
| Yêu cầu đặt hàng phù hợp | 90% | 10% |
| Báo giá đầy đủ | 80% | 20% |
| Điều khoản mua hàng đạt yêu cầu | 70% | 30% |
| Tiến độ giao hàng được bảo đảm | 80% | 20% |
| Vaccine và chứng từ đạt yêu cầu | 95% | 5% |
| Hóa đơn khớp chứng từ | 90% | 10% |

* Giả định các điểm kiểm soát độc lập, tỷ lệ một chu kỳ mua sắm đạt tất cả yêu cầu ngay lần đầu là: 0,85 × 0,90 × 0,80 × 0,70 × 0,80 × 0,95 × 0,90 × 100% \= 29,30%.  
  * Do đó:  
    * Tỷ lệ đạt chất lượng nội bộ ngay lần đầu: 29,30%.  
    * Tỷ lệ chu kỳ phải xử lý lại ít nhất một nội dung: 100% − 29,30% \= 70,70%

* Trên 100 chu kỳ mua sắm, tổng số lượt sai lệch dự kiến là: 15 \+ 10 \+ 20 \+ 30 \+ 20 \+ 5 \+ 10 \= 110 lượt sai lệch  
  * Mật độ sai lệch: 110/100 \= 1,10 lượt sai lệch/chu kỳ

    3. **Khắc phục**  
* Nâng tỷ lệ dữ liệu dự báo đầy đủ ngay lần đầu từ 85% lên tối thiểu 95%.  
* Nâng tỷ lệ yêu cầu đặt hàng phù hợp ngay lần đầu từ 90% lên tối thiểu 95%.  
* Nâng tỷ lệ báo giá đầy đủ từ 80% lên tối thiểu 95% bằng mẫu báo giá chuẩn.  
* Nâng tỷ lệ điều khoản đạt ngay vòng đàm phán đầu từ 70% lên tối thiểu 85%.  
* Nâng tỷ lệ giao hàng đúng hạn từ 80% lên tối thiểu 95%.  
* Nâng tỷ lệ vaccine và chứng từ đạt ngay lần giao đầu từ 95% lên tối thiểu 99%.  
* Nâng tỷ lệ hóa đơn khớp ngay lần đầu từ 90% lên tối thiểu 98%.  
* Giảm mật độ sai lệch từ 1,10 xuống dưới 0,35 lượt/chu kỳ.  
* Nâng tỷ lệ đạt chất lượng nội bộ ngay lần đầu từ 29,30% lên tối thiểu 70% trong giai đoạn đầu.  
* Duy trì 100% vaccine chỉ được nhập kho sau khi đạt nghiệm thu và 100% hóa đơn chỉ được thanh toán sau khi đối chiếu đầy đủ.

  3. **Chi phí**

Giả định:

* Nhân sự thuộc Bộ phận mua hàng, Bộ phận kho và Tài chính đều có chi phí nhân công: 500.000 VNĐ/người/ngày làm việc  
* Một ngày làm việc kéo dài: 8 giờ

Thời gian được sử dụng theo kết quả phân tích trước:

* Thời gian chu kỳ trung bình: **137,0375 giờ**.  
* Thời gian xử lý trung bình: **29,2375 giờ**.  
* Thời gian không xử lý trực tiếp:  
   **137,0375 − 29,2375 \= 107,8 giờ**.

## ***Chi phí nhân công theo giờ:*** 500.000/8 \= 62.500 VNĐ/giờ

## ***Chi phí cho một chu kỳ mua sắm vaccine:*** 62.500 × 137,0375 \= 8.564.844 VNĐ/chu kỳ mua sắm

***Chi phí xử lý mua sắm vaccine:*** 62.500 × 29,2375 \= 1.827.344 VNĐ/chu kỳ mua sắm

***Chi phí không xử lý trực tiếp:*** 8.564.844 − 1.827.344 \= 6.737.500 VNĐ/chu kỳ mua sắm

***Hiệu suất chi phí*** \= Chi phí xử lý/Chi phí chu kỳ × 100% \= 1.827.344/8.564.844 × 100% \= 21,34%

**Khắc phục:**

* Tự động tổng hợp dữ liệu tồn kho và nhu cầu sử dụng để giảm công sức dự báo.  
* Chuẩn hóa yêu cầu đặt hàng và biểu mẫu báo giá để hạn chế bổ sung hồ sơ.  
* Thiết lập thời hạn phê duyệt và phản hồi cho từng bước.  
* Ký thỏa thuận khung với nhà cung cấp thường xuyên để giảm thời gian đàm phán.  
* Theo dõi tiến độ và cảnh báo sớm nguy cơ giao hàng chậm.  
* Yêu cầu nhà cung cấp kiểm tra vaccine và chứng từ trước khi giao.  
* Tự động đối chiếu đơn đặt hàng, phiếu nhập kho và hóa đơn.  
* Giảm tỷ lệ vaccine phải đổi và hóa đơn phải điều chỉnh.  
* Không cắt giảm hoạt động kiểm tra chất lượng, dây chuyền lạnh và nghiệm thu vaccine..

[image1]: <data:image/png;base64,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>