<div id="main">
    <div id="logo">logo</div>
    <div id="name">Name</div>
</div>

<style>
    #main{
        height: 100%;
        width: 100%;
        display: flex;
        align-items: end;
        justify-content: end;
        font-size: 32px;
    }
    @media screen and (max-width: 700px){
        #name {
            visibility: hidden;
            width: 0%;
        }        
    }
    
</style>