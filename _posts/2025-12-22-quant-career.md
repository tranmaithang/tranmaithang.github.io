---
layout: post
comments: true
title: "Bài 2: Chuyện nghề Quant"
title2: "2. Chuyện nghề Quant"
date: 2025-12-22 12:00:00
permalink: 2025/12/22/quant-career/
mathjax: true
tags: General Career
category: General
sc_project: 13194351
sc_security: ccb0f745
img: /assets/posts/2_quantcareer/2_gemini_cover.png
summary: Liệu chúng ta đang làm khoa học thực sự hay chỉ đang cố áp đặt những công thức khô khan lên hành vi phức tạp của con người để chạy theo lợi nhuận trần tục?
---

Trong bài viết trước, chúng ta đã cùng tìm hiểu về khái niệm và những trụ cột nền tảng của Quantitative Finance. Tuy nhiên, một câu hỏi lớn thường đặt ra cho bất kỳ ai muốn dấn thân vào con đường này là: *"Với những kiến thức về toán và lập trình đó, tôi sẽ làm gì hàng ngày trong một tổ chức tài chính?"*

Trong bài viết này, tôi sẽ cùng bạn đi sâu vào tìm hiểu 4 vị trí chủ chốt trong "nghề Quant": **Quant Analyst**, **Quant Developer**, **Quant Trader/Researcher** và **Quant Risk**. Hiểu rõ sự khác biệt này sẽ giúp bạn định hình lộ trình học tập và phát triển bản thân một cách chính xác nhất.


