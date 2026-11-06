# đánh giá greencloudvps: giá từng gói KVM từ 6 USD/tháng, ưu nhược điểm thật và những điều khoản trong ToS dễ khiến bạn mất tiền

GreenCloudVPS là một nhà cung cấp VPS giá rẻ hoạt động từ tháng 10/2013, từng được cộng đồng LowEndTalk bình chọn là Top Provider năm 2021, mạnh nhất ở phân khúc KVM cấu hình cao giá thấp — gói Ryzen KVM bắt đầu từ 6 USD/tháng, còn dòng Budget KVM từng có gói 2GB RAM chỉ 15 USD/năm. Nhưng bên dưới mức giá đó là một chính sách hoàn tiền khá chặt, vài khoản phụ phí ít ai nhắc đến, và một lịch sử thanh toán không phải lúc nào cũng suôn sẻ. Bài đánh giá greencloudvps này đi qua từng dòng sản phẩm đang bán, giá chính thức, và những điều khoản nằm trong Terms of Service mà hầu hết bài giới thiệu bỏ qua.

> **Chọn nhanh:** cần VPS Linux chạy web, bot, proxy cá nhân thì gói **RyzenKVM-1** (1 nhân / 1GB RAM / 15GB NVMe, 6 USD/tháng) hoặc **RyzenKVM-2** (2GB RAM, 10 USD/tháng) là điểm khởi đầu hợp lý. Muốn cấu hình cao nhất tính theo tiền thì dòng Budget KVM trả theo năm rẻ hơn nhiều lần, đổi lại không hoàn tiền. Người ở Trung Quốc đại lục hoặc cần đường truyền ổn định về Trung Quốc: đọc kỹ phần rủi ro về IP bên dưới trước khi chọn gói châu Á.
> 👉 [Xem giá hiện tại các gói KVM của GreenCloudVPS](https://greencloudvps.com/billing/aff.php?aff=6679)

## GreenCloudVPS là nhà cung cấp nào, có đáng tin không?

GreenCloudVPS do một người Việt sáng lập năm 2013, hiện vận hành dưới pháp nhân 365 Group LLC đăng ký tại Mỹ, với hơn 30 datacenter trải từ Mỹ, Canada, châu Âu đến Nhật, Singapore, Hong Kong, Úc và Việt Nam. Họ không tự xây hạ tầng mà thuê chỗ tại các đối tác — điểm này giải thích phần lớn cả ưu lẫn nhược điểm của họ.

Về uy tín, dữ liệu hai bên khá phân biệt. Mặt tích cực: năm 2021 LowEndTalk (diễn đàn lớn về VPS giá rẻ) bình chọn GreenCloud vào danh sách Top Provider, và trang sản phẩm chính thức của họ vẫn treo hai danh hiệu "#1 Top Provider Award" và "#1 Most Stable Provider on LowEndTalk". Một reviewer Việt Nam (blog thuanbui.me) đã dùng 2 VPS của họ từ 2021, thậm chí chuyển cả blog cá nhân sang VPS San Jose của GreenCloud từ 2023. Trên Trustpilot cũng có đánh giá khen rõ ràng: "the performance of the vps is great... the price to performance ratio is insane".

Mặt khác, các đánh giá gần đây trên Trustpilot nghiêng về tiêu cực, tập trung vào mấy nhóm: lỗi thanh toán trong đợt sale, hoàn tiền khó, và tài khoản bị đóng đột ngột. Phần rủi ro ở dưới sẽ nói chi tiết. Kết luận ngắn: đây là nhà cung cấp thật, phục vụ khách hàng thật suốt hơn 10 năm, nhưng bạn cần mua đúng cách để tự bảo vệ mình.

## Bảng giá Ryzen KVM VPS — dòng chủ lực

Ryzen KVM là dòng được GreenCloud đẩy mạnh nhất: CPU Ryzen xung nhịp từ 3.5GHz, ổ NVMe, cổng 10Gbps, chỉ hỗ trợ Linux, hỗ trợ kỹ thuật 24/7. Giá lấy trực tiếp từ trang sản phẩm chính thức. Chi tiết đáng chú ý mà bảng không nói ra: cùng một mức giá, gói đặt tại Mỹ/châu Âu được **gấp đôi băng thông** so với gói đặt tại châu Á (Singapore, Nhật, Hong Kong, Việt Nam).

| Gói | CPU / RAM | Ổ NVMe | Băng thông APAC / Mỹ–EU | Giá | Đặt mua |
| --- | --- | --- | --- | --- | --- |
| RyzenKVM-1 | 1 nhân / 1GB | 15GB | 750GB / 1.5TB | 6 USD/tháng | [ Đặt gói RyzenKVM-1](https://greencloudvps.com/billing/aff.php?aff=6679) |
| RyzenKVM-2 | 1 nhân / 2GB | 30GB | 1TB / 2TB | 10 USD/tháng | [ Đặt gói RyzenKVM-2](https://greencloudvps.com/billing/aff.php?aff=6679) |
| RyzenKVM-3 | 2 nhân / 4GB | 50GB | 2TB / 4TB | 20 USD/tháng | [ Đặt gói RyzenKVM-3](https://greencloudvps.com/billing/aff.php?aff=6679) |
| RyzenKVM-4 | 4 nhân / 8GB | 80GB | 4TB / 8TB | 40 USD/tháng | [ Đặt gói RyzenKVM-4](https://greencloudvps.com/billing/aff.php?aff=6679) |
| RyzenKVM-5 | 8 nhân / 16GB | 150GB | 6TB / 12TB | 80 USD/tháng | [ Đặt gói RyzenKVM-5](https://greencloudvps.com/billing/aff.php?aff=6679) |

Mỗi gói có 1 IPv4 kèm IPv6. Nếu thiếu tài nguyên, bạn có thể nâng cấp trả thêm: 3 USD cho mỗi 1GB RAM, 1 nhân CPU hoặc 10GB SSD mỗi tháng. Nhưng có một trần rất ít người biết: **mỗi tài nguyên chỉ nâng được tối đa gấp đôi cấu hình gốc**. VPS 4GB RAM chỉ thêm được tối đa 4GB nữa, dù bạn sẵn sàng trả tiền. Ai dự định dùng lâu dài nên chọn gói cao hơn ngay từ đầu thay vì mua gói nhỏ rồi nâng.

## Các dòng sản phẩm còn lại đang bán

### Budget KVM — rẻ nhất hệ thống, trả theo năm, không hoàn tiền

Đây là dòng giá rẻ nhất của GreenCloud, và cũng là dòng có ít dữ liệu công khai nhất. Trang bán chính thức (Budget KVM Sale) hiện chia hai hạng cấu hình: hạng 4GB RAM / 35GB ổ RAID-10 / 2 nhân / 4TB băng thông, và hạng 8GB RAM / 60GB / 4 nhân / 8TB. Mỗi gói kèm 1 backup/snapshot miễn phí, dùng panel VirtFusion, chỉ chạy Linux. Trang bán **không hiển thị giá cụ thể** và mỗi gói đều ghi rõ "No refund/Money back on this plan" — mua là không đổi ý được.

Về giá tham khảo: theo dữ liệu được ghi nhận tháng 8/2025, dòng này từng có gói BudgetKVMNYC-10 (1 nhân / 2GB RAM / 20GB NVMe / 2TB băng thông) giá **15 USD/năm** — quy ra khoảng 1,25 USD/tháng, trong khi gói RyzenKVM-2 cùng 2GB RAM giá 120 USD/năm. Chênh lệch gần 8 lần cho cùng lượng RAM là lý do dòng này được săn lùng, dù kho hàng thưa thớt.

Tồn kho (số liệu tại thời điểm tra cứu, luôn thay đổi): gần như toàn bộ node cấu hình mới (EPYC Rome/Milan + NVMe ở New York, Virginia, Utah, Phoenix, Los Angeles, Toronto, Amsterdam) đã hết hàng. Còn hàng chỉ có Chicago DC2, Jacksonville và Kansas City — đều là CPU Intel E5v4 đời cũ hơn kèm ổ SATA SSD. Một chi tiết nhỏ nhưng có thể quan trọng với một số người: node Kansas City chỉ cấp dải IPv6 /112, trong khi mọi node khác cấp /64. Nếu bạn cần dải IPv6 đầy đủ, kiểm tra kỹ node trước khi đặt.

👉 [Kiểm tra tồn kho và giá Budget KVM hiện tại](https://greencloudvps.com/billing/aff.php?aff=6679)

### EPYC Cloud Resource — dòng có node tại Việt Nam

Gói 4 nhân EPYC / 8GB RAM / 80GB NVMe Gen4 RAID-10 / 3TB băng thông / cổng 10Gbps giá **20 USD/tháng**, có mặt tại Singapore, Tokyo, **Hà Nội**, Hong Kong và Sydney. Hạng cao hơn: 8 nhân / 16GB giá 40 USD, 16 nhân / 32GB giá 80 USD. Cùng cấu hình đặt tại Mỹ/châu Âu thì được 8TB băng thông thay vì 3TB, vẫn 20 USD/tháng. VPS đặt tại Việt Nam ở mức giá này rất hiếm, nên dòng này đáng để bạn xem kỹ:

👉 [Xem gói APAC Cloud Resource 20 USD/tháng](https://greencloudvps.com/billing/aff.php?aff=6679)

### CN Premium Optimized — tối ưu đường truyền về Trung Quốc

Dòng này dùng tuyến CN2 GIA / CU Premium / CMIN2, đặt tại Tokyo và Singapore, hướng tới người cần đường ổn định về Trung Quốc đại lục. Bốn hạng đang bán (giá theo dữ liệu được ghi nhận từ nhà phân phối):

| Gói | CPU / RAM | Ổ | Băng thông / Cổng | Giá |
| --- | --- | --- | --- | --- |
| CN Premium Mini (Tokyo) | 1 nhân / 2GB | 20GB | 500GB / 500Mbps | 25 USD/tháng |
| CN Premium Plan 1 | 2 nhân / 4GB | 40GB | 1TB / 1Gbps | 45 USD/tháng |
| CN Premium Plan 2 | 4 nhân / 8GB | 80GB | 2TB / 1.5Gbps | 85 USD/tháng |
| CN Premium Plan 3 | 8 nhân / 16GB | 160GB | 4TB / 2Gbps | 165 USD/tháng |

Dòng này cũng là nơi từng có tranh cãi nhiều nhất trên Trustpilot — xem phần rủi ro bên dưới trước khi quyết định.

### EPYC VDS và Storage KVM

EPYC VDS là dòng duy nhất có **nhân CPU dedicated**: gói 1 nhân EPYC Milan riêng / 8GB RAM / 80GB NVMe / 4TB băng thông giá 10 USD/tháng, gói 2 nhân riêng / 16GB / 160GB giá 20 USD/tháng. Nếu workload của bạn cần CPU đều đặn (database, build, render), dedicated core đáng giá hơn nhiều so với nhân chia sẻ cùng mức giá.

Storage KVM Sale dành cho ai cần ổ lớn: hệ thống chạy NVMe 20–60GB, dữ liệu SATA RAID-10 từ 500GB đến 2TB, RAM 2–6GB, cổng 10Gbps, đặt tại Tokyo, Singapore và vài địa điểm ở Mỹ. CPU thay đổi theo node: Tokyo và Singapore dùng Xeon E5v4, các node Mỹ dùng EPYC Milan, Chicago dùng Xeon Gold. Tất cả gói thuộc đợt sale này đều không hoàn tiền, nhiều hạng đã hết hàng tại thời điểm tra cứu, nên mang tính thời hạn. Dòng Windows VPS và macOS VPS cũng có bán nhưng cần xem giá trực tiếp trên trang của hãng.

## Chính sách hoàn tiền: đọc kỹ phần này trước khi thanh toán

GreenCloud **có** chính sách hoàn tiền, nhưng chỉ áp dụng trong một phạm vi hẹp mà nhiều người không biết. Theo Terms of Service chính thức: chỉ khách hàng mới, chỉ gói VPS đầu tiên, chỉ trong **7 ngày** đầu. Từ đó trở ra, gần như mọi thứ đều nằm ngoài diện hoàn tiền:

- Thanh toán bằng **tiền mã hóa** không hoàn tiền dưới bất kỳ hình thức nào
- **Gói khuyến mãi (promotional plans)** không hoàn tiền — bao gồm toàn bộ Budget KVM Sale, Storage KVM Sale và các flash sale
- Đã dùng **từ 10% băng thông trở lên** thì mất quyền hoàn tiền
- Máy chủ riêng (dedicated), dịch vụ nâng cấp, dịch vụ add-on như cPanel hay DirectAdmin đều không hoàn tiền
- Nếu bạn tự mình发起 PayPal/信用卡争议 — dịch sẽ lập tức bị chấm dứt, chỉ có: nếu bạn tự mở tranh chấp PayPal hoặc chargeback thẻ, **toàn bộ dịch vụ sẽ bị dừng hoặc chấm dứt ngay lập tức**

Một chi tiết hay bị bỏ qua: GreenCloud không tự động hủy đăng ký thanh toán định kỳ của bạn. Điều khoản yêu cầu khách tự hủy tất cả subscription PayPal/thẻ tín dụng trong khu vực khách hàng, nếu không kỳ kế tiếp sẽ bị trừ tiền tiếp; phần tiền thừa do trùng subscription được ghi vào số dư tài khoản, không hoàn lại bằng cash.

## Phụ phí và giới hạn: nằm trong điều khoản, nhưng ảnh hưởng trực tiếp đến ví

Đây là phần ít bài giới thiệu nào đề cập, dù nó quyết định chi phí thật khi dùng lâu:

- **Vượt băng thông**: với gói KVM, phần vượt tại Mỹ/châu Âu tính 3 USD/TB/tháng, tại **châu Á tính 15 USD/TB/tháng**. Cùng vượt 1TB nhưng ở node châu Á đắt gấp 5 lần. Nếu bạn dự đoán dùng quá hạn mức, đây là khoản phải tính vào tổng chi phí trước khi chọn node.
- **Đổi IP**: 2 USD/IP tại mọi datacenter. Điều khoản ghi rõ khả năng truy cập tới "một số website cụ thể (Netflix, Etsy...)" không được đảm bảo.
- **IP bị chặn bởi GFW**: khách hàng Trung Quốc phát hiện IP bị chặn trong **3 giờ** đầu sau khi giao máy được đổi miễn phí một lần; qua cửa sổ này thì mất 2 USD. Ba giờ là khoảng thời gian rất ngắn — nếu bạn mua node châu Á để dùng từ Trung Quốc, hãy kiểm tra IP ngay khi nhận máy.
- **Đổi datacenter**: gói thường 3 USD/lần; gói khuyến mãi 10 USD/lần, và khu vực APAC chỉ cho đổi trong cùng một quốc gia (ví dụ SGDC1 ↔ SGDC2), còn Mỹ/châu Âu được đổi giữa bất kỳ node nào trong vùng. Flash sale chỉ được đổi sau khi hoạt động tối thiểu 1 tháng; gói flash mua bằng mã giảm giá thì không được đổi node.
- **Chuyển dịch vụ và chuyển tài khoản**: đây là hai chính sách khác nhau. Chuyển dịch vụ VPS: lần đầu miễn phí, sau đó 10 USD/VPS. Chuyển tài khoản (push) cho người khác: mỗi tài khoản 1 lần miễn phí, sau đó 10 USD/lần. Riêng gói flash sale không được push, không được đổi email, không được bán lại tài khoản — vi phạm bị khóa tài khoản, xóa máy, không hoàn tiền.
- **Hóa đơn quá hạn**: quá hạn 2 ngày bị tính thêm 10% phí trễ; quá hạn 1 ngày hãng đã có thể tạm dừng dịch vụ, quá 3 ngày có thể chấm dứt hẳn.
- **Khôi phục VPS đã hủy (không thuộc diện hoàn tiền)**: mất 5 USD phí dựng lại.
- Đổi tuyến SoftBank ↔ IIJ tại datacenter Tokyo mất 10 USD, IP sẽ thay đổi và bạn phải tự backup trước.

## Rủi ro và phản hồi tiêu cực: người dùng thực tế gặp gì?

Trên Trustpilot, các đánh giá tiêu cực gần đây của GreenCloudVPS lặp lại thành vài nhóm rõ ràng, đều đáng biết trước khi xuống tiền.

**Lỗi thanh toán tập trung vào các đợt khuyến mãi.** Một đánh giá đăng tháng 3/2025 mô tả: trong một đợt khuyến mãi của hãng, khách đặt hàng xong thì trang không có tùy chọn PayPal, chuyển sang thẻ tín dụng thì báo lỗi; ticket xử lý khoảng 30 phút rồi bị đóng luôn, và theo lời người này, tài khoản cũng bị khóa sau đó. Đánh giá khác (tháng 7) cho biết Google Pay và Link đều lỗi, buộc phải chọn ACH — mà ACH cần khoảng 5 ngày làm việc mới ghi nhận tiền và kích hoạt máy, không hề được cảnh báo trước. Bài học thực tế: vào mùa sale, cổng thanh toán không phải lúc nào cũng hoạt động; gặp lỗi thì dừng lại, đừng đặt đơn lặp lại.

**Vấn đề IP và tuyến truyền.** Một người dùng phản ánh sau khi gia hạn VPS Nhật, truy cập từ Trung Quốc đại lục bị mất hoàn toàn: TCP 443, 2053, 2087 đều không kết nối được. Bộ phận hỗ trợ trước khuyên đổi cổng, sau thừa nhận nghi ngờ cả dải IP bị GFW chặn và đề nghị chờ vài tuần. Đây chính là lý do điều khoản "3 giờ đổi IP miễn phí" tồn tại — nhưng cửa sổ 3 giờ quá ngắn để nhiều người kịp phát hiện.

**Độ ổn định và hỗ trợ.** Trong cộng đồng tiếng Trung, người dùng lâu năm tổng hợp: node Nhật quá tải nặng vào giờ cao điểm tối, tuyến lúc tốt lúc xấu; từng có máy tự tắt khi tải cao, mất kết nối đột ngột và chỉ có thể mở ticket; hãng không cam kết tuyến truyền, đường đi có thể tự động thay đổi. Chất lượng hỗ trợ cũng không đồng đều — ticket thường được trả lời trong khoảng 15 phút đến 1 giờ, nhưng một số phản hồi bị nhận xét là thái độ kém. Trustpilot cũng có các phản ánh đơn phương về tài khoản bị đóng đột ngột kèm dữ liệu không lấy lại được.

Giảm rủi ro xuống mức thấp nhất, từng bước đều có căn cứ: thanh toán bằng **PayPal** để còn đường kiện nếu sót (nhưng nhớ rằng tự mở tranh chấp đồng nghĩa mất toàn bộ dịch vụ — kiện là nước cuối cùng); **chu kỳ thanh toán không nên vượt quá một năm**, bởi hãng có lịch sử tung gói mới tốt hơn làm lu mờ gói cũ mà người dùng gọi là "backstab" (chuỗi 9999 → 1010 → 1111 → 1212 là minh họa điển hình); **backup luôn đặt ngoài VPS**; người dùng Trung Quốc **kiểm tra IP trong 3 giờ đầu** sau khi nhận máy.

## 适合谁、不适合谁

Nói thẳng, có mấy nhóm người không cần đến nhà cung cấp này. Nếu workload của bạn nằm hoàn toàn ở châu Âu và Mỹ, các hãng chủ lực ở hai vùng này như Hetzner, netcup, Contabo hay RackNerd cũng rẻ không kém, và lượng đánh giá Trustpilot của họ lớn hơn nhiều (Hostinger 74K đánh giá, Contabo 12K, so với lượng đánh giá rất nhỏ của GreenCloud) — tức là bạn có nhiều dữ liệu tham khảo hơn khi quyết định. Còn nếu bạn cần dịch vụ quản lý trọn gói (managed) hoặc cam kết SLA về tuyến truyền, GreenCloud càng không phù hợp: đây là dịch vụ unmanaged, điều khoản ghi rõ họ chỉ chịu trách nhiệm phần cứng, còn sự cố do cấu hình phần mềm hay downtime do người dùng tự cấu hình sai đều ngoài phạm vi trách nhiệm.

GreenCloud thật sự có giá trị ở mật độ node châu Á: Singapore, Tokyo, Hong Kong, Sydney, thậm chí Hà Nội, chạy trên EPYC/NVMe với cổng 10Gbps, ở mức giá này gần như không có đối trọng trực tiếp. Nhu cầu của bạn rơi vào khu vực châu Á, nó mới có ý nghĩa.

## Câu hỏi thường gặp

**GreenCloudVPS có hoàn tiền không?** Khách hàng mới, gói VPS đầu tiên, trong 7 ngày đầu, không dùng quá 10% băng thông, không trả bằng crypto, không phải gói khuyến mãi — đủ cả các điều kiện đó mới được hoàn. Gói khuyến mãi thì hoàn toàn không hoàn.

**Có thanh toán được từ Việt Nam không?** Có — Alipay, PayPal, thẻ tín dụng và tiền mã hóa đều được chấp nhận. PayPal là lựa chọn an toàn nhất nếu xảy ra tranh chấp.

**IP bị chặn thì xử lý sao?** Đổi IP tốn 2 USD; khách Trung Quốc được đổi miễn phí 1 lần nếu phát hiện trong 3 giờ đầu. GreenCloud không hoàn tiền vì vấn đề khả năng truy cập tuyến.

**GreenCloudVPS có phải lừa đảo không?** Không. Họ hoạt động từ 2013, có sự ủng hộ từ cộng đồng LowEndTalk và nhiều người dùng lâu năm hài lòng. Vấn đề nằm ở chính sách bảo vệ người mua khá chặt chẽ và việc hỗ trợ chưa ổn định, chứ không phải lừa đảo.

**Chạy được Windows không?** Có dòng Windows NVMe VPS riêng; còn Ryzen KVM và Budget KVM chỉ hỗ trợ Linux.

## Trước khi bấm nút thanh toán

Chọn theo nhu cầu: chỉ chạy website cá nhân, ít traffic → RyzenKVM-1 (6 USD/tháng) là đủ; muốn tiết kiệm tối đa và chấp nhận không hoàn tiền → săn Budget KVM theo năm; cần node châu Á làm landing hay proxy cá nhân → RyzenKVM đặt tại Singapore hoặc Hong Kong; CPU cần chạy liên tục và nặng → chọn thẳng EPYC VDS dedicated core, đừng cố tiết kiệm trên nhân chia sẻ; cần tuyến tối ưu về Trung Quốc đại lục → CN Premium, nhưng hãy chuẩn bị tinh thần với rủi ro IP đã nói ở trên. Kiểm tra ba điều trước khi thanh toán: gói bạn chọn có thuộc diện không hoàn tiền không (đa số deal rẻ đều thuộc nhóm này), chu kỳ thanh toán có vượt quá một năm không, và bạn đã chuẩn bị PayPal làm phương án dự phòng chưa. Xong ba việc đó thì [👉 đặt mua GreenCloudVPS tại đây](https://greencloudvps.com/billing/aff.php?aff=6679).
