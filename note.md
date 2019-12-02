non mi ricordo mai come inserire le immagini.
il codice è questo:
<div class="outer">
<figure>
  <img src="" alt="">
  <figcaption></figcaption>
</figure>
</div>

e il css è

hugo new post/.md

il rosso
<span class="rosso">
e il css corrispondente
<style>
body { background-color:white; }
.rosso {color:#e6005c; }
p { background-color:#FFFFFF; }
</style>

figure {
  display: inline-block;
  text-align: center;
  font-style: italic;
  font-size: small;
  margin: 5px; /* adjust as needed */
}
figure img {
  vertical-align: top;
}
figure figcaption {

}

.outer {
  display: block;
  text-align: center;
}
