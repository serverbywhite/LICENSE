# PyMaKaizu License v5.7.1 (Non-Commercial Use)

Các Công cụ có tên sau : **PyShadow**, **PyMaKaizu**, **PyZuma**.

Giấy phép cập nhật ngày 10-10-2025, dùng chung cho các công cụ trên.

## Lời mở đầu

Tài liệu này là Giấy phép Sử dụng Phần mềm **Pyshadow**, **PyMaKaizu**, **PyZuma**. Bằng việc truy cập, tải xuống hoặc sử dụng Công cụ, Người dùng được xem là đã chấp nhận và đồng ý tuân thủ tất cả các điều khoản và điều kiện được nêu rõ dưới đây. **PyMaKaizu** là Chủ sở hữu và giữ toàn bộ quyền sở hữu trí tuệ đối với các Công cụ này.

Những gì chúng tôi làm là mang lại một giải pháp bảo vệ khỏi việc mã nguồn bị tấn công nhằm gây **crack**, **dịch ngược**. Chúng tôi đem lại giải pháp bảo vệ mã nguồn của bạn khỏi các mối đe dọa nguy hiểm không đáng có, tuy nhiên không có giải pháp nào hoàn hảo để giúp cho mã nguồn của bạn tránh nguy cơ bị **'Hack'**, chúng tôi chỉ tăng chi phí và thời gian cho kẻ tấn công nhằm gây khó cho kẻ tấn công. Xin nhắc lại không có giải pháp nào bảo vệ hoàn toàn. Ngoài ra chúng tôi có cơ chế theo dõi hành vi mã của bạn nếu có dấu hiệu **malware**, **keylog**, **v.v** chúng tôi sẽ ngăn chặn ngay lập tức và không tha thứ cho các hành vi này. Không chấp nhận các kháng nghị và từ chối cung cấp dịch vụ bảo vệ.

### Những gì chúng tôi bảo vệ

- Ngăn chặn theo dõi **"mạng"** và các công cụ tùy chỉnh để theo dõi **"mạng"**.
- Ngăn chặn các phần mềm phổ biến như **'httptoolkit'**, **'mitm'**, **'httpproxy'**, **httpdebugging**.
- Ngăn chặn các công cụ dịch ngược động, tĩnh như: **'FRIDA'**, **'DECOMPILE6'**, **'UNCOMPILE3'**, **'GDB'**, **'DEBUGGING'**, v.v.
- Ngăn chặn việc dynamic analysis, static analysis bằng các công cụ tùy chỉnh.
- Theo dõi hành vi môi trường tiến trình mạng, giám sát liên tục để ngăn hook.
- Ngăn **hook** ở các tầng cấp thấp và cấp cao, tuy nhiên nếu bị **hook** ở cấp **OS**, **Kernel** thì chúng tôi không đảm bảo được là ngăn thành công các cấp hook này.
- Ngăn chặn các việc liên quan đến **crack**.
- Ngăn chặn các loại hook như **Audithoook**, **Hook cùng tiến trình**, **Hook trước tiến trình**, tuy nhiên nếu hook tùy chỉnh do người khác viết thì chúng tôi không đảm bảo ngăn được, (Có thể báo cách thức của hook cho chúng tôi đê nâng cấp lên bản chống lại mới hơn).
- Chiếm lại quyền tiến trình để làm sạch môi trường thực thi.
- Ngăn fake chứng chỉ **CA**, **CC**, **SC**, **CSC**, **EC**, **DSC**, **EV**, **OV**, **DV**.


### Chú Ý
1. **Thời Gian Thực Thi Mã**
 - Có thể thời gian thực thi của mã tăng lên đáng kể vì cần xác minh và ký lại khá nhiều thứ nên nếu bạn cần một mã hóa có thời gian thực thi như mã gốc thì điều này chúng tôi không thể đảm bảo với bạn. 
2. **Báo Cáo Vi Phạm**
 - Nếu phát hiện những Công cụ (Tools) được mã hóa bằng Công cụ mã hóa của chúng tôi mà có dấu hiệu **Malware**, **Virus**, **Trojan**, **Keylog**, v,v. Hãy báo ngay cho chúng tôi qua Telegram : junidokai, khi báo kèm theo enc_id để chúng tôi có thể vô hiệu hóa đối với các công cụ gây hại này. Lưu ý nếu có thể hãy chứng minh rằng Công cụ (Tools) đó gây hại để không bị xóa một cách vô cớ đối với các Dev và chỉ những Công cụ mã hóa (**ENC**) mà có tên của chúng tôi thì sẽ được chấp nhận yêu cầu xóa còn các **OBF** thì sẽ không hỗ trợ.
