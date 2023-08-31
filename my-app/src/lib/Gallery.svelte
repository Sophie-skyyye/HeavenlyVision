<div class="outer">
    <div class="imgboxs"><img src="img/img1.jpg"></div>
    <div class="imgboxs"><img src="img/img2.jpg"></div>
    <div class="imgboxs"><img src="img/img3.jpg"></div>
</div>

<div class="outer">    
    <div class="imgboxs"><img src="img/img4.jpg"></div>
    <div class="imgboxs"><img src="img/img5.jpg"></div>
    <div class="imgboxs"><img src="img/img6.jpg"></div>
</div>


<style>

    *{
        box-sizing: border-box;
        margin: 0;
        
    }
    .outer{
        width: 100%;
        display:flex;
        flex-direction: row;
        justify-content: center;
    }

    .imgboxs{
        width:30%;
        display:flex;
        align-items: center;
    }
 
    .imgboxs img{
        display: flex;
        justify-content: space-evenly;
        width: 100%;
        padding: 10px;
    }

</style>