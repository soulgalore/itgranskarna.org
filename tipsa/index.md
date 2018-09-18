---
layout: default
title: Skicka in din berättelse nu!
description: Du gör skillnad, hjälp oss att på hur IT egentligen byggs is Sverige.
keywords: it, teknik, offentlig, upphandling
---


 <section id="promo" class="promo section offset-header">
        <div class="container text-center">
        <h1 class="title tips">Tipsa oss om knas i IT Sverige!</h1>
            <p class="intro">Fuskas det i offentliga upphandlingar? Ser din chef till att ert företag lurar pengar av kommun/landsting/stat? Byggs det helknasiga lösningar för en massa miljoner? Tipsa oss om det. Du är anonym. Vi publicerar din berättelse.</p>
        </div>
    </section>

 
<section id="tips" class="docs section">  
<div class="container">  
<div class="docs-inner">
<p>Du kan tipsa oss antingen genom formuläret nedan eller via <a href="mailto:tipsa@itgranskarna.org">tipsa@itgranskarna.org</a>. Om du behöver sända oss dokument använd <a href="https://send.firefox.com/">https://send.firefox.com/</a> och lägg till länkarna till dokumenten i formuläret.</p>

<form name="tipsa" method="POST" action="/tack/" netlify>
  <div class="form-group row">
    <label for="inputName" class="col-form-label col-form-label-lg">Namn/alias: </label>
      <input type="text" class="form-control form-control-lg" name="alias" id="inputName" placeholder="Namn">
  </div>
  <div class="form-group row">
    <label for="inputName" class="col-form-label col-form-label-lg">E-post: </label>
      <input type="email" class="form-control form-control-lg" name="epost" id="inputName" placeholder="Vi behöver kunna kontakta dig">
  </div>
  <div class="form-group row">
    <label for="exampleFormControlTextarea1" class="col-form-label col-form-label-lg">Skriv din historia här:</label>
    <textarea class="form-control form-control-lg" id="textArea" name="tips" rows="10"></textarea>
  </div>
    <div data-netlify-recaptcha></div>
  <div class="form-group row">
    <div>
      <button type="submit" class="btn btn-primary btn-lg">Skicka tips</button>
    </div>
  </div>
</form>
</div>
  </div>
</section>
   