3. **Khẳng Định An Toàn**
 - Cơ chế theo dõi hành vi mã không lấy dữ liệu, mã nguồn của bạn chúng tôi quét mã xem có hành vi nào gửi dữ liệu về server không nếu có coi đó là **keylog**. XIn nhắc lại chúng tôi không thu thập mã nguồn và dữ liệu của bạn.

**0. ĐỊNH NGHĨA**
- “Công cụ”: chỉ chung cho các phần mềm có tên PyShadow, PyMaKaizu, PyZuma.
- “ENC”: file hoặc tool đã được mã hóa bằng công cụ chính chủ.
- “OBF”: các bản obfuscate biến thể do chúng tôi phát hành nhưng không thuộc phạm vi hỗ trợ chính thức.
- “Chủ sở hữu”: nhóm phát triển ban đầu – PyMaKaizu.
- “enc_id”: mã định danh duy nhất được sinh ra từ hệ thống mã hóa chính chủ, dùng để quản lý, xác minh và vô hiệu hóa nếu có vi phạm.

**1. ĐIỀU KHOẢN CHUNG**
 - Giấy phép này áp dụng cho bất kỳ cá nhân hoặc tổ chức nào (gọi chung là **"Người dùng"**) truy cập, tải xuống hoặc sử dụng mã nguồn/công cụ mang tên Pyshadow (gọi tắt là **"Công cụ"**).

**2. QUYỀN SỞ HỮU TRÍ TUỆ VÀ BẢN QUYỀN**
 - Quyền Sở hữu: ***PyMaKaizu*** là chủ sở hữu duy nhất của **công cụ**, bao gồm toàn bộ **mã nguồn**, thiết kế và tài liệu liên quan.
 - Cấm Sao chép: Cấm tuyệt đối mọi hành vi **sao chép**, **tái bản** (**reproduction**) hoặc phân phối lại **công cụ** dưới bất kỳ hình thức nào mà không có sự **cho phép bằng văn bản từ Chủ sở hữu**.
 - Cấm Đánh cắp Mã nguồn: Nghiêm cấm mọi hành vi **trích xuất**, **đánh cắp**, **sao chép** hoặc phổ biến bất kỳ phần nào của mã nguồn gốc của **công cụ**.

**3. QUYỀN CỦA NGƯỜI DÙNG**
- **Người dùng được quyền:**

    - Sử dụng: Sử dụng Phần mềm cho các mục đích hợp pháp và phù hợp với các điều khoản của Giấy phép này.
    - Lấy Liên kết (**Raw Link**): Được quyền lấy liên kết raw (**raw link**) của **công cụ** hoặc các thành phần liên quan để gửi các yêu cầu thực thi (ví dụ: thực thi code qua công cụ bên ngoài, CI/CD, hoặc tương tự), với điều kiện việc thực thi đó không vi phạm bất kỳ điều khoản cấm nào dưới đây.

**4. HÀNH VI CẤM VÀ GIỚI HẠN SỬ DỤNG**
 - **Người dùng tuyệt đối không được thực hiện các hành vi sau:**

     - Sử dụng **Trái phép**: Sử dụng **công cụ** vào bất kỳ mục đích nào cho công cụ/hoạt động trái phép, bất hợp pháp, độc hại hoặc **vi phạm pháp luật hiện hành**.
     - Phân phối **Mã độc**: Sử dụng **công cụ** để tạo, chia sẻ, phân phối hoặc quảng bá mã độc hại (malware), virus, trojan, hoặc bất kỳ phần mềm gây hại nào khác.
     - **Lạm dụng**: Cố ý sử dụng **công cụ** sai mục đích, gây hại, hoặc làm tổn thất đến danh tiếng, tài sản của Chủ sở hữu hoặc bên thứ ba.

**5. TỪ CHỐI TRÁCH NHIỆM**
 - Tự Chịu Trách Nhiệm: Người dùng hoàn toàn tự chịu trách nhiệm đối với mọi hậu quả, tổn thất hoặc trách nhiệm pháp lý phát sinh từ việc cố tình hoặc vô ý sử dụng sai mục đích hoặc vi phạm bất kỳ điều khoản nào của Giấy phép này. Chủ sở hữu **công cụ** (***PyMaKaizu***) sẽ không chịu bất kỳ trách nhiệm pháp lý nào liên quan đến việc lạm dụng hoặc sử dụng **công cụ** vào mục đích bất hợp pháp của Người dùng.

