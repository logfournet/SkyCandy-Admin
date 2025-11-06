# Thêm Model Item

Hướng dẫn thêm và config một model item vào SkyCandyPack

**Bước 1**
- Tìm kiếm model item mà bạn muốn thêm. Có thể tìm tại **[SyncMC](https://syncmc.forum/)** hoặc **[NullForums](https://nullforums.net/)**
- Tài và giải nén file model vừa tải về và tìm file json để mở bằng Blockbench giả sử như sau
![image_24.png](image_24.png)

**Bước 2**
- Tạo một file mới trên Panel. Đường dẫn là plugins/SkyCandyPack/pack/item
- Có thể sẽ có sẵn một số file như axe, sword.. và bạn thể click vào và tạo một file con trong đó
![image_25.png](image_25.png)
- Giả sử muốn thêm axe thì click vào axe rồi tạo một file mới (Có thể tạo file tự do, chủ yếu tạo 1 thư mục chung để dễ phân loại)
![image_26.png](image_26.png)
![image_27.png](image_27.png)
![image_28.png](image_28.png)
![image_29.png](image_29.png)

**Bước 3**
- Tìm kiếm file .json và .png (.png.mcmeta nếu có). Để biết json model đó dùng Texture nào thì **Chuột Phải** vào Texture cần chọn và chọn **Show In File Explorer**
![image_31.png](image_31.png)
![image_33.png](image_33.png)
![image_32.png](image_32.png)

- Ném toàn bộ các file .json và các file texture .png (Kể cả .png.meta nếu có)
![image_30.png](image_30.png)

**Bước 4**
- Tạo file config.yml để định danh item model đó giữa hàng ngàn item model khác cùng loại vật liệu
![image_34.png](image_34.png)
```yaml
customname: "&bOcean"
type: item/handheld
material: diamond_axe
customid: 5
```
![image_35.png](image_35.png)
- Chọn YAML và Create File
![image_36.png](image_36.png)
- Đặt tên file là **config.yml**
![image_38.png](image_38.png)
- Kết quả khi hoàn thành
![image_39.png](image_39.png)

**Bước 5**
- Dùng lệnh **/skycandypack build** để tiến hành xây dựng gói Pack
![image_40.png](image_40.png)
- Check thử bằng lệnh **/skycandypack gui**
![image_41.png](image_41.png)
- Ta thấy đã thêm thành công item model custom
![image_42.png](image_42.png)