# KillAura
## 1. Định nghĩa

Là 1 hack cho phép tự đánh vào mục tiêu trong phạm vi xác định.

## 2. Ý nghĩa

- Là 1 hack có độ phổ biến lớn trong cộng đồng cheat.
- Hack này có thể diệt bất kì mục tiêu nào mà không cần phải đánh.
- Rất mạnh, khó patch.

## 3. Tham số

- MinCPS:
+ Định dạng: Số tự nhiên
+ Ý nghĩa: CPS tối thiểu để đánh mục tiêu
+ Giới hạn khi chỉnh trong ClickGUI: 0 - 20
+ Giới hạn khuyến cáo: 9 - 18
- MaxCPS
+ Định dạng: Số tự nhiên
+ Ý nghĩa: CPS tối đa để đánh mục tiêu
+ Giới hạn khi chỉnh trong ClickGUI: 0 - 20
+ Giới hạn khuyến cáo: 9 - 18
- HurtTime
+ Định dạng: Số tự nhiên
+ Ý nghĩa: Thời gian nghỉ giữa 2 hit, tính theo tick
+ Giới hạn khi chỉnh trong ClickGUI: 0 - 10
+ Giới hạn khuyến cáo: 10
- Range
+ Định dạng: Số thập phân
+ Ý nghĩa: Vùng có thể đánh trong một phạm vi xác định, tính theo đơn vị “mét” trong Minecraft (1 mét = 1 block)
+ Giới hạn khi chỉnh trong ClickGUI: 0.00 - 8.00
+ Giới hạn khuyến cáo: 3.00 - 5.00
- ThroughWallsRange 
+ Định dạng: Số thập phân
+ Ý nghĩa: Vùng có thể đánh xuyên tường trong một phạm vi xác định, tính theo đơn vị “mét” (giống Range)
+ Giới hạn khi chỉnh trong ClickGUI: 0.00 - 8.00
+ Giới hạn khuyến cáo: 0.00 - 2.50
- RangeSprintReducement 
+ Định dạng: Số thập phân
+ Ý nghĩa: Phần phạm vi bị giảm đi do sprint
+ Giới hạn khi chỉnh trong ClickGUI: 0.00 - 0.40
+ Giới hạn khuyến cáo: 0.00 - 0.10
- SwingRange (FDP Client)
+ Định dạng: Số thập phân
+ Ý nghĩa: Vùng phạm vi kích hoạt animation item (điều kiện mục tiêu phải nằm trong phạm vi kích hoạt)
+ Giới hạn khi chỉnh trong ClickGUI: 0.00 - 8.00
+ Giới hạn khuyến cáo: 4.00 - 8.00
- DiscoverRange (FDP Client)
+ Định dạng: Số thập phân
+ Ý nghĩa: Vùng phạm vi kích hoạt 
+ Giới hạn khi chỉnh trong ClickGUI: 0.00 - 8.00
+ Giới hạn khuyến cáo: DiscoverRange > Range
- RotationMode
+ Định dạng: Danh sách
+ Ý nghĩa: Chế độ xoay người chơi đến mục tiêu
+ Mode thường gặp: Vanilla, Backtrack (Liquidbounce); LiquidBounce, ForceCenter, SmoothCenter (FDP)
- Spin-HitHurtTime (Liquidbounce)
+ Định dạng: Số tự nhiên
+ Ý nghĩa: Thời gian nghỉ hit giữa 2 lượt xoay trong RotationMode Spin, tính theo tick
+ Giới hạn khi chỉnh trong ClickGUI: 0 - 10
+ Giới hạn khuyến cáo: 10
- MaxSpinSpeed (Liquidbounce)
+ Định dạng: Số thập phân
+ Ý nghĩa: Tốc độ quay tối đa của RotationMode Spin
+ Giới hạn khi chỉnh trong ClickGUI: 0.00 - 180.00
+ Giới hạn khuyến cáo: 30.00 - 150.00
- MinSpinSpeed (Liquidbounce)
+ Định dạng: Số thập phân
+ Ý nghĩa: Tốc độ quay tối thiểu của RotationMode Spin
+ Giới hạn khi chỉnh trong ClickGUI: 0.00 - 180.00
+ Giới hạn khuyến cáo: 30.00 - 150.00
- MaxTurnSpeed 
+ Định dạng: Số thập phân
+ Ý nghĩa: Tốc độ quay tối đa của người chơi đến mục tiêu 
+ Giới hạn khi chỉnh trong ClickGUI: 0.00 - 180.00
+ Giới hạn khuyến cáo: 60.00 - 150.00
- MinTurnSpeed 
+ Định dạng: Số thập phân
+ Ý nghĩa: Tốc độ quay tối thiểu của người chơi đến mục tiêu 
+ Giới hạn khi chỉnh trong ClickGUI: 0.00 - 180.00
+ Giới hạn khuyến cáo: 60.00 - 150.00
- RoundAngle (Liquidbounce)
+ Định dạng: Bật / tắt
+ Ý nghĩa: Phép làm tròn tốc độ quay
+ Khuyến cáo: không bật
- RoundAngle-Directions
+ Định dạng: Số tự nhiên
+ Ý nghĩa: Độ chính xác của phép làm tròn góc quay
+ Giới hạn khi chỉnh trong ClickGUI: 2 - 45
+ Giới hạn khuyến cáo: 4
- NoSendRotation:
+ Định dạng: Bật / tắt
+ Ý nghĩa: Quay trong im lặng (RotationMode Spin)
+ Khuyến cáo: bật
- NoHitCheck (AlwaysHitable):
+ Định dạng: Bật / tắt
+ Ý nghĩa: Không kiểm tra hit target
+ Khuyến cáo: Tuỳ theo độ mạnh của anticheat, yếu nên bật
- BlinkCheck:
+ Định dạng: Bật / tắt
+ Ý nghĩa: Check có bật Blink để huỷ KillAura
+ Khuyến cáo: Tuỳ
- Priority
+ Định dạng: Danh sách
+ Ý nghĩa: Lựa chọn mục tiêu được ưu tiên
+ Mode thường gặp: Health, Distance, Direction(LiquidBounce), LivingTime, Armor, HurtResistance(FDP Client), HurtTime, HealthAbsorption(FDP Client), RegenAmplifier(FDP Client)
- TargetMode
+ Định dạng: Danh sách
+ Ý nghĩa: lựa chọn đơn hoặc đa mục tiêu
+ Mode thường gặp: Single, Switch, Multi
- Swing
+ Định dạng: Bật / tắt
+ Ý nghĩa: Animation khi sử dụng KillAura vào mục tiêu
+ Khuyến cáo: Tuỳ theo độ mạnh của anticheat, yếu nên bật
- KeepSprint
+ Định dạng: Bật / tắt
+ Ý nghĩa: Vẫn Sprint khi đang tấn công mục tiêu
+ Khuyến cáo: Tuỳ theo độ mạnh của anticheat, yếu nên bật
- AttackTiming
+ Định dạng: Danh sách
+ Ý nghĩa: Loại thời gian đánh mục tiêu
+ Mode thường gặp: Pre, Post, All, Legit(FDP Client)
- AutoBlock(LiquidBounce)
+ Định dạng: Danh sách
+ Ý nghĩa: Tự động chặn kiếm khi tấn công mục tiêu
+ Mode thường gặp: None, Packet, Vanilla, AfterTick, AfterAttack
- AutoBlock (FDP Client)
+ Định dạng: Danh sách
+ Ý nghĩa: Hình thức chặn kiếm
+ Mode thường gặp: Range, Fake, None
- AutoBlockPacket (FDP Client)
+ Định dạng: Danh sách
+ Ý nghĩa: Tự động chặn kiếm khi tấn công mục tiêu
+ Mode thường gặp: AfterTick, AfterAttack, Vanilla, Delayed, Delayed2, Legit, OldIntave, OldHypixel, Test
- AutoBlockRange
+ Định dạng: Số thập phân
+ Ý nghĩa: Phạm vi chặn kiếm khi tấn công mục tiêu
+ Giới hạn chỉnh ClickGUI: 0.00 - 8.00
+ Giới hạn khuyến cáo: 3.00 - 5.00
- AutoBlockSetting (LiquidBounce): Định dạng đúng / sai, gồm
+ InteractAutoBlock: Autoblock ở góc nhìn thứ 3
+ VerusAutoBlock: 1 dạng autoblock bypass Verus có thể đi kèm với các AutoBlock khác
+ AutoBlockThroughWalls: AutoBlock xuyên tường
+ SmartAutoBlock: AutoBlock thông minh
- BlockRate
+ Định dạng: Số tự nhiên
+ Ý nghĩa: Tỉ lệ chặn kiếm khi tấn công 
+ Giới hạn chỉnh ClickGUI: 0 - 100, đơn vị “%”
+ Giới hạn khuyến cáo: 100%
- RayCast
+ Định dạng: Bật / tắt
+ Ý nghĩa: Đánh bất kỳ mục tiêu nào (Được coi mục tiêu) nằm giữa bạn và mục tiêu (Như thể nhắm vào đó và đánh vào)
+ Khuyến cáo: Bật hay không cũng không ảnh hưởng
- RayCastIgnored (Cần bật RayCast)
+ Định dạng: Bật / tắt
+ Ý nghĩa: Giống như RayCast, nhưng bỏ qua Mục tiêu và đánh bất cứ thứ gì giữa bạn và mục tiêu
+ Khuyến cáo: Bật hay không cũng không ảnh hưởng
- LivingRayCast (Cần bật RayCast)
+ Định dạng: Bật / tắt
+ Ý nghĩa: Bỏ qua tất cả các thực thể không là thực thể sống
+ Khuyến cáo: Bật hay không cũng không ảnh hưởng
- AAC (LiquidBounce, FDP <= 3.1.1)
+ Định dạng: Bật / tắt
+ Ý nghĩa: Bypass của AAC
+ Khuyến cáo: Tuỳ theo độ mạnh của anticheat, yếu nên bật
+ Note: Tính năng này đã bị loại bỏ từ LiquidBounce B88
- SilentRotation:
+ Định dạng: Bật / tắt
+ Ý nghĩa: Khi KillAura aim vào mục tiêu góc nhìn không bị thay đổi
+ Khuyến cáo: Tuỳ theo độ mạnh của anticheat, yếu nên bật
- Strafe
+ Định dạng: Danh sách
+ Ý nghĩa: Tự do di chuyển qua lại mục tiêu theo hình vòng cung khi bật KillAura
+ Mode thường gặp: Silent, Off, Strict
- FOV
+ Định dạng: Số thập phân
+ Ý nghĩa: Góc người chơi nhìn thấy kẻ địch để KillAura
+ Giới hạn chỉnh trong ClickGUI: 0 -> 180
+ Giới hạn khuyến cáo: 180
- Predict
+ Định dạng: Bật / tắt
+ Ý nghĩa: Phép điều chỉnh HitBox kẻ địch
+ Khuyến cáo: Tuỳ theo anticheat
- MaxPredictSize
+ Định dạng: Số thập phân
+ Ý nghĩa: Hệ số HitBox tối đa có thể hit được
+ Giới hạn trong ClickGUI: 0.1 - 5
+ Giới hạn khuyến cáo: 1
- MinPredictSize
+ Định dạng: Số thập phân
+ Ý nghĩa: Hệ số HitBox tối thiểu có thể hit được
+ Giới hạn trong ClickGUI: 0.1 - 5
+ Giới hạn khuyến cáo: 1

