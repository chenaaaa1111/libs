# libs
 # imgLib 文件夹下是多图上传插件 依赖jquery
 
 <script src="./../js/ImgUpLib.js"></script>
<script>
    ImgUpLib.init({el:"#imgUp",
        fileType         : ["jpg","png","bmp","jpeg"],   // 上传文件的类型
        fileSize         : 1024 * 1024 * 10,                  // 上传文件的大小 10M
        imgMaxSize:5});

    $('.save').click(function(){
        //imgarray 是点击上传时的文件数组
            console.log(')))))imgarray',ImgUpLib.imgArray);
    })
</script>
