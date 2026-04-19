# Cách viết file Readme.md (Ngôn ngữ Markdown)
*Mẹo:* Dùng http://markdownlivepreview.com/ => code Markdown (Readme.md) bạn viết để xem trước. Hoặc thêm extention `Markdown All in One` trong VsCode
***
<br>

# 1.Tiêu đề ( `#` )

# Đây là tiêu đề 1.1

```
# Đây là tiêu đề 1.1
```

## Đây là tiêu đề 1.2

```
## Đây là tiêu đề 1.2
```

### Đây là tiêu đề 1.3

```
### Đây là tiêu đề 1.3
```

###### Đây là tiêu đề 1.6

```
###### Đây là tiêu đề 1.6
```

<br>
<br>


# 2. Chèn Code ( ` ``` ` )
*Chú ý: ``` ` ``` ở dưới dấu ``` ~ ``` ; Không phải ``` ' ``` ở dưới dấu ```<```
<br>

``` 
``` print("hello") ```
``` 

```
print("hello") //Kết quả
```
<br>

hoặc
```
```python
print("hello") ```
```

```python
print("hello") //Kết quả
```

<br>

hoặc
```
`print("hello")`
```
`print("hello")` //Kết quả

<br>

hoặc
```
>Blockquotes
>
>>Blockquotes
```
>Blockquotes
>
>>Blockquotes

<br>
<br>

# 3. Xuống dòng mới ( `<br>` )
```
Dòng 1
<br>
Dòng 2
```
Kết quả:
```
Dòng 1


Dòng 2
```

<br>
<br>

# 4. Chèn ảnh ( `![](...)` )

```
![](/Picture/scarlet.jpg)
```

Kết quả:<br>
![](/Picture/scarlet.jpg)

hoặc để chỉnh kích thước cho đẹp
```
<p align="center">
  <img src="/Picture/scarlet.jpg" width="300">
</p>
```
Kết quả:<br>
<p align="center">
  <img src="/Picture/scarlet.jpg" width="300">
</p>

<br>
<br>

# 5. Chèn link ( `[...](...)` )

```
[Github](https://github.com)
```
Kết quả: [Github](https://github.com)

<br>

hoặc
```
https://github.com
```
Kết quả: https://github.com

<br>
<br>

# 6. Ký tự in đậm, in nghiêng ( ` * ` )
<br>

```
*từ cần in nghiêng*
```

Kết quả: *từ cần in nghiêng*

<br>

```
**từ cần in đậm**
```

Kết quả: **từ cần in đậm**

<br>

```
***từ cần đậm + nghiêng***
```

Kết quả: ***từ cần đậm + nghiêng***

<br>

```
~từ cần gạch~
```

Kết quả: ~từ cần gạch~
<br>
<br>

# 7. Gạch đầu dòng ( `Tab` )

```
- Gạch đầu dòng thứ nhất
  
  - Thụt với đầu dòng 1
  
  - Thụt với đầu dòng 1
 
- Gạch đầu dòng thứ hai
  
  - Thụt với đầu dòng 2
  
  - Thụt với đầu dòng 2
  
```

- Gạch đầu dòng thứ nhất
  
  - Thụt với đầu dòng 1
  
  - Thụt với đầu dòng 1
  
- Gạch đầu dòng thứ hai
  
  - Thụt với đầu dòng 2
  
  - Thụt với đầu dòng 2
  

<br>
<br>

# 8. Tạo bảng ( `|` )

```
| Cột 1 Hàng 1 | Cột 2 | Cột 3| Cột 4 |
|--------------|-------|------|-------|
| Hàng 2 | 2 x 1 | 2 x 2 | 2 x 3 | 2 x 4 |
| Hàng 3 | 3 x 1 | 3 x 2 | 3 x 3 | 3 x 4 |
| Hàng 4 | 4 x 1 | 4 x 2 | 4 x 3 | 4 x 4 |
```

Kết quả:

| Cột 1 Hàng 1 | Cột 2 | Cột 3| Cột 4 |
|--------------|-------|------|-------|
| Hàng 2 | 2 x 1 | 2 x 2 | 2 x 3 | 2 x 4 |
| Hàng 3 | 3 x 1 | 3 x 2 | 3 x 3 | 3 x 4 |
| Hàng 4 | 4 x 1 | 4 x 2 | 4 x 3 | 4 x 4 |

<br>
<br>

# 9. Kẻ ngang ( `***` )
```
***
```
Kết quả:
***

<br>
<br>
