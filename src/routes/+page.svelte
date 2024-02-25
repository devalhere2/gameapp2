<script>
    import Header from "./Header.svelte";
    import Footer from "./Footer.svelte";
    import Mainbody from "./Mainbody.svelte";

</script>

<div id="main">
    <div class="header">
        <Header />
    </div>
    <div class="mainbody">
        <Mainbody />
    </div>
    <div class="footer">
        <Footer />
    </div>
</div>

<style>
    :global(body) {
        box-sizing: border-box;
        margin: 0;
        padding: 0;
        font-family: 'Courier New', Courier, monospace;
    }
    #main{
        display: flex;
        flex-direction: column;
        height: 100vh;
    }
    .mainbody{
        flex-grow: 1;
    }
    .header{
        height: 60px;
    }
    .footer {
        height: 25px;
        display: flex;
        justify-content: center;
        align-items: center;
    }


</style>