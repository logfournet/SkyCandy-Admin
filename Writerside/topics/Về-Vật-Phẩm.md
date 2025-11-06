# Item Model

Cấu tạo của một item model sẽ bao gồm 1 file config.yml, 1 file json (.json) và một hoặc nhiều file texture (.png) với file texture có thể đi kèm với file .png.mcmeta cùng tên nếu có
![image_23.png](image_23.png)

* **config.yml**: Chứa tên hiển thị, loại model item, vật liệu và customid vật phẩm!
```yaml
customname: "&bTên Model"
type: item/handheld
material: netherite_axe
customid: 16
```

| Config               | Công Dụng                                                                                                                                            |
|---------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------|
| customname       | Tên được hiển thị trong Gui                                                                                                                          | 
| type         | Mặc dịnh là item/handheld, giữ nguyên                                                                                                                | 
| material         | Vật liệu muốn thêm custom model ([Material](https://hub.spigotmc.org/javadocs/bukkit/org/bukkit/Material.html))                                      | 
| customid        | Là một con số từ 0-999999 dùng để định danh các model với nhau để thêm vào MMOItems, không được trùng nhau và customid mới phải lớn hơn customid cũ. | 


* **.json**: Chứa tên, cấu trúc cube-block của vật phẩm cũng như danh sách texture (Có thể mở bằng [Blockbench](https://www.blockbench.net/))
![image_16.png](image_16.png)
![image_18.png](image_18.png)
![image_15.png](image_15.png)

* **.png**: Là định dạng hình ảnh được dùng làm Texture cho file .json trên. Ta có thể thấy tại mục Texture trong Blockbench
![image_19.png](image_19.png)
Bạn có thể tìm thấy đường dẫn tới Texture bằng cách **Chuột Phải** vào Texture cần chọn và chọn **Show In File Explorer** 
![image_20.png](image_20.png)
![image_17.png](image_17.png)

* **.png.mcmeta**: Là định dạng animation (hoạt ảnh frame) thường đi kèm với .png với tên file cùng tên với một file .png bất kì dùng để tạo hoạt ảnh cho Texture. Một số model item thì thường sẽ không có file này đi kèm với file .png
![image_21.png](image_21.png)

Có thể nhận biết Texture có hoạt ảnh hay không thì trong Blockbench phần Texture sẽ hiện **Icon Đoạn Phim** góc phải dưới cùng! Nếu không có hoạt ảnh thì sẽ không có **Icon** này
![image_22.png](image_22.png)