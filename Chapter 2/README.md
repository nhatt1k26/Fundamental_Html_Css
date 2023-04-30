# Some keyword

## Compare % vs vh,vw

## Compare rem vs em

font-size: 100% = 16px

1 em = 1 rem = 16px

Change of rem depend on font-size, em dont

## Border

border-style: solid - dotted - dashed

border-top / border-bottom / border-left / border-right /out line  (cant be radius)/

border-radius: 10px 20px 30px 40px 50%;

## Margin

margin: 20px:  top = right = left =bottom =20px

margin: 20px 40px: top = bottom = 20px; right = left = 40px

margin: 10px 20px 30px: top = 10px; right = left = 20pxl bottom = 30px

margin: 10px 20px 30px 40px: top =10, right = 20, bottom= 30, left= 40 px

margin-left: auto;

margin-right:auto;

margin collapse: =max (margin-bottom, margin-top)

## Padding

Similar to margin

Contrast to Margin, we can not use negative number for padding

## Box sizing

width - width + padding-left + padding-right + border-left + border-right

width = 100px + 10px + 10px + 5px + 5px =130px ( with content-box)

width = 100px - 10px - 10px - 5px - 5px =130px ( with border-box )

## Inline block

## Font size

Google font

Font-family

sans-serif

font-weight

text-align

line-weight

max-width

 letter-spacing: 0.1rem;

 word-spacing: 0.1rem;

overflow: hidden;

text-overflow: ellipsis : display cdot inline

/* Hien thi dau 3 cham tren hang thu 3

display: -webkit-box

-webkit-box-orient: vertical;

-webkit-line-clamp: 3;

overflow: hidden;

text-overflow: ellipsis;

word-break: break-all;

word-break: break-work

## Picture Custom

    width:20rem;

    height: 20rem;

    object-fit: cover;

    object-position: left;

    margin: 0auto;

    display:inline-block

## Pseudo Class

.Pseudo:hover{

    color:orange;

}

.Pseudo:active{

    color:purple;

}

.Pseudo:visited{

    color: blue;

}

## Exercise

1. Tạo một khối có class là box có độ rộng và chiều cao lần lượt là 200x300, có màu nền là #ffa400 và chữ bất kỳ màu đên, border màu vàng, padding 10 px, margin 15px bo góc 4 px, chữ canh giữa
2. Tạo một khối cso đoạn chữ rất dài bất kỳ, có rộng tối đa là 500px, hiện thị 3 hàng kết hợp dấu 3 chấm.
3. Tạo một khối có đoạn chữ rất dài bất bất kyfm có độ rộng tối đa là 100px, hiện thị 1 hàng kết hợp dấu 3 chấm
4. Tạo một khối có độ rộng và chiều cao lần lượt là 100 vw và 100 vh cho hình nền bất kỳ, yêu cầu phủ toàn khối, canh góc bên phải, không có lặp lại.
5. Tạo một khối có độ rộng và chiều cao tương ứng là 400 x 400, và cho hình ảnh hiện thị bên trong, yêu cầu khối này là hình tròn, và hình ảnh nằm trọng trong bên trong, không được méo, không được tràn ra ngoài
6. Chèn font từ Google vào bài tập sử dụng fotn Roboto với các độ đậm là 400 và 600