**Trong trang này:**
- [1. Bối cảnh lịch sử: Tại sao Quant quan trọng hơn bao giờ hết?](#-boi-canh-lich-su-tai-sao-quant-lai-quan-trong-hon-bao-gio-het")
    - [Quant Analyst](#-quant-analyst)
    - [Quant Developer](#-quant-developer)
    - [Quant Trader/Researcher](#-quant-trader-researcher)
    - [Quant Risk](#-quant-risk)
- [2. Nghề Quant - Lựa chọn nào dành cho bạn?](#-nghe-quant-lua-chon-nao-cho-ban)
- [3. Từ những "nhà vật lý lạc lối" đến kiến trúc sư của tài chính hiện đại](#-tu-nhung-nha-vat-ly-lac-loi-den-kien-truc-su-cua-tai-chinh-hien-dai)


<a name="-boi-canh-lich-su-tai-sao-quant-lai-quan-trong-hon-bao-gio-het"></a>

## 1. Bối cảnh lịch sử: Tại sao Quant quan trọng hơn bao giờ hết?

> *"Thực tế, tôi rất lạc quan về tương lai của ngành Quant. Ngành công nghiệp này đang trở nên kỹ thuật hơn bao giờ hết, và nhu cầu thấu hiểu các rủi ro trong hệ thống cũng đang ở mức cao nhất từ trước đến nay."* – [Robert C. Merton](https://en.wikipedia.org/wiki/Robert_C._Merton), Nobel Kinh tế, trích dẫn trên tạp chí "Risk", 2012.

Vào năm 1997, khi Robert Merton giành giải Nobel cho công trình nghiên cứu về công thức định giá quyền chọn **Black-Scholes**, nhu cầu của ngành tài chính về nhân lực có kỹ năng toán học và lập trình đã bùng nổ. Thời điểm đó, các Ngân hàng đầu tư liên tục tạo ra và tiếp thị các loại chứng khoán phái sinh phức tạp (Exotic Derivatives), và các "Quant" được thuê để định giá (pricing) cũng như phòng hộ (hedging) cho chúng. Sau cuộc khủng hoảng tài chính 2008, [đạo luật Dodd-Frank](https://en.wikipedia.org/wiki/Dodd%E2%80%93Frank_Wall_Street_Reform_and_Consumer_Protection_Act) về cơ bản đã hạn chế mảng kinh doanh phái sinh phức tạp này. Nhiều người cho rằng kỷ nguyên của Quant đã chấm dứt, nhưng thực tế hoàn toàn ngược lại.

Để hiểu được sự lạc quan của Merton, trước tiên chúng ta phải hiểu thế giới đã thay đổi sâu sắc trong 20 năm qua:
* **Sự trỗi dậy của Quản lý tài sản định lượng:** Hiện nay có hàng trăm quỹ phòng hộ (Hedge Funds) vận hành hoàn toàn dựa trên các phương pháp định lượng.
* **Sự thay đổi của Sàn giao dịch:** Năm 1997, chênh lệch giá mua-bán (bid-ask spread) trên Sàn giao dịch chứng khoán New York (NYSE) là 1/8 đô la. Những chuyên gia bỏ ra 4 triệu đô la để có một "chỗ ngồi" trên NYSE có thể thu lợi từ mức chênh lệch đó trên hàng triệu cổ phiếu giao dịch mỗi ngày. Đến năm 2001, những vị trí đó đã mất 75% giá trị. Ngày nay, hầu hết mọi giao dịch trên NYSE và các nơi khác đều được thực hiện bởi những dàn máy tính hoạt động thầm lặng của các nhà giao dịch tần suất cao (High-Frequency Trading).
* **Vị thế của Quản trị rủi ro:** Trước đây, các khuyến nghị của nhà quản trị rủi ro tại ngân hàng thường không được các trader hoặc cấp quản lý coi trọng. Giờ đây, các ngân hàng đều có Giám đốc rủi ro (CRO) – người ngồi trong ban điều hành và có quyền bác bỏ quyết định của cả những trader thành công nhất để bảo vệ hệ thống.
* **Định giá Rủi ro đối tác**: Cho đến trước vụ phá sản của Lehman Brothers năm 2008, các ngân hàng lớn vẫn mặc định rằng rủi ro vỡ nợ khi cho nhau vay là không đáng kể. Ngày nay, có những đội ngũ khổng lồ trong các ngân hàng này chỉ để đo lường và định giá rủi ro vỡ nợ của đối tác (Counterparty Credit Risk). Các phép toán dùng để định giá chứng khoán phái sinh phức tạp ngày xưa vẫn còn quá đơn giản so với thách thức trong việc xác định giá và chiến lược phòng hộ cho rủi ro đối tác trong một giao dịch cơ bản nhất hiện nay.

Trong môi trường mới này, nghề Quant không mất đi mà phân hóa thành những vai trò chuyên biệt hơn. Tôi sẽ cùng bạn bóc tách 4 vị trí quan trọng nhất trong thế giới tài chính định lượng hiện đại. Các vị trí bao gồm:


| Role | Primary Focus | Core Skills | Tech Stack | Environment |
| :--- | :--- | :--- | :--- | :--- |
| **Quant Analyst** | Pricing & Validation | Stochastic Calculus | `C++`, `VBA`, `Python` | Investment Banks |
| **Quant Developer** | Infrastructure & Speed | Data Structures / Algo | `C++`, `Java`, `Rust` | HFT Firms, Investment Banks |
| **Quant Trader** | Alpha Generation | Statistics, Machine Learning | `Python`, `R`, `KDB+` | Hedge Funds, Prop Trading |
| **Quant Risk** | Risk Mitigation | Advanced Statistics | `SQL`, `Python`, `SAS` | Risk Dept, Central Banks |

<figure style="margin: 10px 0;">
<figcaption style="text-align: center; font-style: italic; font-size: 0.95em; margin-top: 10px; color: #666;">
    Bảng 1: Tổng quan về các vị trí Quant trong lĩnh vực Tài chính định lượng.
</figcaption>
</figure>


<a name="-quant-analyst"></a>

#### Quant Analyst

Còn được gọi là Kỹ sư tài chính (Financial Engineer). Đây là khái niệm truyền thống nhất về một "Quant". Các Quant này được thuê để định giá các chứng khoán phái sinh (Derivatives Pricing). Vai trò này cực kỳ phổ biến trong những Ngân hàng đầu tư lớn. 

Các kỹ năng cần thiết bao gồm: Giải tích ngẫu nhiên (Stochastic Calculus), Phương trình vi phân riêng phần (Partial Differential Equation - PDEs) và lập trình bằng các ngôn ngữ kiểu tĩnh như C++, C# hoặc Java. 

Một vị trí khác mới nổi lên vài năm qua là "Model Validation" Quant – tập trung vào việc kiểm chứng tính hợp lệ của các mô hình thay vì trực tiếp phát triển chúng như Quant Analyst.

<a name="-quant-developer"></a>

#### Quant Developer

Vai trò này rất đa dạng và đôi khi các nhà tuyển dụng dùng từ "Quant" kèm theo để làm đẹp cho các vị trí IT truyền thống vốn ít công việc định lượng. Một Quant Dev thực thụ thường làm việc ở vị trí cấp cao tại bộ phận Middle Office hoặc Front Office (nơi trực tiếp tạo ra lợi nhuận) của các Ngân hàng đầu tư (Sell-side) cũng như tại các Quỹ quản lý tài sản (Buy-side). Quant Dev xây dựng cơ sở hạ tầng giao dịch, thiết kế công cụ phân tích/báo cáo hoặc tối ưu hóa tốc độ thực thi cho các mô hình định lượng mẫu. 

Các kỹ năng cần thiết bao gồm: Kiến trúc phần mềm, Khoa học máy tính hoặc Toán học với kỹ năng Lập trình xuất sắc (C, C++, C#, Java, Python, Julia, Go, Haskell).

<a name="-quant-trader-researcher"></a>

#### Quant Trader/Researcher

Đây thường là vị trí với mức thu nhập cao nhất ngành "Quant". Lý do chủ yếu là vì mức thu nhập thường gắn liền trực tiếp với hiệu quả giao dịch (PnL). Vị trí này có sự linh hoạt và tính học thuật cao nhờ bản chất nghiên cứu. 

Kỹ năng cần thiết gắn liền với các mô hình tạo ra lợi nhuận: Thống kê (Statistics), Phân tích kỹ thuật (Technical Analysis) và gần đây là Machine Learning cùng thống kê Bayesian. Bằng Tiến sĩ (PhD) và thành tích xuất bản học thuật thường là điều kiện tiên quyết cho các vị trí hàng đầu. 

Trong nhóm này còn có High Frequency Trader (Giao dịch viên tần suất cao) – những người giỏi về kỹ thuật hệ thống cấp thấp, phân tích độ trễ mạng hoặc lập trình phần cứng tối ưu.

<a name="-quant-risk"></a>

#### Quant Risk

Kể từ sau khủng hoảng tài chính 2008, việc quản trị rủi ro ở cấp độ giao dịch, danh mục và toàn doanh nghiệp được chú trọng đặc biệt. Các Quant Risk này đo lường và giảm thiểu rủi ro cho tổ chức. Đây là công việc không hề đơn giản, nhất là tại các công ty có mức độ rủi ro đa tầng (đối tác, phái sinh phức tạp, sai sót mô hình). 

Nền tảng về thống kê cao cấp là cực kỳ quan trọng, thường dành cho những người học Toán hoặc các ngành liên ngành như MORSE (Toán, Nghiên cứu vận hành, Thống kê và Kinh tế).


<a name="-nghe-quant-lua-chon-nao-cho-ban"></a>

## 2. Nghề Quant - Lựa chọn nào dành cho bạn?

Thế giới Quantitative Finance không phải là một "pháo đài" bất khả xâm phạm dành riêng cho những thiên tài toán học. Như chúng ta đã thấy, ngành này có đủ không gian cho những tư duy logic khác nhau: từ những người yêu thích vẻ đẹp nguyên bản của lý thuyết toán học (Analyst/Risk), những "phù thủy" mã nguồn (Developer) cho đến những chiến binh trực tiếp đối đầu với biến động thị trường (Trader/Researcher). Lời khuyên dành cho bạn là: **Đừng cố gắng giỏi tất cả mọi thứ.** Hãy xác định thế mạnh của mình (Toán hay Lập trình) để chọn một điểm xuất phát phù hợp nhất.

Mỗi vị trí đòi hỏi một bộ kỹ năng kỹ thuật hoàn toàn khác nhau.

- Yêu thích sự chính xác của các công thức và định giá phái sinh? Hãy chọn **Financial Engineering**.

- Đam mê xây dựng hệ thống và tối ưu hóa code? **Computer Science** là dành cho bạn.

- Muốn trực tiếp "chiến đấu" với thị trường và tìm kiếm lợi nhuận? Hãy đầu tư sâu vào **Statistics & Machine Learning**.

Chúc bạn tìm thấy cánh cửa riêng cho mình trong thế giới đầy thú vị này!


<a name="-tu-nhung-nha-vat-ly-lac-loi-den-kien-truc-su-cua-tai-chinh-hien-dai"></a>

## 3. Từ những "nhà vật lý lạc lối" đến kiến trúc sư của tài chính hiện đại

Nghề Quant không đơn thuần là một công việc kỹ thuật; nó là một hành trình lịch sử đầy cảm hứng bắt đầu từ những năm 1970-1980, khi những "nhà vật lý lạc lối" rời bỏ học thuật để mang tư duy khoa học vào sự hỗn loạn của Phố Wall. Trong cuốn hồi ký kinh điển “My Life as a Quant”, [Emanuel Derman](https://en.wikipedia.org/wiki/Emanuel_Derman) (người từng giữ chức Head of Quantitative Strategies tại Goldman Sachs) đã mô tả về sự xuất hiện của các nhà khoa học trong tài chính không chỉ để tìm kiếm lợi nhuận, mà để tìm kiếm một "quy luật" trong sự bất định.

Họ đã biến thị trường từ những tiếng la hét trên sàn đấu giá thành những dòng mã lệnh tinh vi, nơi trí tuệ toán học trở thành vũ khí sắc bén nhất. Dù bạn chọn trở thành một Analyst khắt khe, một Developer thần tốc hay một Trader nhạy bén, hãy nhớ rằng bạn đang tiếp nối di sản của những người đã dám dùng định luật của tự nhiên để giải mã hành vi của con người. Nghề Quant không chỉ cần những cái đầu lạnh với các con số, mà còn cần những trái tim nóng khao khát chinh phục những biên giới mới của tri thức. Cánh cửa của thế giới Quantitative Finance luôn rộng mở cho những ai tin rằng: **Đằng sau mỗi biến động của thị trường luôn tồn tại một cấu trúc toán học chờ được khám phá.**

Sau đây là bản dịch chương đầu trong cuốn hồi ký [“My Life as a Quant”, Emanuel Derman](https://download.e-bookshelf.de/download/0000/5845/30/L-G-0000584530-0002384412.pdf) được tôi rút gọn một phần. Tôi hy vọng những dòng hồi ký của một trong những huyền thoại lớn nhất ngành Quant sẽ cho bạn một góc nhìn sâu sắc hơn về nghề này, cũng như cái "tâm" và cái "tầm" của một Quant thực thụ. Liệu chúng ta đang làm khoa học thực sự hay chỉ đang cố áp đặt những công thức khô khan lên hành vi phức tạp của con người để chạy theo lợi nhuận trần tục?

<hr>
<div class="imgcap">
<img src ="/assets/posts/2_quantcareer/2_My-Life-as-a-Quant.png" align = "center" style="width: 80%;">
<div style="text-align: center; font-style: italic; font-size: 0.95em; margin-top: 10px; color: #666;"> Hình 1: My Life As A Quant: Reflections On Physics And Finance, Emanuel Derman</div>
</div>
<hr>

> #### MÔ HÌNH HÓA THẾ GIỚI 
>
> Mục đích thực sự đằng sau việc tìm kiếm các định luật khoa học là gì? Nói thẳng ra, đó chính là **"thuật tiên tri"** – mô tả hiện tượng quan sát được, dự đoán tương lai và kiểm soát nó. Hầu hết các công nghệ hiện đại mà chúng ta đang tận hưởng từ máy tính, điện thoại di động, vũ khí hạt nhân, hay công nghệ vũ trụ đều được phát triển dựa trên các nguyên lý cơ bản của vật lý. Và gần đây, các nhà vật lý đã bắt đầu dùng chính những công cụ đó trong ngành tài chính.
>
> Suốt 20 năm qua, từ Phố Wall đến London, trong những tổ chức tài chính lớn nhỏ, những nhóm cựu nhà vật lý và nhà toán học ứng dụng đã cố gắng đem kỹ năng của mình áp dụng vào thị trường chứng khoán. Trước đây, họ được gọi là **"nhà khoa học tên lửa"** (bởi những người lầm tưởng rằng tên lửa là ngành khoa học tiên tiến nhất), nhưng giờ đây họ thường được gọi là các "Quants" (chuyên gia định lượng).
>
> Các "Quants" thực hành cái gọi là "kỹ thuật tài chính" hay "tài chính định lượng". Môn học này là sự pha trộn liên ngành giữa các mô hình lấy cảm hứng từ vật lý, các kỹ thuật toán học và khoa học máy tính, tất cả đều nhằm mục đích định giá các loại chứng khoán tài chính. Tài chính định lượng **"xịn" nhất** là khi nó đem lại cái nhìn sâu sắc về mối quan hệ giữa giá trị và sự bất định, đạt đến chất lượng của một ngành khoa học thực thụ; còn loại **"tệ" nhất** thì chỉ là một mớ hỗn độn giả khoa học của toán học phức tạp được dùng với những lý lẽ mập mờ.
>
> Cách đây không lâu, kỹ thuật tài chính thậm chí còn chưa được coi là một môn học. Khi tôi bước chân vào ngành này năm 1985, nó còn chẳng có tên gọi và là thứ mà người ta phải vừa làm vừa học tại các ngân hàng đầu tư. Giờ đây, bạn có thể lấy bằng thạc sĩ về ngành này tại hàng loạt trường danh tiếng như NYU, Michigan hay Columbia. 
>
> Một phần lý do cho làn sóng các nhà vật lý đổ xô sang tài chính là sự sụp đổ của thị trường học thuật vào những năm 1970. Thật trùng hợp, khi các nhà vật lý rời bỏ giới học thuật thì Phố Wall lại bắt đầu cần họ. Lệnh cấm vận dầu mỏ năm 1973 khiến thị trường trở nên biến động dữ dội, những quy tắc kinh nghiệm cũ không còn áp dụng được nữa. Quản trị rủi ro và phòng hộ (hedging) trở thành yêu cầu cấp thiết.
>
> Làm sao để hiểu được sự chuyển động của giá cả? Vật lý xưa nay luôn quan tâm đến động lực học – cách vạn vật thay đổi theo thời gian. Và các nhà vật lý, kỹ sư vốn là những "người đa năng" – vừa giỏi toán, vừa biết xây dựng mô hình và lập trình máy tính. Phố Wall bắt đầu vẫy gọi họ. Vào những năm 1980, họ đông đến mức được gọi là các "POWs" – Physics on Wall Street (Những nhà vật lý trên Phố Wall).
>
>
> #### LÝ THUYẾT THÀNH CÔNG NHẤT
>
> Các nhà vật lý làm gì ở Phố Wall? Chủ yếu họ xây dựng mô hình để định giá chứng khoán. Và mô hình nổi tiếng nhất chính là **Black-Scholes (1973)** dùng để định giá quyền chọn. Nhà kinh tế học nổi tiếng Steve Ross từng viết rằng: *"Lý thuyết định giá quyền chọn là lý thuyết thành công nhất không chỉ trong tài chính, mà trong cả kinh tế học."*
>
> Black và Scholes đã chứng minh rằng làm quyền chọn giống như làm món salad trái cây. Nếu bạn biết giá táo và cam, bạn có thể tính ra giá một hộp salad trộn. Tuy nhiên, tỷ lệ trong "món salad tài chính" này phải thay đổi liên tục khi giá cổ phiếu thay đổi. Công thức Black-Scholes chính là "công thức nấu ăn" cho bạn biết chính xác cần bao nhiêu cổ phiếu và bao nhiêu tiền mặt tại mỗi thời điểm.
>
>
> #### ĐỜI CỦA MỘT QUANT
>
> Cuộc sống của một Quant trong thực tế khác xa với một nhà vật lý. Khi tôi mới đến Phố Wall năm 1985, sếp tôi đã nói một câu rất thấm: *"Trong công việc này, cậu thực sự chỉ cần biết bốn phép tính: cộng, trừ, nhân, chia – và phần lớn thời gian cậu chẳng cần đến phép chia đâu!"*
>
> Ông ấy có lý. Trong kinh doanh, một mô hình đơn giản, dễ hiểu thường hữu ích hơn một mô hình phức tạp nhưng khó vận hành. Các trader quan tâm đến giao diện thân thiện và tốc độ xử lý hơn là những sai số nhỏ nhặt.
>
>
> #### KẺ SUY TƯ VS. NGƯỜI HÀNH ĐỘNG
>
> Tôi từng nhận ra từ "Quant" đôi khi mang nghĩa mỉa mai. Vào năm 1985 tại Goldman Sachs, việc tỏ ra giỏi toán đôi khi còn bị coi là... đáng xấu hổ. Nói chuyện về toán học trong thang máy với các trader thường khiến họ khó chịu.
>
> Trader và Quants thực sự là hai loài khác nhau. Trader là những người hành động, quyết đoán, nghĩ nhanh và sống trong thế giới đầy những sự ngắt quãng. Quants thì ngược lại, họ được đào tạo để nghiên cứu sâu, làm một việc từ đầu đến cuối một cách tỉ mỉ.
>
> Quants giống như những **"kẻ vi phạm các quy tắc phân loại"**. Họ sống giữa hai thế giới: một nửa là nhà khoa học, một nửa là người làm tài chính. Tuy nhiên, trong thế kỷ 21, địa vị của Quants đã dần được khẳng định. Khả năng gây ra (hoặc ngăn chặn) sự hủy diệt bằng các mô hình toán học đã mang lại cho họ sự nể trọng cuối cùng.