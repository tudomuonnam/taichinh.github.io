---
title: "Chiến lược đầu tư chứng khoán"
date: "2020-10-23"
draft: false
author: Long Vũ
tags: [chiến lược, đầu tư, chứng khoán]
---
## Lời mở đầu

Chứng khoán đã thành từ khoá hot trong năm 2020 nhờ covid lockdown, làm việc ở nhà khiến mọi người quan tâm đến đầu tư. Một lượng lớn tham gia đầu tư với mong muốn giàu nhanh, muốn làm việc toàn thời gian với đầu tư để kiếm lợi nhuận "không tưởng" tốt hơn lương đi làm. Kết quả là, có đến 90% nhà đầu tư mất tiền trên sàn. Con số có vẻ không khác bao nhiêu so với trào lưu khởi nghiệp trước đó.

Một trong những lý do hàng đầu để nhà đầu tư (NDT) mất tiền là không có chiến lược đầu tư cụ thể. Công việc hằng ngày là lên mạng nghe ngóng, thấy mọi người "phím hàng" cổ phiếu nào là đầu tư. Không phân tích cơ bản, không phân tích kĩ thuật, không backtest, không ... gì cả. Nhờ những NDT thế này nên các đội lùa gà, phao tin, nhóm kín, đầu tư tiền ảo, đa cấp 4.0 luôn có đất làm ăn và kết quả là NDT mất tiền vẫn không rút ra kinh nghiệm.

Vì vậy, series các chiến lược đầu tư chứng khoán sau đây sẽ mô tả kiến thức cơ bản để các NĐT có cái nhìn tổng quan về việc sử dụng đồng tiền ra sao để mang về lợi nhuận.

## Mua và giữ 
### Khái niệm 
Mua và nắm giữ là một chiến lược đầu tư thụ động, trong đó một nhà đầu tư mua cổ phiếu (hoặc các loại chứng khoán khác như ETF) và nắm giữ chúng trong một thời gian dài bất kể biến động trên thị trường. 

Một nhà đầu tư sử dụng chiến lược mua và nắm giữ chủ động lựa chọn các khoản đầu tư nhưng không quan tâm đến biến động giá ngắn hạn và các chỉ số kĩ thuật. Nhiều nhà đầu tư huyền thoại như Warren Buffett và Jack Bogle ca ngợi cách tiếp cận mua và nắm giữ là lí tưởng cho các cá nhân tìm kiếm lợi nhuận dài hạn lành mạnh.

Thay vì coi quyền sở hữu cổ phiếu như một phương tiện ngắn hạn để kiếm lợi nhuận như các traders, các nhà đầu tư mua và nắm giữ cổ phiếu trong suốt các phiên giao dịch của thị trường tăng giá và giảm giá (bull and bear markets). Do đó, chủ sở hữu cố phiếu sẽ là người chịu thất bại cuối cùng hoặc là người nhận được phần thưởng xứng đáng với sự chờ đợi.

(Nguồn: vietnambiz)

Mua và giữ là chiến thuật cơ bản rất quan trọng. Là tham chiếu mà các chiến thuật khác luôn phải soi lại khi đánh giá hiệu quả chiến thuật của mình.

### Lợi ích và rủi ro
1. __Lợi ích__
- Là phương pháp đầu tư thụ động, không cần quan tâm đến thị trường, phân tích ... chỉ cần đầu tư một lượng (tiền, cổ phiếu) cố định vào một cổ phiếu/chỉ số nhất định. Chỉ số (như VN30) có mức dao động rất thấp.
- Về dài hạn chỉ số sẽ có xu hướng tăng.
- Chi phí duy trì tài khoản rất thấp (0.3%/năm so với quỹ đầu tư chủ động 3%/năm)
2. __Rủi ro__
- Lựa chọn chỉ số đầu tư rất quan trọng. Đầu tư lâu dài thường sử dụng một chỉ số như VN30, VN100 để đầu tư. Nếu đầu tư dựa vào cổ phiếu có thể chịu rủi ro quản trị công ty, rủi ro thị trường ...
- Khá buồn chán, không có gì hay ho, kịch tính hằng ngày để theo dõi. Về mặt tâm lý, đây có thể là rào cản lớn đối với các NDT chưa rèn luyện được cảm xúc trên thị trường.

## Cách làm
- Mua và quên (set and forget): NĐT sử dụng một khoản tiền mua chứng khoán và để đó. Không mua bán gì thêm. Cách làm này có thể sử dụng khi bạn nhận được một số tiền lớn (bán nhà, trúng số .. )
- Bình quân giá mua. Đây là cách các NDT thụ động hay áp dụng nhất. Cú sau một khoảng thời gian cố định (hằng tuần, tháng, quý ...) bạn bỏ một số tiền cố định để mua tài sản (chứng khoán, chỉ số, vàng ...) bất kể giá tăng hay giảm.

## Thực tế tại Việt Nam
Sau đây là backtest chiến thuật mua và nắm giữ tại thị trường Việt Nam. Sử dụng chỉ số VN30.
Thời gian từ 01/10/2019 đến 01/10/2020. Mua hàng tháng, tại ngày 01 (hoặc ngày kế tiếp nếu ngày 01 không giao dịch)
1. Mua và quên 
![Chiến thuật mua và quên](/post/strategy/img/buy-hold-buy.png)
Return on Investment (ROI) của chiến lược này là : -6.78%. Nghĩa là, nếu bạn đầu tư 100 triệu vào chỉ số VN30 cách đây 1 năm bạn sẽ mất gần 7 triệu 
2. Bình quân giá mua 
![Chiến thuật mua và mua thêm](/post/strategy/img/buy-hold-more.png)
ROI = 120.73. Chiến lược này sinh lời. Bạn nhận được gấp 1,2 lần số tiền bỏ ra! Chiến lược này đặc biệt hiệu quả trong thị trường giá lên.
3. Mua, nắm giữ và mua thêm từ 10/2016
Nếu mọi người chưa phục vì thời gian quá ngắn không thể theo dõi được. Đây là chiến lược mua và giữ từ 10/2016 - 10/2020 (5 năm). Chiến lược này chịu sự điều chỉnh mạnh năm 2018 khi VNINDEX từ 1200 xuống 800. Tuy nhiên chiến lược này vẫn rất mạnh mẽ với ROI tăng 525%. Nghĩa là tăng gấp đôi mỗi năm 
![Chiến thuật mua và mua thêm 2016](/post/strategy/img/buy-hold-more-2016.png)

## Tạm kết

- Mua và nắm giữ là chiến lược rất quan trọng, dễ thực hiện và phù hợp với đa số người dân không có chuyên môn về tài chính. Đây cũng là "ngọn hải đăng" mà các chiến lược khác khi viết ra phải soi lại. 
- Nếu bạn đang dành phần lớn thời gian cho công việc chuyên môn, đang giao dịch thua lỗ ... hãy thử chiến lược này nhé.
- Hiện nay các quỹ ETF dựa trên VN30 có khá nhiều (E1VFVN30, VNX50ETF ...) bạn có thể dễ dàng giao dịch với một tài khoản chứng khoán ở công ty bất kì
- Mua, nắm giữ và mua thêm là chiến lược rất mạnh và dễ thành công với thị trường giá lên. Chiến lược này có thể dễ dàng áp dụng với các tài sản khác: vàng, bất động sản ...


