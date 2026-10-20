

**4.1.Phần A – Tổ chức thư mục bằng GUI**
**4.2. Phần B – Thao tác bằng CLI (ôn Mục 4.2)**

•	B1. pwd 
•  B2. ls -a
•  B3. mv lich_hoc.txt docs/
           mv logo_trung_tam.png
           mv  anh_lop_hoc.jpg
•  B4.Copy-Item media/logo_trung_tam.png
•  B5.
 Rm temp_201.tmp 
           Rm temp_202.tmp
•  B6. cd logs
           cd ..
•  B7. Copy-Item ../media/anh_lop_hoc.jpg ../archive/ 
         cd ..
 *B8. Liệt kê toàn bộ dự án kể cả file ẩn.
            Get-ChildItem -Recurse -Force
            
        ** Gán các lệnh B1-B7**
        ```  
#B1: pwd 
#B2: ls -a 
#B3: mv lich_hoc.txt docs/
         mv logo_trung_tam.png/
         mv anh_lop_hoc.jpg media/ 
#B4: Copy-Item media/logo_trung_tam.png / 
#B5: Rm temp_201.tmp
         Rm temp_202.tmp 
#B6: cd logs; Get-ChildItem; cd .
#B7: cd docs; Copy-Item ../media/anh_lop_hoc.jpg ../archive/; cd .. 
```
