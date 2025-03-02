# Hướng dẫn thao tác cơ bản
# Bước 1: Hàn diode lên PCB "hướng phải đúng chiều", hướng diode như hình, mặc định lỗ tròn qua lỗ vuông trên PCB để dễ hình dung 
![h1](https://github.com/Hieupham0012/Guide_banime40_DIY/blob/main/h%C3%ACnh/IMG_4033.jpg)

# Bước 2: Hàn hotswap lên PCB
# Bước 3: Hàn chân MCU lên PCB đúng hướng như hình, và sau đó hàn MCU vào chân đã hàn lên PCB trước đó.
![h2](https://github.com/Hieupham0012/Guide_banime40_DIY/blob/main/h%C3%ACnh/IMG_3336.jpg)
# Bước 4: Hàn Reset "nên hàn để dễ flash về sau, có thể chập chân reset trên mạch không cần hàn reset"
![h3](https://github.com/Hieupham0012/Guide_banime40_DIY/blob/main/h%C3%ACnh/IMG_4034.jpg)

# Bước 5: Nạp code và để test mạch hoàn thiện. "nạp code bằng QMK toolbox bằng file trên", tải file .hex để nạp. Cách nạp: chọn đường dẫn đến file hex đã tải, chọn tick ô auto flash, chọn đúng chip atmega32u4
![]()
# Bước 6: Cắm dây type c từ máy tính vào mạch atmega32u4, Mạch ban đầu sẽ tự flash luôn. Nếu không thì nhấn giữ reset 2 giây rồi nhả ra nhấn lại và nhả 1 lần nữa liền. 
![video cách bấm reset](https://www.youtube.com/shorts/RQlWx_O3xkk)
