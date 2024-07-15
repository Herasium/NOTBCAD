<svelte:head>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:ital,wght@0,100..800;1,100..800&display=swap" rel="stylesheet">
  <meta property="og:type" content="website" />
    <meta property="og:url" content="https://blockcoin.social" />
    <meta property="og:description" content="Wait, something has changed again ????" />
    <meta name="theme-color" content="#000000" />
    <meta name="description" content="Wait, something has changed again ????" />
</svelte:head>


<script>
  import bg_waves from "$lib/img/bg_waves.svg"
  import logo from "$lib/img/logo.svg"
</script>

<div id="bg_color" />
<img src={bg_waves} id="bg_waves" />

<div id="container">
  <img src={logo} id="logo" />
  <div id="text">
    YaY Discord Link !! #Hera
  </div>
  <a href="https://discord.gg/xhNNAJKfzq" class="button">My New Discord !</a>
  <a href="https://beta.blockcoin.social" class="button">I don't give a fuck, give me back my Blockcoin!!!!!!!11!1!1</a> 
</div>

<style>

  #text {
    margin:10px;
    font-size: 20px;
    text-align:center;
    width: 80%;
    color:#FFFFFF;
    z-index:3;
    font-family: "JetBrains Mono", monospace;
  }

  .button {
    z-index:3;
    margin: 10px;
    font-size: 20px;
    text-align:center;
    width: 80%;
    color:#FFFFFF;
    font-family: "JetBrains Mono", monospace;
  }

  #container {
    z-index:10;
    position: fixed;
    top:0;
    left:0;
    width:100%;
    height: 100%;
    display:flex;
    align-items:center;
    justify-content:center;
    flex-direction:column;
  }

  #bg_color {
    position:fixed;
    z-index: -1;
    top:0;
    left:0;
    width:100%;
    height:100%;
    background-color: #000000
  }

  #bg_waves {
    position: fixed;
    z-index:1;
    left:0;
    bottom: 0;
    height:auto;
    width:100%;
  }

</style>
