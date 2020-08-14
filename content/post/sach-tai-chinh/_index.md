---
title: "Sách Tài Chính"
date: 2020-08-12T16:27:23+07:00
author: Long Vũ
draft: False
---

Đọc sách không chỉ mang giá trị giải trí, nó còn là nguồn cung cấp kiến thức đầy đủ và toàn diện nhất. Đọc sách giúp nhớ kiến thức lâu hơn và dễ tra lại đơn giản hơn các cách khác như xem bài giảng Video và "các chuyên gia" mạng giải thích. 

Điểm bất lợi là đọc sách hơi buồn tẻ. Sách kiến thức thì rất khô khan. Sách truyền động lực thì dễ đọc nhưng chả áp dụng được gì cả.

Bản thân mình thích sách hơn Video vì sách rất yên tĩnh. Bạn không bị nhiễu động bởi âm thanh, ánh sáng từ máy tính. Quảng cáo (dù vô tình hay cố ý) từ video là điều mình khó chịu nhất, khiến việc học tập không thể liên tục được.

Ok, quay về nội dung chính. Nếu bạn đọc đủ nhiều và đủ lâu sẽ thấy phần lớn sách đề na ná như nhau. Tìm kiếm được 1 kiến thức mới sau vài trăm trang sách là rất quý giá rồi. Sau đây mình sẽ tổng hợp một số cuốn sách mà mình đọc và cảm thấy bổ ích nhất cho ngành tài chính. Hãy bắt đầu nào!

{{ $sectionPages := where .Site.Pages "sach-tai-chinh" .Section }}
{{ if ge (len $sectionPages) 1 }}
  <ul>
    {{ range $sectionPages }}
      <li>{{ .Title }}</li>
    {{ end }}
  </ul>
{{ end }}