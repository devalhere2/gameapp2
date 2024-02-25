<script>
    export let name = 'Temp';
    export let active = 0;
</script>

<div id="main">
    <div id="name">{name}</div>
    <div id="playing">{active} Active</div>
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