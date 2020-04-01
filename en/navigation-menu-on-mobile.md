# Navigation and Menu on Mobile

- [Hide Register and Login menus on mobile mode](#hide-register-and-login-menus-on-mobile-mode)
- [หัวข้อ2: บน Topmenu เมื่อเปลี่ยน Background Color เป็นสีเข้ม (Edit Section)  ต้องการเปลี่ยนสี Font ให้ชัดขึ้น](#หัวข้อ2-บน-topmenu-เมื่อเปลี่ยน-background-color-เป็นสีเข้ม-edit-section-ต้องการเปลี่ยนสี-font-ให้ชัดขึ้น)
- [หัวข้อ3: ต้องการเปลี่ยนสี  Background Color ของ Hamberger menu เมื่อแสดงที่หน้าจอมือถือ (เดิมเป็นสีดำ)](#หัวข้อ3-ต้องการเปลี่ยนสี-background-color-ของ-hamberger-menu-เมื่อแสดงที่หน้าจอมือถือ-เดิมเป็นสีดำ)

Once you built your website perfectly in both content and design, you may want to make it a little different between opening your website on computer screen and mobile. 


## Hide Register and Login menus on mobile mode

You can hide Register and Login menu on any device screens smaller than 1024px such as tablet and mobile.

1. On Content editor, click on 3-dot and select "CSS/JS"
   
=> น้องวุ่นดูรูปของพี่จะได้เลย เอาภาพให้เห็น่าอยู่บน content editor ด้วยจ้ะนะ (พี่รวม 1-3 ของพี่จะมาไว้ข้อเดียว๗ )

2. On Site Config panel, navigate to **Site** tab and select CMS from left menu. 

=> น้องวุ่นดูรูปของพี่จะข้อ 4 ได้เลย พร้อม คลิกเมนู CMS ซ้่ายมือ

3. On Site Management, select **CSS/JS** tab. 

=> น้องวุ่นดูรูปของพี่จะข้อ 4 เพิ่ม focus ตรง CSS/JS

4. Insert the following code.เพิ่ม Code ด้านล่างนี้ลงไป 

<style> 

@media only screen and (max-width:1024px) { 
  .top_login  { display:none; }     

   /*class_name*/ 
} 

</style> 

    class_name

    selected_topmenu {display:none;}  /*  to hide Topmenu Section  */ 

    sitemapFooter {display:none;}   /*  to hide Sitemap Footer Section  */ 

    poweredFooter {display:none;}  /*   to hide Powered Section */ 
    
=> น้องวุ่นดูรูปของพี่จะข้อ 4 เพิ่ม ใส่ code แบบที่พี่จะทพตัวอย่างเลย


5. Save this on Site Config panel.

=> น้องวุ่น ปแสดงปุ่ม save ของ panel site config

6. Don't forget to Save by the main save button.

=> น้องวุ่นการ save บน content editor หลัก

7. You will get like this.

=> น้องวุ่นดูรูปของพี่จะข้อ 8


------------------------------------------------------------------------------------------------


## หัวข้อ2: บน Topmenu เมื่อเปลี่ยน Background Color เป็นสีเข้ม (Edit Section)  ต้องการเปลี่ยนสี Font ให้ชัดขึ้น 

 

1. เข้าโปรแกรม RVsitebuilder  

2. เมนู Content 

3. คลิกปุ่ม Option (Three Dot) >> เลือก CSS/JS 

4. บน Dialog : Site Config >> เลือก Site Tab  

5. ใน List Menu เลือก CMS (ด้านซ้าย) 

6. ที่ Site Management >> เลือก CSS/JS 

เพิ่ม Code ด้านล่างนี้ลงไป  

<style> 

nav#topmenu a { color: #a9a9a9 !important; } 

</style> 

กด Save บน Dialog 

7.กด Save บน Program 

8.กด Mysite 

 

## หัวข้อ3: ต้องการเปลี่ยนสี  Background Color ของ Hamberger menu เมื่อแสดงที่หน้าจอมือถือ (เดิมเป็นสีดำ) 

เฉพาะหน้าจอตำ่กว่า 1024px  เช่น Mobile, Tablet  

               

1. เข้าโปรแกรม RVsitebuilder  

2. เมนู Content 

3. คลิกปุ่ม Option (Three Dot) >> เลือก CSS/JS 

4. บน Dialog : Site Config >> เลือก Site Tab  

 

5. ใน List Menu เลือก CMS (ด้านซ้าย) 

6. ที่ Site Management >> เลือกแท็บ CSS/JS 

เพิ่ม Code ด้านล่างนี้ลงไป 

<style> 

@media only screen and (max-width:1024px) { 

.uk-navbar {background-color: #501a00; color: #fff;}  /* background Logo Section */ 

.uk-offcanvas-bar { background: #501a00;} 

html:not(.uk-touch) .uk-nav-offcanvas > li > a:hover { 

                background: #00000030; color: #ffffff; 

} 

} 

</style> 

 

กด Save บน Dialog 

7.กด Save บน Program 

8.กด Mysite 

 

 