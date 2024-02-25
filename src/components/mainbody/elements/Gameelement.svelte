<script>
    export let name = 'Temp';
    export let playing = 0;
</script>

<div id="main">
    <div id="name">{name}</div>
    <div id="playing">{playing} Playing</div>
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