**6. GIỚI HẠN TRÁCH NHIỆM**
- Chủ sở hữu không chịu trách nhiệm cho bất kỳ thiệt hại trực tiếp, gián tiếp, ngẫu nhiên, đặc biệt hoặc hệ quả nào (bao gồm nhưng không giới hạn ở mất mát dữ liệu, thiệt hại kinh doanh, kiện tụng pháp lý...) phát sinh từ việc sử dụng hoặc không thể sử dụng Công cụ, kể cả khi Chủ sở hữu đã được thông báo về khả năng xảy ra các thiệt hại đó.

**7. KHÔNG CHUYỂN NHƯỢNG**
- Các tổ chức, cá nhân không được phép bán lại, chuyển nhượng, cho thuê, mua bán dưới mọi hình thức đối với các công cụ được chia sẻ miễn phí. Nếu bị phát hiện chúng tôi sẽ chấm dứt hỗ trợ đối với các phiên bản bị chia sẻ mã nguồn không còn tên của chúng tôi hoặc ít nhất bị sửa đổi.

**8. CẬP NHẬT VÀ THAY ĐỔI**
- Chủ sở hữu có quyền sửa đổi, bổ sung hoặc cập nhật các điều khoản của Giấy phép này bất cứ lúc nào. Các bản cập nhật sẽ có hiệu lực ngay khi được công bố trên kênh chính thức của Chủ sở hữu.
- Người dùng tiếp tục sử dụng Công cụ đồng nghĩa với việc đồng ý với các điều khoản được cập nhật.

**9. CƠ CHẾ VÔ HIỆU HÓA VÀ XỬ LÝ VI PHẠM**
- Chủ sở hữu có quyền vô hiệu hóa, thu hồi hoặc xóa bỏ enc_id mà không cần báo trước nếu phát hiện hành vi vi phạm các điều lệ trong giấy phép này.
- Người dùng có quyền khiếu nại nếu cho rằng việc vô hiệu hóa là không chính xác, nhưng phải cung cấp bằng chứng hợp lệ.
- Các phiên bản, enc_id bị vô hiệu hóa sẽ **không được phục hồi** nếu không có thỏa thuận lại bằng văn bản từ Chủ sở hữu.

**10. XÁC THỰC PHIÊN BẢN & CẢNH BÁO GIẢ MẠO**
- Phiên bản chính thức của Công cụ phải có chữ ký hoặc thông tin nhận dạng từ Chủ sở hữu và ít nhất có banner quen thuộc của chúng tôi thì mới chấp nhận hỗ trợ.
- Các bản bị chỉnh sửa, giả mạo, crack hoặc phân phối lại không thông qua kênh chính thức **sẽ không được hỗ trợ**, và **mọi trách nhiệm phát sinh thuộc về người sử dụng**.

**11. QUYỀN CẬP NHẬT & BẢO TRÌ**
- Đôi khi Chủ sỡ hữu tức chúng tôi sẽ tạm dừng Công cụ để cập nhật, bảo trì, vá lỗ hổng, sẽ không báo trước nếu truy cập công cụ không được thì bạn thử lại sau ít phút đến vài giờ.

**12. QUYỀN KIỂM SOÁT TẠM THỜI**
- Trong trường hợp phát hiện rủi ro bảo mật, lạm dụng diện rộng hoặc sự cố nghiêm trọng
- Chủ sở hữu có quyền:
    - Tạm vô hiệu hóa enc_id.
    - Chặn tạm thời công cụ mà không cần báo trước.
    - Sau khi sự cố được giải quyết, quyền truy cập có thể được khôi phục nếu người dùng không vi phạm.

**13. PHÂN LOẠI SỬ DỤNG HỢP LỆ**
- Mục đích hợp lệ: bảo vệ mã nguồn, kiểm soát phát hành mã, xác thực và bảo mật thông tin.
- Mục đích bị cấm: che giấu mã độc, thực hiện các hoạt động vi phạm pháp luật, gây hại cho hệ thống hoặc người dùng khác.
- Người dùng vi phạm phân loại sử dụng này sẽ bị thu hồi quyền truy cập mà không cần thông báo trước.

