<script>
    import Chatelement from "./elements/Chatelement.svelte";
</script>

<div id="main">
    <div id="card">
        <div id="heading">Chat Room</div>
        <div id="games">

            <Chatelement name={'Games'} active={15}/>
            <Chatelement name={'Music'} active={50}/>
            <Chatelement name={'Movies'} active={15}/>
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
        height: 80%;
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
