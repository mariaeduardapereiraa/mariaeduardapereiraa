<section class="tópicos">
   <h2> class="tópicos__titulo">TÓPICOS VISITADOS RECENTEMENTE</h2>
    <ul class="tópicos__lista">
        <li class="tópicos__item">
              <a href="#" class="tópicos__link">Android</a>
        </li>
        <li class="tópicos__item">
              <a href="#" class="tópicos__link">Marketing Digital</a>
        </li>
        </li>
        <li class="tópicos__item">
              <a href="#" class="tópicos__link">Agile</a>
        </li>
        <li class="tópicos__item">
              <a href="#" class="tópicos__link">Startups</a>
        </li>
        <li class="tópicos__item">
              <a href="#" class="tópicos__link">HTML e CSS</a>
        </li>
        <li class="tópicos__item">
              <a href="#" class="tópicos__link">OO</a>
        </li>
        <li class="tópicos__item">
              <a href="#" class="tópicos__link">Java</a>
        </li>
    </ul>
 </section>
.tópicos {
    background: var(--azul-degrade);
    text-align: center;
   padding: 1em 0;
}

.tópicos__titulo {
   color: var(--branco);
    font-weight: 300;
    margin-bottom: 1em;
}

.tópicos__lista {
   display: flex;
   flex-wrap: wrap;
   justify-content: center;
}

.tópicos__item {
   margin: 2em 0.5em;
}

.tópicos__link {
   color: var(--branco);
  padding: 1em;
  background-color: var(--laranja);
  text-decoration: none;
  font-size: 14px;
  font-weight: 700;

}