**14. ĐIỀU KHOẢN CUỐI CÙNG**
- Nếu một điều khoản trong bản giấy phép này bị coi là không hợp lệ hoặc không thể thực thi theo pháp luật, các điều khoản còn lại vẫn giữ nguyên hiệu lực.
- Việc Chủ sở hữu không thực thi bất kỳ điều khoản nào không có nghĩa là từ bỏ quyền thực thi trong tương lai.
- Giấy phép được điều chỉnh và giải thích theo pháp luật Việt Nam. Chúng tôi sẽ tố giác các hành vi sai trái đến các cơ quan công an có thẩm quyền.
- Trong trường hợp Người dùng không thuộc lãnh thổ Việt Nam, các tranh chấp hoặc khiếu nại sẽ được xử lý theo quy định của Luật An ninh mạng quốc tế và các hiệp ước quốc tế liên quan đến quyền sở hữu trí tuệ.
- Các bạn quốc tể xin hãy đọc điều khoản vì khi vi phạm chúng tôi sẽ làm gắt hơn sẽ không có khiếu lại nào dành cho các bạn.
- Các hành vi vi phạm nghiêm trọng có thể dẫn đến việc cấm vĩnh viễn địa chỉ IP và thiết bị liên quan.

**15. TỔNG KẾT**
- Nếu có việc tranh chấp kiện tụng pháp lí mã chúng tôi sẽ vô hiệu hóa enc_id đến khi các bạn hoặc người cung cấp Công cụ đã giải quyết xong với nhau hoặt ít nhất rằng người làm tool (Dev) cung cấp được bằng chứng mã không hề gây hại. Chúng tôi sẽ vô hiệu hóa từ 24 đến 48 giờ để trong thời gian này Dev có thể cung cấp xác thực, nếu hết thời gian mà không cung cấp được tính xác thực thì chúng tôi có quyền quyết định xóa vĩnh viễn, đồng thời chúng tôi không chịu trách nhiệm thiệt hại nào về thời gian bị vô hiệu hóa.
- Việc tổ chức hoặc cá nhân đã dùng công cụ của chúng tôi đều phải tuân thủ các điều lệ này không có ngoại lệ đối với cá nhân hoặc tổ chức nếu bạn không chấp nhận thì dùng mã hóa của người khác chúng tôi không ép buộc nhưng đã dùng mã hóa của chúng tôi các bạn không có quyền lựa chọn không bị ràng buộc với các điều lệ trên.
 - Giấy phép này có hiệu lực ngay khi Người dùng bắt đầu truy cập hoặc sử dụng **công cụ**. Chủ sở hữu có quyền chấm dứt với người dùng nếu vi phạm các điều lệ trên.

**Ngày ban hành:** 10-10-2025  
**Phiên bản:** 5.7.1  
© 2025 PyMaKaizu – All Rights Reserved.


# Language English

# PyMaKaizu License v5.7.1 (Non-Commercial Use)

The following tools are covered under this license: PyShadow, PyMaKaizu, and PyZuma.

License updated on October 10, 2025, and applies collectively to all tools above.

Introduction

This document is the official Software License Agreement for PyShadow, PyMaKaizu, and PyZuma.
By accessing, downloading, or using the Tools, the User acknowledges and agrees to comply with all terms and conditions set forth below.
PyMaKaizu is the owner and retains full intellectual property rights over these Tools.

Our purpose is to provide protection against cracking and reverse engineering attacks. We aim to make it harder and more time-consuming for attackers to compromise your source code.
However, no protection is perfect, and we cannot guarantee absolute security. Our system only increases the difficulty for attackers.
Additionally, we monitor your code’s behavior — if signs of malware, keyloggers, or similar malicious activities are detected, we will immediately block the associated tool and terminate service.
We do not accept appeals or reinstate support for violators.

What We Protect

Prevention of network monitoring and custom-made network inspection tools.

Blocking popular tools such as httptoolkit, mitm, httpproxy, httpdebugging, etc.

Prevention of dynamic and static reverse engineering tools such as FRIDA, DECOMPILE6, UNCOMPILE3, GDB, DEBUGGING, etc.

Protection against both dynamic and static analysis tools.

Continuous process and network behavior monitoring to prevent hooking.

Prevention of low-level and high-level hooking, but not guaranteed against OS or Kernel-level hooks.

Prevention of software cracking attempts.

Blocking of fake certificates including CA, CC, SC, CSC, EC, DSC, EV, OV, DV, etc.

Notices

Execution Time
Code execution time may increase significantly due to verification and re-signing processes.
We cannot guarantee the same performance as the original unprotected code.

Violation Reporting
If you find any tool encrypted with our official encryptor showing signs of malware, virus, trojan, keylogger, etc., please report it immediately via Telegram: junidokai.
Include the enc_id in your report so we can disable the malicious tool.
Evidence is required to prove that the tool is harmful to avoid false removals.
Only officially encrypted tools (ENC) with our signature are eligible for removal requests; OBF versions are not supported.

Safety Assurance
Our behavior scanning system does not collect your data or source code.
It only detects whether your program sends suspicious data to external servers (e.g., keylogging).
We do not collect or store any of your code or data.

