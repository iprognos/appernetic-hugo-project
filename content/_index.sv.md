+++
title = ""
draft = false
type = "page"
keywords = [
  "OMX Stockholm",
  "Stockholmsbörsen",
  "Aktieförutsägelser",
  "Förutsägelser"
]
description = "Hitta köp eller säljlägen för nästa dag enkelt och snabbt för Stockholmsbörsen med en kombination av tekniska indikatorer och AI (deep learning)."
+++
<header>
  <section class="video v-center">
  <div id="bgVideo" class="background" ><video id="video_background" preload="auto" autoplay="autoplay" loop="loop" poster="/img/Heaven-From-Top.jpg"><source src="/Heaven-From-Top.mp4" type="video/mp4">bgvideo</video></div>
<div class="hero-unit">
    <div class="container text-left">
<h1 class="hero-title-lg dont-break-out">Aktieförutsägelser</h1>

<h2 class="title text-left dont-break-out">Hitta köp eller säljlägen snabbt med tekniska indikatorer och AI</h2>
<a class="btn btn-primary btn-lg uppercase page-scroll" href="#services">Börja här</a>


</div>
<!-- end card -->

    </div>
</div>
</section>
</header>

  <section id="services">
    <div class="container">
      <div class="row">
        <div class="col-lg-12">
          <h2 class="section-heading">iPrognos handelsstrategi</h2>
          <h3 class="section-subheading text-muted">Hitta köp eller säljlägen för nästa dag enkelt och snabbt för Stockholmsbörsen med en kombination av tekniska indikatorer och AI (djupinlärning).</h3>
          <p class="large">Välj ut köpvärda aktier i bubbeldiagrammet utifrån procentuell förändring, trend och simulerad avkastning eller sortera fram dom i tabellen. Titta närmare på simulering för vald aktie och om det ser bra ut gå vidare och lägg en köporder hos din bank.  
            
Djupinlärning används för att förutse den totala dynamiken i aktiernas pris med marginal för transaktionskostnader.
En indikator används som summerar aktiens utveckling under kommande 10 dagar.
Idén är att variabeln signalerar dagar som klart ligger över målvariationen på 2.5%.


Positivt värde på indikatorn indikerar att det är flera dagar som i medeltal är n % högre än dagens stängningskurs, vilket kan vara ett bra köp läge.
Höga negativa värden indikerar i sin tur när det är dags att sälja. </p>
        </div>
      </div>
    </div>
  </section>


  <section id="indikatorer" class="bg-light-gray page-section">
    <div class="container">
      <div class="row">
        <div class="col-lg-12">
          <h2 class="section-heading">Tekniska indikatorer och regler</h2>
          <h3 class="section-subheading text-muted">Flera olika tekniska indikatorer används för att hitta köplägen:</h3>
          <p class="large">
