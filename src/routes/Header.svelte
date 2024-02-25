<script>
    import Sitename from "../components/header/Sitename.svelte";
    import Gameinfo from "../components/header/Gameinfo.svelte";
    import Profile from "../components/header/Profile.svelte";
</script>

<div id="main">
    <div id="name">
        <Sitename />
    </div>
    <div class="temp"></div>
    <div id="panel">
        <div id="gameinfo"><Gameinfo /></div>
        <div id="profile"><Profile /></div>
    </div>
</div>

<style>
    #main{
        display: flex;
        flex-direction: row;
        height: 100%;
            
    }
    .temp{
        flex-grow: 1;
    }
    #name {
        width: 25vw;
        background-color: violet;
    }
    #panel {
        width: 40vw;
        display: flex;
    }
    #gameinfo {
        width: 20vw;
    }
    #profile {
        width: 20vw;
    }
</style>