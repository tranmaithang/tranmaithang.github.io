---
layout: post
comments: true
title: "Bài 1: Giới thiệu về Quantitative Finance"
title2: "1. Giới thiệu về Quantitative Finance"
date: 2025-12-19 12:00:00
permalink: 2025/12/19/introduce/
mathjax: true
tags: General
category: General
sc_project: 13194132
sc_security: c98ecbff
img: /assets/posts/1_introduce/1_gemini_cover.png
summary: Quantitative Finance (Tài chính định lượng), khi những "Phù thủy toán học" làm chủ cuộc chơi tài chính.
---

**Trong trang này:**
- [1. Giới thiệu](#-gioi-thieu)
    - [Quantitative Finance là gì?](#-quantitative-finance-la-gi)
    - [Ba trụ cột chính để trở thành một "Quant"](#-ba-tru-cot-chinh-de-tro-thanh-mot-quant)
    - [Các ứng dụng quan trọng nhất của Quantitative Finance](#-cac-ung-dung-quan-trong-nhat-cua-quantitative-finance)
    - [Tại sao Quantitative Finance lại hấp dẫn?](#-tai-sao-quantitative-finance-lai-hap-dan)
    - [Thách thức của ngành](#-thach-thuc-cua-nganh)
- [2. Mục đích của Blog](#-muc-dich-cua-blog)


<a name="-gioi-thieu"></a>

## 1. Giới thiệu

Nhiều người coi Quantitative Finance là một "chiếc đũa thần" với những công thức phức tạp, nhưng thực chất đó là sự kết hợp khéo léo giữa toán học, lập trình và lý thuyết tài chính. Trong bài viết mở đầu blog, tôi sẽ cùng các bạn giải mã Quantitative Finance – thế giới của những **"Phù thủy toán học"** trên phố Wall.

Có một sự thật thú vị là rất nhiều lý thuyết của Tài chính định lượng có nguồn gốc từ việc cố gắng thắng các sòng bài. [Edward O. Thorp](https://en.wikipedia.org/wiki/Edward_O._Thorp), một giáo sư toán học, được coi là "cha đẻ" của ngành Quantitative Finance, trước khi kiếm được hàng triệu USD trên thị trường chứng khoán, ông đã dùng toán học để đánh bại các nhà cái tại Las Vegas trong trò chơi bài Blackjack. Điều này cho thấy bản chất của Quantitative Finance là: **Tìm kiếm lợi thế nhỏ nhưng bền bỉ trong một hệ thống dường như là ngẫu nhiên**.


<a name="-quantitative-finance-la-gi"></a>

#### Quantitative Finance là gì?

Trong tài chính truyền thống, các quyết định đầu tư thường dựa trên Phân tích cơ bản (Fundamental Analysis) như tình hình kinh doanh của công ty, triển vọng ngành hay các yếu tố kinh tế vĩ mô.

Ngược lại, tài chính định lượng tin rằng các hiện tượng thị trường có thể được mô tả và dự báo thông qua các mô hình toán học. Một người làm Quant không nhìn vào **“câu chuyện”** hay tin đồn, họ nhìn vào **“quy luật”** ẩn mình sau những con số và dữ liệu. Mục tiêu cốt lõi là sử dụng các mô hình toán học phức tạp để định giá tài sản, quản lý rủi ro và xây dựng các chiến lược quản lý danh mục đầu tư tối ưu.

<hr>
<div class="imgcap">
<img src ="/assets/posts/1_introduce/1_gemini_infographic.png" align = "center" style="width: 80%;">
<div style="text-align: center; font-style: italic; font-size: 0.95em; margin-top: 10px; color: #666;"> Hình 1: Các trụ cột chính và ứng dụng của Quantitative Finance.</div>
</div>
<hr>


<a name="-ba-tru-cot-chinh-de-tro-thanh-mot-quant"></a>

#### Ba trụ cột chính để trở thành một "Quant"

Để trở thành một người làm trong lĩnh vực này (thường được gọi là Quant), bạn cần trang bị cho mình những thức kiến thức nền tảng sau đây:

- Toán học: Bao gồm Giải tích ngẫu nhiên (Stochastic Calculus), Xác suất thống kê (Probability Theory), Đại số tuyến tính (Linear Algebra), Phương trình vi phân (Differential Equations). Đây là công cụ để mô tả sự biến động của giá tài sản.

- Lập trình và Khoa học dữ liệu: Các mô hình toán học cần được hiện thực hóa bằng mã code. C++, C#, Java, Python, R là những ngôn ngữ phổ biến nhất để xử lý dữ liệu và chạy các mô hình mô phỏng.

- Kiến thức tài chính: Hiểu về Thị trường tài chính (Financial Market), Chứng khoán phái sinh (Derivatives), Quản trị rủi ro (Risk Management) và Tối ưu hóa danh mục đầu tư (Portfolio Theory).


<a name="-cac-ung-dung-quan-trong-nhat-cua-quantitative-finance"></a>

#### Các ứng dụng quan trọng nhất của Quantitative Finance

Quantitative Finance được ứng dụng rộng rãi trong các tổ chức tài chính lớn như Ngân hàng đầu tư (Investment Bank), Quỹ đầu tư bảo hộ (Hedge Fund), và Quỹ quản lý tài Sản (Asset Management):

- Định giá phái sinh (Derivatives Pricing): Sử dụng các mô hình toán học như Black-Scholes để xác định giá trị hợp lý của các quyền chọn.

- Quản trị rủi ro (Risk Management): Tính toán các chỉ số như Value-at-Risk (VaR) để dự báo mức lỗ tối đa mà một danh mục có thể phải chịu trong những điều kiện thị trường xấu.

- Giao dịch thuật toán (Algo Trading): Xây dựng các hệ thống tự động mua bán dựa trên các tín hiệu kỹ thuật hoặc sự chênh lệch giá nhỏ nhất trong thời gian cực ngắn (High-Frequency Trading).

- Tối ưu hóa danh mục đầu tư (Portfolio Optimization): Tìm ra tỷ lệ phân bổ vốn vào các tài sản sao cho lợi nhuận cao nhất với mức rủi ro thấp nhất.


<a name="-tai-sao-quantitative-finance-lai-hap-dan"></a>

#### Tại sao Quantitative Finance lại hấp dẫn?

- Mức thu nhập đột phá: Đây là một trong những ngành có mức lương và thưởng cao nhất trong giới tài chính toàn cầu.

- Môi trường trí tuệ: Công việc có nhiều thử thách về mặt trí tuệ, bạn cũng có cơ hội làm việc với những người xuất sắc hàng đầu thế giới (nhiều Quants vốn là các tiến sĩ toán học hoặc vật lý). 

- Sự kết hợp giữa lý thuyết và thực tiễn: Những công thức toán học khô khan sẽ được áp dụng trực tiếp để tạo ra lợi nhuận trên thị trường tài chính thực tế.


<a name="-thach-thuc-cua-nganh"></a>

#### Thách thức của ngành

Trong Quantitative Finance, chúng ta thường nhắc đến khái niệm [Black Swan](https://en.wikipedia.org/wiki/The_Black_Swan:_The_Impact_of_the_Highly_Improbable) của [Nassim Taleb](https://en.wikipedia.org/wiki/Nassim_Nicholas_Taleb). Đó là những sự kiện cực kỳ hiếm gặp, không thể dự báo nhưng lại gây ra hậu quả thảm khốc. Thách thức lớn nhất không phải là giải phương trình, mà là biết khi nào nên dừng sử dụng mô hình đó khi thị trường thay đổi bản chất.

Mô hình tài chính giống như một bản đồ. Bản đồ giúp bạn đi đúng hướng trong 99% thời gian, nhưng nó không thể vẽ ra một cơn động đất bất ngờ làm thay đổi hoàn toàn địa hình. Sự sụp đổ của quỹ [Long-Term Capital Management](https://en.wikipedia.org/wiki/Long-Term_Capital_Management) năm 1998 — nơi hội tụ của những bộ óc vĩ đại nhất giới tài chính và cả những chủ nhân giải Nobel — là bài học đắt giá nhất: *"Khi tất cả các biến số toán học đều đúng, nhưng tâm lý con người và sự hoảng loạn của thị trường lại đi theo hướng ngược lại, đó là lúc bản năng của người làm Quant được thử thách."*


<a name="-muc-dich-cua-blog"></a>

## 2. Mục đích của Blog

Quantitative Finance là một ngành rất “ngách”. Ngược dòng thời gian về thập niên 60-70 của thế kỷ XX, lĩnh vực này thậm chí còn chưa có một tên gọi chính thức hay giáo trình giảng dạy bài bản. Đó từng là thứ kiến thức mà các chuyên gia phải vừa làm vừa học tại các ngân hàng đầu tư.

Ngày nay, dù đã trở thành một ngành khoa học danh tiếng được đào tạo tại các trường đại học hàng đầu thế giới, nhưng tại Việt Nam, cánh cửa bước vào thế giới này vẫn còn khá hạn chế. Bản thân tôi, khi còn học đại học tại Việt Nam, mặc dù học chuyên ngành tài chính ngân hàng cũng chưa từng có khái niệm gì về Quantitative Finance.

Sau một thời gian học tập và làm việc ở nước ngoài, tôi nhận ra rằng: Toán học và Lập trình không chỉ là công cụ, mà là "ngôn ngữ" mới để đọc hiểu thị trường. Tôi mong muốn blog này sẽ là nơi hệ thống lại kiến thức của mình cũng như chia sẻ về Quantitative Finance tới nhiều bạn đọc Việt Nam. Tôi sẽ cố gắng đi từ những khái niệm cơ bản nhất tới những mô hình phức tạp kèm theo các ví dụ và mã nguồn (source code) để các bạn có thể thực hành ngay lập tức. Tôi cũng mong muốn nhận được phản hồi của bạn đọc, để thông qua những thảo luận tôi và các bạn có thể hiểu hơn về Quantitative Finance.

**Credit:** Blog được xây dựng dựa trên source code [machinelearningcoban.com](https://github.com/tiepvupsu/tiepvupsu.github.io/) của bạn Vũ Hữu Tiệp. Chân thành cảm ơn bạn Vũ Hữu Tiệp! 