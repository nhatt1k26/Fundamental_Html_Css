## Transform property

transform:

 scaleX(2)	scaleY(2) =  scaleX(2,2)

rotate(45deg) 

translateX(1rem) = margin-left(10px)

translateX(100%):  100 % = width

translateY(100%): 100% = height

translateX(100%) translateY(100%) = translate(100%,100%)

skew(30deg) - create

## Position Relative

left: 10px

top

bottom

right

## Position: absolute -> Không chiếm diện tích 

Chú ý ( position: absolute của div con cần đi kèm với postion: absolute theo div cha)

left/ top/bottom/right: ăn theo div cha

transform: translate ăn theo div con 

Cách phủ hết 1 box nằm trong div cha:

top:0;

left:0;

right:0;

bottom:0;

width: auto;

height: auto; ( Nếu ko có thì giá trị width và height bị fixed với giá trị khởi tạo ban đầu )

## Control Layer in Position

position: relative;

z-index:1;

position: fixed:

+ Hoạt động dựa vào body chứ không phụ thuộc vào phần tử cha
+ không hoạt động tốt với phần tử cha đang dùng : transform translate

## Before and after

if content of before/after is blank, custom box is can be used in both of before and after

Currentcolor: lấy màu theo màu chữ ở thuộc tính phía trước.

With transition:

.effect{

    text-decoration: none;

    display: inline-block;

    padding: 2rem;

    text-align: center;

    background-color: white;

    border: 1pxsolidorange;

    margin: 5rem;

    transition: color0.25slinear;

    position: relative;

    z-index: 1;

}

.effect:before{

    content:"";

    height: 100%;

    width: 0;

    position: absolute;

    top:0;

    right:0;

    background-color:  orange;

    z-index: -1;

    transition: width 0.25slinear;

}

.effect:hover:before{

    width : 100%

}
