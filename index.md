
<style>
    #content h1 {
        display: none;
    }
    #content .carousel-inner,
    #content .carousel-control {
        border-radius: 10px;
    }
    #content .carousel-caption {
        padding-top: 0;
        padding-left: 20px;
        padding-right: 20px;
        background: rgba(0,0,0,0.75);
        border-radius: 10px;
        text-align: left;
    }
    #content .carousel-caption h3 {
        color: #fff;
        font-size: 26px;
}
</style>

# Forsiden

<div id="aboutCarousel" class="carousel slide">
    <ol class="carousel-indicators">
        <li data-target="#aboutCarousel" data-slide-to="0" class="active"></li>
        <li data-target="#aboutCarousel" data-slide-to="1"></li>
        <li data-target="#aboutCarousel" data-slide-to="2"></li>
        <li data-target="#aboutCarousel" data-slide-to="3"></li>
    </ol>

    <div class="carousel-inner">
        <div class="item active">
            <img src="img/slide1.jpg" />
            <div class="carousel-caption">
                <h3>Hvorfor</h3>
                <p>
                Vår tid er unik. Like mye som den er kompleks er den også
                heftet med enorme utfordringer. Selv om det finnes mange som
                jobber for å fremme nye perspektiver, nye verdier og nye
                løsninger kan det virke som utviklingen ubønnhørlig drar i fra
                oss.
                </p>
            </div>
        </div>
        <div class="item">
            <img src="img/slide2.jpg" />
            <div class="carousel-caption">
                <h3>Ulike arenaer, samme mål</h3>
                <p>
                Bak ordet samfunnsomlafting står tanken om at alt filantropisk
                arbeid hører sammen. Utfordringer innenfor sosial
                rettferdighet, demokratisk inkludering, økologi, bærekraftig
                ressursforvaltning og naturvern kretser rundt like verdier og
                forståelse av samfunn.
                </p>
            </div>
        </div>
        <div class="item">
            <img src="img/slide3.jpg" />
            <div class="carousel-caption">
                <h3>Samarbeid og samhold</h3>
                <p>
                Foreningen for samfunnsomlafting sitt formål er derfor å fremme
                samarbeid og samhold mellom privatpersoner, organisasjoner og
                foretak som aktivt jobber for samfunnsendringer av filantropisk
                art.
                </p>
            </div>
        </div>
        <div class="item">
            <img src="img/slide4.jpg" />
            <div class="carousel-caption">
                <h3>Foreningen</h3>
                <p>
                Foreningen for samfunnsomlafting er en ideell, livsynsnøytral
                og partipolitisk uavhengig interesseorganisasjon for
                enkeltindivider som jobber for en bedre fremtid.
                </p>
            </div>
        </div>
    </div>

    <a class="left carousel-control" href="#aboutCarousel" data-slide="prev">
        <span class="icon-prev"></span>
    </a>
    <a class="right carousel-control" href="#aboutCarousel" data-slide="next">
        <span class="icon-next"></span>
    </a>
</div>

<script>
$(document).ready(function() {
    $('#aboutCarousel').carousel();
});
</script>
