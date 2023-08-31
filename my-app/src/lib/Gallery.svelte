<div class="outer">
    <div class="imgboxs">1</div>
    <div class="imgboxs">2</div>
    <div class="imgboxs">3</div>
</div>



<style>

    *{
        box-sizing: border-box;
        margin: 1;
        
    }
    .outer{
        width: 100%;
        display:flex;
        flex-direction: row;
    }

    .imgboxs{
        width:30%;
        display:flex;
        justify-content: space-evenly;
        justify-content: center;
        align-items: center;
    }

    .imgboxs img{
        justify-content: center;
        align-items: center;
    }

</style>