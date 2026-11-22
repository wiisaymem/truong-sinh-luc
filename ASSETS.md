# Trường Sinh Lục — SunnyLand
SunnyLand artwork: Luis Zuno / ansimuz, CC0. Xác nhận https://opengameart.org/content/sunny-land-2d-pixel-art-pack . Mirror cộng đồng https://github.com/hanmi255/SunnyLand ; không khẳng định là bản mới nhất.
Tất cả PNG dưới đã xem trực quan; nạp trực tiếp, cần mạng:
- https://raw.githubusercontent.com/hanmi255/SunnyLand/HEAD/assets/textures/Layers/back.png — trời cyan, mây trắng, CC0
- https://raw.githubusercontent.com/hanmi255/SunnyLand/HEAD/assets/textures/Layers/middle.png — núi/đảo phủ cây, hai lớp parallax, CC0
- https://raw.githubusercontent.com/hanmi255/SunnyLand/HEAD/assets/textures/Layers/tileset.png — cỏ/đất và đá chân bậc, CC0
- https://raw.githubusercontent.com/hanmi255/SunnyLand/HEAD/assets/textures/Props/tree.png — cây lá rộng, CC0
- https://raw.githubusercontent.com/hanmi255/SunnyLand/HEAD/assets/textures/Props/pine.png — thông, CC0
- https://raw.githubusercontent.com/hanmi255/SunnyLand/HEAD/assets/textures/Props/bush.png — bụi cây, CC0
- https://raw.githubusercontent.com/hanmi255/SunnyLand/HEAD/assets/textures/Props/rock.png — đá trang trí, CC0
- https://raw.githubusercontent.com/hanmi255/SunnyLand/HEAD/assets/textures/Props/shrooms.png — nấm, CC0
- https://raw.githubusercontent.com/hanmi255/SunnyLand/HEAD/assets/textures/Props/sign.png — biển gỗ, CC0
- https://raw.githubusercontent.com/hanmi255/SunnyLand/HEAD/assets/textures/Props/wooden-house.png — nhà gỗ cảnh nền, CC0
- https://raw.githubusercontent.com/hanmi255/SunnyLand/HEAD/assets/textures/Props/platform-long.png — mặt bậc gỗ, CC0
- https://raw.githubusercontent.com/hanmi255/SunnyLand/HEAD/assets/textures/Props/crate.png — thùng, CC0
Không dùng nhân vật SunnyLand thay Martial Hero. Đã xem FX/item-feedback.png nhưng không dùng vì chưa có combat. Mirror có nhiều props khác, không tuyên bố thiếu toàn bộ. Không có đèn lồng/hàng rào cổ trang được dùng từ mirror; đèn lồng, cột, tường, biển tên còn tự vẽ canvas tạm. Nhà gỗ chỉ trang trí, không thêm va chạm.
Martial Hero — LuizMelo, CC0; giữ cắt frame 200x200, Idle/Run 8 frame, Jump/Fall 2 frame:
- https://raw.githubusercontent.com/gengen1988/unity-martial-hero/master/Textures/Idle.png
- https://raw.githubusercontent.com/gengen1988/unity-martial-hero/master/Textures/Run.png
- https://raw.githubusercontent.com/gengen1988/unity-martial-hero/master/Textures/Jump.png
- https://raw.githubusercontent.com/gengen1988/unity-martial-hero/master/Textures/Fall.png
Mirror https://github.com/gengen1988/unity-martial-hero
Chinese Temple — bart, CC-BY 3.0: https://opengameart.org/content/minimalist-chinese-temple-tileset ; PNG https://opengameart.org/sites/default/files/Chinese%20Temple.png ; license https://creativecommons.org/licenses/by/3.0/ . Thay đổi: bỏ nền trắng, tăng sáng/tăng sắc đỏ cam bằng canvas; ghép tile theo sàn mái gốc.
Giữ map 7680x832, toàn bộ tọa độ sàn, NPC hue 140/265/55, input pointerId và phím, camera và cơ chế bay/nhảy/ngồi. Không có sát thương, nội lực thật, ngự kiếm, nhạc hoặc chu kỳ ngày đêm. Bản gốc v2 đã được thay bằng gói offline trong repo.

Bản sửa 22/11/2026: PNG offline tại assets/sunnyland/ và assets/hero/; Temple giữ base64. Bố trí largeProps kiểm tra toàn bộ AABB ảnh, không trừ vùng trong suốt: 226 cặp trước, 0 cặp sau. Khoảng hở nhà gỗ–cây tối thiểu 24 px; giữ cây ngoài vùng đền. Y-sort theo chân, cây phía sau nhà khi cùng chân. Bụi là lớp nhỏ, được phép chạm gốc; không áp dụng cho kiểm đếm props lớn. Không thay đổi tọa độ solids, NPC, player hoặc input.
