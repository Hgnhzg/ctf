- MẠNG CHUYỂN MẠCH KÊNH khi cần trao đổi thông tin với nhau thì giữa chúng 
sẽ thiết lập 1 kênh cố định và duy trì kênh vật lý đó cho đến khi 1 
trong 2 trạm ngắt liên lạc.
vd : chuyên mạch của điện thoại
- MẠNG CHUYỂN MẠCH THÔNG BÁO ưu hơn mạch kênh.
- MẠNG CHUYỂN MẠCH GÓI (PACKED) 
  + Datagram : ứng dụng mạng trao đổi ít
  + Chuyển mạch ảo (kênh logic) : VC và PVC
- MÔ HÌNH OSI : 7 tầng
1 - physical vật lý : nhận khung tin (frame) dữ liệu
2 - datalink liên kết dữ liệu : làm mọi thứ về khung tin/packet
3 - network mạng :  định dạng thông báo là packet
4 - transport giao vận : đảm bảo gói tin tới đích k sai
5 - session phiên : ép các bên tuân thủ
6 - presentation trình diễn
7 - application ứng dụng
- KỸ THUẬT ĐIỀU CHẾ FSK
- KỸ THUẬT ĐIỀU CHẾ M-FSK

- SUY GIẢM TÍN HIỆU ![image](https://github.com/user-attachments/assets/876a09e5-c1b3-49f5-bfac-7ef7323eb52c)
- TỶ SỐ TÍN HIỆU TRÊN NHIỄU : ![image](https://github.com/user-attachments/assets/7a2a29d0-22a2-4248-bd93-4f64fb49514f)
  +) TẠP ÂM NHIỆT :
  
   N0 là mật độ công suất tạp âm [Watt.Hertz]
   K là hằng số Boltzman, K = 1,38 x 10-23 J/0K
   T là nhiệt độ Kelvin
   Tạp âm nhiệt trong toàn giải băng W (Hz) sẽ là:

   N = K.T.W [w.Hz]
-  Công thức Nyquist : giả sử trong môi trường truyền không có nhiễu.
  C = 2Wlog2M (bps)

  C: Tốc độ kênh truyền cực đại (bps)
  W: Băng thông của kênh truyền (Hz)
  M: Số mức thay đổi của tín hiệu trên đường truyền.

- Công thức Shannon – Hartley : Tốc độ cực đại của kênh truyền trong trường hợp kênh truyền có
nhiễu.
 ![image](https://github.com/user-attachments/assets/ef1e85b4-ad72-428c-b523-c02a367c11e4)

![image](https://github.com/user-attachments/assets/f190bd61-ac4d-41d9-878b-3b1cb772146f)







  
