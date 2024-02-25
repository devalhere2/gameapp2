<script>
    export let name = 'Temp';

</script>

<div id="main">
    <div id="name">{name}</div>
    
</div>

<style>
    #main{
        display: flex;
        width: 100%;
        background-color: grey;
        height: 50px;
        align-items: center;
    }
    #name{
        flex-grow: 1;
        padding-left: 10px
    }
</style>