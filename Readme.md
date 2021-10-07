# OSINT CHALLENGE

## Internet love

***Desciption***

Bạn có thể tìm thấy @username của ID Twitter này 44196397. Format flag: flag{username}

---

***Writeup***

- Chúng ta sử dụng trang web <https://tweeterid.com/> để tra cứu Twitter @username dựa trên ID

![Image](.\image\internet_love_image_1.png)

---

> Flag thu được : `flag{elonmusk}`

---

## Contact

***Desciption***

I like Bot gg/GXtshq7Qwe format flag: flag{namebot}

---

***Writeup***

- Ta search gợi ý   `gg/GXtshq7Qwe` trên google và ta thu được một số thông tin đường dẫn: <https://discord.gg/GXtshq7Qwe>


![Image](.\image\contact_image_1.png)

- Sau khi vào đường link ta được di chuyên sang trang <https://discord.com/invite/GXtshq7Qwe> và ở đó thì ta có được lời mới từ một bot tên là knapstack

![Image](.\image\contact_image_2.png)

---

> Flag thu được : `flag{knapstack}`

---

## Eyes

***Desciption***

Sing with me: You are very beautiful.... format flag: flag{name-of-this-place}

[eyes.jpg](image\eyes.jpg)

---

***Writeup***

- Đâu tiên, ta sử dụng <https://yandex.com> để tìm kiếm thông tin về hình ảnh đã cho

![Image](.\image\eyes_image_1.png)

- Ta tiếp tục sử dụng các thông tin và đường dẫn bên dưới để tiếp tục tìm kiếm ta thu được một số địa danh

![Image](.\image\eyes_image_2.png)

- Ta tiếp tục tìm kiếm dựa trên các đia danh thì ta thu được hồ T'Nưng là nơi xuất phát của ảnh gợi ý

![Image](.\image\eyes_image_3.png)

>Nhưng đây chưa phải là kết quả :))

- Ta tiếp tục sử dụng google để tìm kiếm thêm các thông tin về hồ T'Nưng và ta phát hiện ra rằng hồ T'Nưng còn có tên gọi khác là Biển Hồ, Biển Hồ Pleiku, hồ Tơ Nưng,...

![Image](.\image\eyes_image_4.png)
  
---

> Sau 7749 lần brute force thì ta thu được flag: `flag{Bien-Ho}`

---

## Thiên tài bất hảo

***Description***


Hãy giúp tôi nào!!! Tôi đang hoàn thành bài kiểm tra và tôi đang cần bạn tìm cho tôi một vài thứ. Tôi tin rằng bạn sẽ tìm thấy. Tôi đang cố nhớ tên giáo sư đang dạy tôi nhưng tôi chả nhớ nổi… người này là giáo sư duy nhất tại UC San Diego, đồng thời là trợ lý giáo sư (Assistant Professor) cho Khoa Khoa học Máy tính (Computer Science) vừa là phó giáo sư cho Khoa Toán (Mathematics). Format flag: flag{Họ và tên giáo sư}.Không bao gồm tên đệm và cách nhau bằng một dấu cách.

---

***Background***

Để có thể làm được bài bài này thì chúng ta còn có một chút hiểu biết về [google hacking](https://whitehat.vn/threads/google-hacking-kien-thuc-co-ban-ma-pentester-thuong-bo-qua.8092/)

- Từ khóa `site:` để giới hạn kết quả trả về ở một số website cụ thể

- sử dụng biểu tương `""` để kết quá trả về phải có chính xác từ cần tìm kiếm

- `()` được sử dụng để nhóm các cụm từ tìm kiếm và kiểm soát logic tìm kiếm của truy vấn.

- `|`  sẽ trả về kết quả tìm kiếm phù hợp với các cụm từ ở hai bên của đường ống dẫn. Giống như cách viết "HOẶC" giữa các cụm từ tìm kiếm.

>NOTE: Có thể phải tìm kiếm trên nhiều trang web các nhau nêu các các trang đó chưa thông tin giống như trong truy vấn

- Dựa vào đề bài thì chúng ta sẽ sử dụng một số format sau để tìm kiếm: "Assistant Professor", "Computer Science", "Mathematics" và cụm từ có liên quan UC San Diego. Ngoài ra chúng ta cũng cần phải tìm kiếm các cụm từ đồng nghĩa có khả năng như "Associate Professor" <=> "Assistant Professor" và ta cũng có thể loại bỏ dần các cụm như "Computer Science", UC San Diego nếu khó khăn trong việc tìm kiếm
---

***Writeup***

- Sau khi ta thực hiện một số truy vấn (thật ra là rất nhiều) ta không thu được kết quả cần có. Ta sẽ bắt đầu bỏ qua một số cụm từ như "Computer Science" và ta thu được đường dẫn <https://math.ucsd.edu/>

![Image](.\image\thien_tai_bat_hao_image_1.png)

- Vào đường dẫn đó và tiếp tục các giáo sư bằng các thông tin trên ta thu được một người hợp lệ (brute force đến chết)

![Image](.\image\thien_tai_bat_hao_image_2.png)

---

> Flag thu được là: `flag{Alina-Bucur}`

---


## Music

***Description***

Do you like number 17076? Do you like listening to music? Format flag: flag{....}

[music_2.txt](.\file\music_2.txt)

---

***Writeup***

- Tìm đến vị trí 17076 trong file music_2.txt ta thu được 'v=5m4QcGCBoC0'

![Image](.\image\music_image_1.png)

- Tìm kiếm v=5m4QcGCBoC0 ta thu được một đương dẫn đến youtube

![Image](.\image\music_image_2.png)

- Do tới đây ta không còn gợi ý gì thêm nên chúng ta tiếp tục tìm kiếm trong đường link youtube trên và ta nhận ra được comment bất thường đến từ bạn Lê Thanh Duẩn :))

