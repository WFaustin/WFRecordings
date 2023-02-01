<script>
    import TopNavbar from "./top-navbar.svelte";
</script>
<div id="head">
    <TopNavbar></TopNavbar>
</div>
<div id="body">
    <section id="titleSection">
        <div>
            <h1>WF Recordings</h1>
            <p>
                Committed to providing musical services all across the globe.
            </p>
        </div>

    </section>
    
</div>

<style>
    *{
        box-sizing: border-box;
        font-family:Verdana, Geneva, Tahoma, sans-serif;
        margin: 0px; 
        padding: 0px;
    }

    p{
        font-style: italic;
    }
    #titleSection{
        height: 100vh;
        background: #56DAFC;
    }
</style>