0. DEFINITIONS

“Tool” refers collectively to PyShadow, PyMaKaizu, and PyZuma.

“ENC” refers to any file or tool encrypted by the official encryption system.

“OBF” refers to obfuscated variants released but not officially supported.

“Owner” refers to the original development group, PyMaKaizu.

“enc_id” is a unique identifier generated by our encryption system to manage, verify, and revoke access if violations occur.

1. GENERAL TERMS

This license applies to any individual or organization (hereinafter referred to as the "User") that accesses, downloads, or uses the code/tool named PyShadow (the "Tool").

2. INTELLECTUAL PROPERTY AND COPYRIGHT

Ownership:
PyMaKaizu is the sole owner of the Tool, including all source code, designs, and related documentation.

No Copying:
Any form of copying, reproduction, or redistribution without written consent from the Owner is strictly prohibited.

No Source Theft:
Extraction, duplication, or distribution of the Tool’s source code is forbidden.

3. USER RIGHTS

Users are allowed to:

Use:
Use the software for lawful purposes consistent with this License.

Raw Link Access:
Access raw links of the Tool or related components for execution (e.g., code execution through CI/CD or external systems), provided it does not violate any restrictions below.

4. PROHIBITED ACTIONS AND USAGE RESTRICTIONS

Users are strictly prohibited from:

Unauthorized Use:
Using the Tool for illegal, unlawful, or malicious purposes.

Malware Distribution:
Creating or distributing malware, viruses, trojans, or any harmful software.

Abuse:
Misusing the Tool in ways that damage the Owner’s reputation or property.

5. DISCLAIMER OF LIABILITY

User Responsibility:
The User assumes full responsibility for all consequences arising from misuse, intentional or accidental.
The Owner (PyMaKaizu) shall not be liable for any legal or financial damages caused by improper or illegal usage of the Tool.

6. LIMITATION OF LIABILITY

The Owner is not liable for any direct, indirect, incidental, or consequential damages (including but not limited to data loss, business interruption, or legal disputes) arising from the use or inability to use the Tool, even if advised of possible damages.

7. NON-TRANSFERABILITY

Users may not sell, lease, rent, or transfer the Tool in any form.
Any detected redistribution or modification will result in termination of support.

8. UPDATES AND MODIFICATIONS

The Owner reserves the right to revise, update, or modify this License at any time.
Updates take effect immediately upon publication via official channels.
Continued use of the Tool constitutes acceptance of the new terms.

9. REVOCATION AND VIOLATION HANDLING

The Owner may revoke, disable, or delete an enc_id without notice if a violation is detected.
Users may file an appeal with valid evidence.
Once revoked, an enc_id cannot be restored unless reauthorized in writing by the Owner.

10. AUTHENTICATION AND ANTI-FORGERY NOTICE

Official Tools must contain a signature or identifier from the Owner.
Modified, cracked, or redistributed versions are not supported, and all responsibility falls on the user.

11. MAINTENANCE AND SERVICE RIGHTS

The Owner may temporarily suspend the Tool for maintenance, patching, or upgrades without prior notice.
If access is unavailable, try again after a few minutes or hours.

12. TEMPORARY CONTROL RIGHTS

In cases of severe security risks, widespread abuse, or system failures, the Owner may:

Temporarily disable the affected enc_id.

Block access to the Tool without notice.

Restore access once the issue is resolved and no violation is confirmed.

**13. VALID USE CLASSIFICATION**

Permitted Purposes:
Source code protection, release control, authentication, and security validation.

Prohibited Purposes:
Concealing malware, performing illegal actions, or harming systems or users.
Violators will lose access immediately without notice.

**14. FINAL TERMS**

If any clause in this License is deemed invalid or unenforceable, the remaining clauses remain in effect.
Failure by the Owner to enforce any provision does not waive its future enforcement rights.
This License is governed by the laws of Vietnam.
Violations will be reported to the competent authorities.
For non-Vietnamese users, disputes shall follow international cybersecurity and IP law.
Severe violations may result in permanent bans of IP addresses and related devices.

**15. SUMMARY**

In case of legal disputes, the enc_id may be temporarily disabled for 24–48 hours while verification is performed.
If the developer fails to provide valid proof of legitimacy, the Owner reserves the right to permanently delete the enc_id.
The Owner holds no liability for losses during suspension.

All individuals or organizations using our encryption must comply with this License.
If you do not agree, you are free to use other encryption solutions.
However, by using our encryption, you are legally bound by these terms.

Issued on: October 10, 2025
Version: 5.7.1
© 2025 PyMaKaizu – All Rights Reserved.