![Image](.\image\music_image_3.png)

---

>Flag thu được: `flag{Osint-is-cool}`

---

## Địa lý lớp 6

***Description***
Tìm tọa độ của mỗi vị trí. Format flag: flag{vĩ độ hình 1, kinh độ hình 1, vĩ độ hình 2, kinh độ hình 2}. Vĩ độ và kinh độ chính xác tới 3 chữ số thập phân sau dấu phẩy và không chứa khoảng cách trong flag.

[picture1](.\image\picture1.png)

[picture2](.\image\picture2.png)

---

***Writeup***




---

>Flag thu được: `flag{Osint-is-cool}`

---

## Thấy chuyện bất bình, chụp màn hình gửi quý dzị!

***Description***

Cách đây không lâu, một admin của diễn đàn công nghệ trong 1 lần review trải nghiệm sản phẩm đã vô tình làm lộ mật khẩu của mình, bạn có thể tìm ra password này là gì không? Hint: v=BtulL3oArQw Format flag: flag{textpassword}

---

***Writeup***

- Từ các thử thách 'Music' ta biết được `v=BtulL3oArQw` sẽ nằm trong một link youtube

![Image](.\image\admin_1.png)

- Sau một lúc tìm kiếm thì tương tự trong thử thách `Music` ta phát hiện comment bất thường đến từ bạn Lê Thanh Duẩn và đây cũng tiếp tục là một link youtube

![Image](.\image\admin_2.png)

- Đi tiếp theo link youtube đó và tiếp tục tìm đến phần comment và ta vẫn phát hiện bạn Lê Thanh Duẩn với một gợi ý khác link youtube :))

![Image](.\image\admin_3.png)

- Tìm kiếm gợi ý `Stirring16/LassPass` trên google nhưng không thu được kế quả nhưng nếu chúng ta tách `stirring16` ra để tim kiếm thì ta sẽ tìm được một user github và user đó có một repository có tên là 'LassPass'

![Image](.\image\admin_4.png)

- Trong repository đó ta có 3 file cần phần tích 

![Image](.\image\admin_5.png)

- Phân tích file `bash` ta thấy được được một dòng lệnh khả nghi

![Image](.\image\admin_6.png)

- Phân tích tiếp file `bashrc2` ta thu được giá trị của biến `CODE` và kết hợp với link được tìm thấy trong câu lệnh trên ta thu được một link hoàn chỉnh <https://pastebin.com/D6MQgdyv>

![Image](.\image\admin_7.png)

- Chuyển đến link đo ta thu được một chuỗi mã có khả năng là mã Bas64

![Image](.\image\admin_8.png)

- Ta thực hiên decode Bas64 thì lại tiếp tục thu được một link youtube có móc thời gian

![Image](.\image\admin_9.png)

- Nhìn kĩ vào khung video tại thời điểm đó ta thấy được một đoạn mã

![Image](.\image\admin_10.png)

---

![Image](.\image\admin_11.png)

---

>Flag thu được: `flag{gernuv-2jiKke-vywjec}`

---

## Message

***Description***

A drone captured the location of the wanted hacker After the police arrived, he must have run away and left a message What is that message? (hint:something is wrong wrong) Fortmat flag: flag{a-b-c-d-f}

[UIT.png](.\image\UIT.png)

---

***Writeup***

- Từ hình ảnh gợi ý ta biết được đây là trường Đại học Công nghệ thông tin :))

- Lưu ý rằng trường có 4 tòa A, B, C, D, E nhưng trong flag lại là a-b-c-d-f và dựa vào gợi ý `something is wrong wrong` thì ta có thể hiểu rằng điều sai sẽ nằm ở tòa E của trường

![Image](.\image\message_image_1.png)

- Thực hiện chuyển google sang chế độ xem phố xung quanh tòa E của trường ta phát hiện ra gợi ý `something is wrong wrong` ở dạng tiếng việt trong một căn phòng học của trường. [*here*](https://www.google.com/maps/@10.8698544,106.802631,3a,75y,72.53h,90t/data=!3m8!1e1!3m6!1sAF1QipMKUz65tfZKZ4csBvUQRg0GIM66cqJMGjuMgKEL!2e10!3e11!6shttps:%2F%2Flh5.googleusercontent.com%2Fp%2FAF1QipMKUz65tfZKZ4csBvUQRg0GIM66cqJMGjuMgKEL%3Dw203-h100-k-no-pi-0-ya186.23415-ro-0-fo100!7i8704!8i4352?hl=vi-VN)

![Image](.\image\message_image_2.png)

![Image](.\image\message_image_3.png)

- Mặc dù cụm `Sai gì đó đúng đúng` vừa đủ số ký tự cho flag nhưng chúng ta vẫn phải brute force đến chết để tìm ra kết quả

![Image](.\image\message_image_4.png)

---

>Flag thu được: `flag{Co-gi-ddo-Sai-Sai-Sai-gi-do-dung-dung}`

---
