# IntroductionToAIBTL1

## Chuẩn bị Thư Viện
chạy lệnh sau để cài đặt thư viện:
```
    pip install -r requirement.txt
```
## Các file được viết:
### Seting.py
Bao gồm các setting cơ bản để hiển thị visualize được định nghĩa trong class setting gồm
```
    self.cellWidth #### Kích thước của 1 ô, kiểu dữ liệu số
    self.alpha ### độ nghiêng khi vẽ của 1 ô, kiểu dữ liệu số
    self.color ### mã màu rgb khi vẽ bàn chơi với,kiểu dử liệu list các tuple
               ### Với các phần tử trong list này lần lượt là mã rgb cho màu của
               ### background, ô chịu được sức nặng yếu, ô chịu được sức nặng mạnh, ô đích, nút nhẹ và nút nặng

```