<script>
</script>

<main>
<h1>cephas is a monster lol</h1>
<div class="monster">monster</div>
<div class="webpagerecom">why not go to my other webpage:</div>
<a href="https://calc.cephas.monster">calculator</a>
<a href="https://covid.cephas.monster">covid tracker</a>
<a href="https://blog.cephas.monster">My blog</a>
<a href="https://sky.cephas.monster" class="sky">hypixel skyblock tracker(in heavy development)</a>
</main>

<style>
	main {
		text-align: center;
		margin: 0 auto;
	}
    .monster{
        background: linear-gradient(
            to right,
            #365924 0%,
            #508335 50%,
            #59ff00 100%
        );
        background-clip: text;
        font-size:20vw;
        -webkit-text-fill-color: transparent;
        -webkit-background-clip: text;
    }
    .webpagerecom{
        font-size: 3vw;
    }
    a{
        color: red;
        font-size: 3vw;
        padding-left: 5vw;
        padding-right: 5vw;
    }
    a::before{
        color: powderblue;
    }
    a::after{
        color: powderblue;
    }

    @media (max-width: 600px){
        .webpagerecom{
            font-size:5vw;
        }
        a{
            font-size:5vw;
        }
    }
    a:-webkit-any-link() {
        color: powderblue;
    }
    .sky {
                background: linear-gradient(
            to right,
            #bf00c1 0%,
            #FE5F55 50%,
            #DDD92A 90%
        );
        background-clip: text;
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
        text-decoration-line: underline;
        text-decoration-thickness: auto
    }
</style>
