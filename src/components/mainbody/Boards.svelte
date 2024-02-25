<script>
    import Gameelement from "./elements/Gameelement.svelte";
</script>

<div id="main">
    <div id="card">
        <div id="heading">Board Games</div>
        <div id="games">
            <Gameelement name={'Chess'} playing={15}/>
            <Gameelement name={'LUDO'} playing={50}/>
            <Gameelement name={'Checkers'} playing={15}/>
            
        </div>
    </div>
</div>

<style>
    #main {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        height: 100%;
    }
    #card {
        border: 1px solid red;
        border-radius: 20px;
        height: 50%;
        width: 80%;
        padding: 20px;
    }
    #heading{
        height: 10%;
        display: flex;
        align-items: center;
        text-decoration: underline;
        font-size: 18px;
        color: magenta;
    }
    #games{
        height: 90%;
        overflow-y: auto;
        overflow-x: hidden;
    }
</style>
