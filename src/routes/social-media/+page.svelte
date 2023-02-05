<script>
    import TwitterLogo from "$lib/images/2021 Twitter logo - blue.png"
    import BandCampLogo from "$lib/images/bandcamp-logotype-color-128.png"
</script>

<div id="bigContainer">
    <div id="Title">
        How to Connect
    </div>
    <div>
        <a href="https://wfrecs.bandcamp.com/"><img src={BandCampLogo} alt="Twitter" width="200px" height="100px"></a>
        <a href="https://twitter.com/WF_Recordings"><img src={TwitterLogo} alt="Twitter" width="200px" height="200px"></a>
        <a href="/">Personal Website</a>
    </div>
    
</div>

<style>
    #bigContainer{
        display: flex;
        height: 100vh;
        vertical-align: center;
        margin-top: 50px;
        justify-content: center;
        align-self: center;
        align-items: center;
        flex-flow: column;
    }
    #Title{
        width: 100%; 
        text-align: center;
    }

</style>