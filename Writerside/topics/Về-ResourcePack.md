# Về Gói Pack

Mục tiêu của danh mục này sẽ giúp bạn hiểu thêm về cấu tạo cơ bản của một gói ResourcePack

![image_2.png](image_2.png)

* **assets**: Chứa các file model json và texture cấu thành nên ResourcePack
  ![image_5.png](image_5.png)

* **pack.mcmeta**: Nơi lưu trữ tên và thông tin của gói ResourcePack
  ![image_4.png](image_4.png)

* **pack.png**: Là hình đại diện của gói ResourcePack
  ![image_3.png](image_3.png)

Cấu tạo chi tiết của gói ResourcePack có thể đọc [tại đây](https://minecraft.wiki/w/Tutorial:Creating_a_resource_pack)

**Cấu Trúc Model Item**
* Model Item thường sẽ có định dạng là <tên>.json và có thể mở bằng [BlockBench](https://www.blockbench.net/)
* Model Item thường nằm tại assets\minecraft\models\item
* Model Item phụ thuộc vào Texture Item (Kết Cấu) để hiển thị. Nếu không có Texture Item thì nó sẽ hiển thị đen và tím
  ![image_6.png](image_6.png)


**Cấu Trúc Texture Item**
* Texture Item thường có định dạng <tên>.png (Định dạng hình ảnh phổ biến)
* Texture Item thường nằm tại assets\minecraft\textures\item
* Texture Item có thể có hoạt ảnh động như hiệu ứng (Sẽ kèm theo một file <cùng tên>.png.mcmeta)
* Nếu không có .png.mcmeta thì sẽ không có hoạt ảnh cho Texture Item
  ![image_7.png](image_7.png)