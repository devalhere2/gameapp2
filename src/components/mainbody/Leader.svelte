<script>
    import Leaderelement from "./elements/Leaderelement.svelte";
</script>

<div id="main">
    <div id="card">
        <div id="heading">Leader Board</div>
        <div id="games">
            
            <Leaderelement name={'Sukesh'}/>
            <Leaderelement name={'Mukesh'}/>
            <Leaderelement name={'gukesh'}/>            
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
