=============
Live Report  
=============

**CMS KPI**
===================

1. Contract KPI
---------------
 
 Xem số lượng lead theo chiến dịch

 .. image:: _static/images/ContractKPI1.png
    :width: 400pt

 Đặc tả:
  
  + Lead: tổng số lead
  + Coupon: tổng số lead được được phân
  + App: tổng số lead có lịch hẹn
  + Visit: tổng số lead đã đến trung tâm 
  + Contract (MKT): tổng số lead đã chuyển thành học viên được tính cho MKT 
  + Contract (School): tổng số lead đã chuyển thành học viên được tính cho School
 
  .. note::
    - Chương trình ASP: Nếu ngày tạo lead so với ngày chuyển học viên dưới **30** ngày thì Contract được tính cho MKT còn ngược lại được tính cho trường
    - Chương trình KDG, BR01: Nếu ngày tạo lead so với ngày chuyển học viên dưới **60** ngày thì Contract được tính cho MKT còn ngược lại được tính cho trường
    - Chương trình ASP: Nếu ngày tạo lead so với ngày chuyển học viên dưới **90** ngày thì Contract được tính cho MKT còn ngược lại được tính cho trường
    - Ngày chuyển học viên được tính theo trạng thái CONTRACT và Contracted

  + Contracted Day: ngày chuyển đổi thành học viên

2. Registration
---------------

 Xem sỉ số bé tại trung tâm

 .. note::
    Báo cáo có chạy job

 .. image:: _static/images/Registration1.png
    :width: 400pt


 + Actual: số lượng hv trong ngày
 + Net: số lượng tăng/giảm so ngày trước
 + Prev: số hv so với cuối tháng trước

 .. note::
    Actual, Net, Prev: tính theo công thức báo cáo Enrollment

 + New Register: số đăng ký mới
 + Saving: bảo lưu

 .. note::
    Tính theo báo cáo Saving

 + Waiting: chờ lớp

 .. note::
    Tính theo báo cáo Waiting
    
 + Teacher: số lượng giáo viên
 + Rate: tỷ lệ Teacher/Actual
 + NSU: số học viên mới

3. New Cash In
---------------

4. Enrollment
---------------

5. Re-Enrollment
----------------

Xem số lượng tái tục theo tỷ lệ học phí mới

Điều kiện lấy hv trong tháng:
 + Hv có học phí cho vào lớp trong tháng/năm xem báo cáo, và tổng học phí >= **50%** học phí lớp 

Điều kiện tính Re-Enrollment theo tháng tiếp theo
 + Tháng/Năm hv bắt đầu học sau thời điểm đang xem 
 + Hoặc tháng/năm hv kết thúc lớp sau thời điểm đang xem
 + Hoặc tháng/năm khai giảng lớp sau thời điểm đang xem 
 + Hoặc tháng/năm kết thúc lớp sau thời điểm đang xem 
 + Và tổng học phí bỏ vào lớp >= **80%** học phí lớp 

.. note::
    + Tổng học phí bỏ vào lớp được tính bằng tổng số tiền bỏ vào lớp có ngày trước ngày bắt đầu của lớp 
    + Học phí số tiền trong tab Học phí màn hình chi tiết học viên 

6. Enrollment By Day
--------------------

7. Waiting
----------


7. Collection analytics
-----------------------


9. Revenue analytics
-----------------------


10. NSU analytics
-----------------------






