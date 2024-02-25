<script>
    import Boards from "../components/mainbody/Boards.svelte";
    import Leader from "../components/mainbody/Leader.svelte";
    import Chat from "../components/mainbody/Chat.svelte";
    import Cards from "../components/mainbody/Cards.svelte";
</script>

<div id="main">
    <div id="game">
        <div id="cards"><Cards /></div>
        <div id="boards"><Boards /></div>
    </div>
    <div id="people">
        <div id="chat"><Chat /></div>
        <div id="leader"><Leader /></div>
        
    </div>
</div>

<style>
    #main {
        display: flex;
        height: 100%;
    }
    #game {
        display: flex;
        width: 70vw;
        height: 100%;
    }
    #people {
        display: flex;
        flex-direction: column;
        width: 30vw;
        height: 100%;
    }
    #cards {
        width: 35vw;
        height: 100%;
    }
    #boards {
        width: 35vw;
        height: 100%;
    }
    #leader {
        width: 30vw;
        height: 50%;
    }
    #chat {
        width: 30vw;
        height: 50%;
    }

    
</style>