- Strafe
+ Định dạng: Danh sách
+ Ý nghĩa: Tự do di chuyển qua lại mục tiêu theo hình vòng cung khi bật KillAura
+ Mode thường gặp: Silent, Off, Strict
- Strafe
+ Định dạng: Danh sách
+ Ý nghĩa: Tự do di chuyển qua lại mục tiêu theo hình vòng cung khi bật KillAura
+ Mode thường gặp: Silent, Off, Strict
- Strafe
+ Định dạng: Danh sách
+ Ý nghĩa: Tự do di chuyển qua lại mục tiêu theo hình vòng cung khi bật KillAura
+ Mode thường gặp: Silent, Off, Strict
- Strafe
+ Định dạng: Danh sách
+ Ý nghĩa: Tự do di chuyển qua lại mục tiêu theo hình vòng cung khi bật KillAura
+ Mode thường gặp: Silent, Off, Strict
- Strafe
+ Định dạng: Danh sách
+ Ý nghĩa: Tự do di chuyển qua lại mục tiêu theo hình vòng cung khi bật KillAura
+ Mode thường gặp: Silent, Off, Strict
- Strafe
+ Định dạng: Danh sách
+ Ý nghĩa: Tự do di chuyển qua lại mục tiêu theo hình vòng cung khi bật KillAura
+ Mode thường gặp: Silent, Off, Strict
- Strafe
+ Định dạng: Danh sách
+ Ý nghĩa: Tự do di chuyển qua lại mục tiêu theo hình vòng cung khi bật KillAura
+ Mode thường gặp: Silent, Off, Strict