<strong>Bollingerbands</strong> Bollinger består av ett glidande medelvärde omgivet av två band som beror på volatiliteten i aktien. Ju mindre volatilitet desto närmare ligger banden varandra. Ju högre volatilitet desto längre är det mellan banden. Det är vanligt att aktien pendlar mellan det undre och det övre bandet. Köpa kan man göra när kursen ligger nedanför det undre och sälja när den ligger ovanför det övre bandet.</P><p class="large">
<strong>RSI</strong> är tekniska momentum-indikatorn. RSI mäter en aktiekurs relativa styrka och kan anta värden mellan 0 och 100.</p><p class="large">
<strong>CCI</strong>, commodity channel index CCI-indikatorn skapades av Donald Lambert med avsikt att identifiera cykliska trender. Tanken bakom CCI är att aktier trendar i cykler där topp- och bottennivåer noteras inom periodiska intervaller. CCI pendlar oftast inom intervallet mellan -100 och +100.</p><p class="large">
<strong>EMA</strong> 5, 10, 30 och 50 dagar (Exponential moving average). Viktat medelvärde där viktningen minskar exponentiellt för varje tidigare stapel.</p><p class="large">
<strong>PSAR</strong> Parabolic stop-and-reversal Trendindikator som används för att hitta stop-loss-nivåer. Tolkningen av denna indikator är att en köpsignal genereras när aktiekursen bryter indikatorkurvan underifrån. På motsvarande sätt genereras en säljsignal när aktiekursen bryter indikatorkurvan uppifrån. De parametrar som används i de tekniska indikatorerna kommer också att optimeras med olika sökalgoritmer för att ge högsta sharpe värde. Vid simulering med prognos läggs också den prognostiserade kursutvecklingen om två dagar tilli köp och säljsignalerna.
Vid köp ska t ex dagens prognostiserade stängningskurs vara lägre än prognostiserad kurs om 2 dagar.
Vid simulering av köp läggs också en stop trailing order som triggas om kursen faller med 10% (kan ställas in på sidan). Vid sälj triggas en order om vinsten blir 70% eller mer (kan ställas in på sidan).</p>
        </div>
      </div>
    </div>
  </section>


  <section id="prognoser">
    <div class="container">
      <div class="row">
        <div class="col-lg-12">
          <h2 class="section-heading">Uträkning av prognoser</h2>
          <h3 class="section-subheading text-muted">För att räkna ut prognostiserad kurs används k-fold korsvalidering av tidsserien för att hitta den bästa MLP (multi layer perceptron neural network) strukturen (Antal gömda lager och antal noder).</h3>
<p class="large">Strukturen väljs utifrån vilken nätverksstruktur som ger minst MSE (mean squared error). När bästa nätverkstrukturen har hittats används ett Elman neuralt nätverk med RPROP inlärningsalgoritm för att göra prognosen. </p>
        </div>
      </div>
    </div>
  </section>
  <section id="indikatorer" class="bg-light-gray page-section">
    <div class="container">
      <div class="row">
        <div class="col-lg-12">
          <h2 class="section-heading">Beta test programmet</h2>
          <h3 class="section-subheading text-muted">En webbtjänst har utvecklats (SaaS) som ger en översikt med prognoser för alla aktier på Stockholmsbörsen med interaktiva grafer. </h3>
          <p class="large">Tjänsten har utvecklats till en fungerande prototyp (MVP) och iPrognos har genomfört långtidstester som har givit mycket goda resultat. Nu behöver vi din hjälp för att göra den ännu  bättre. Så anmäl dig via formuläret till höger eller här under om du använder en mobil.</P>
        </div>
      </div>
    </div>
  </section>

  <section id="contact" class="hidden-md hidden-lg bg-light-gray">
    <div class="container">
      <div class="row">
        <div class="col-lg-12 text-center">
          <h2 class="section-heading">Anmäl dig nu!</h2>
          <h3 class="section-subheading text-muted">Vi har ett fåtal platser kvar till kölistan för beta programmet.</h3>
        </div>
      </div>
      <div class="row">
        <div class="col-lg-12">
        <div id="form-messages"></div>
          <form name="sentMessage" id="contactFormBottom" novalidate method="POST">
  		  <input type="hidden" name="Type" value="Beta program" />
            <div class="row">
              <div class="col-md-6">
                <div class="form-group"><label class="text-muted small">Namn</label>
                  <input class="form-control" name="name" placeholder="Förnamn / Efternamn" type="text" />
                </div>
                <div class="form-group"><label class="text-muted small">E-post</label>
                  <input class="form-control" name="email" placeholder="E-post" type="email" />
                </div>
              </div>
              <div class="clearfix"></div>
              <div class="col-lg-12 text-center">
                <div id="success"></div>
                <button type="submit" value="submit" class="btn btn-primary btn-md">Skicka anmälan</button>                  
              </div>
            </div>
          </form>
        </div>
      </div>
    </div>
  </section>
