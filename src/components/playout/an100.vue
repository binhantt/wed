<template>
    <div>
        <div>
            <div class="an100">
                <ul class="an100-1"> 
                     <li><a href="">kiến thức</a>
                        <ul class="an100-1-1">
                            <li><a href="">toán</a></li>
                            <li><a href="">lí</a></li>
                            <li><a href="">hóa</a></li>
                            <li><a href="">sinh</a></li>
                            <li><a href="">sữ</a></li>
                            <li><a href="">địa</a></li>
                            <li><a href="">tiếng anh</a></li>
                            <li><a href="">ngữ văn</a></li>
                        </ul>
                    </li>
                    <li><a href="">trang chu </a></li>
                 
                  
                    
                    <li><a href=""> hỗ trợ</a></li>
                    <li><a href=""> đăng kí /đăng nhập</a></li> 
                  <li><a href=""> thi môn </a></li>
                </ul>
            </div>
        </div>
    </div>
</template>
<style>
 li {
 list-style: none;
}
a{
    text-decoration: none;
}
.an100-1{
    background: linear-gradient(180deg, #CD2929 0%, rgba(184, 61, 61, 0) 100%);
    height: 50px;
}
.an100-1 a{
    color: black;
    font-size: 20px;
    font-family: Inter;

}
ul.an100-1-1 {
   display: none;
   position: absolute;
   width: 200px;
   height: 800px;
   border: 1 solid none;
   background:rgb(159, 77, 77);
   padding: 0%;
   text-align: center;
   top: 42px;
   left: 0%;

}
ul.an ul.an100-1-1:hover{
 display: block;
}

.an100-1{
    display: flex;
    justify-content: space-around;
    margin: 0%;
    align-items: center;
    padding: 0%;
    
}

</style>
<script>
export default{
    name:"an100"
}
</script>
