<h1>Counter Javascript</h1>
<p>Questo è il 2° progetto eseguito per il Master in Sviluppo web di Start2impact.</p>

<h2>🤔 Di cosa si tratta?</h2>
<p>Si tratta di un semplice contatore reso interattivo grazie a JavaScript. L'utente può incrementare, decrementare o resettare il contatore con i relativi pulsanti.</p>

<h2>💡 Funzionalità:</h2>
<ul>
  <li><strong>Incremento:</strong> Aumenta il valore del contatore di 1.</li>
  <li><strong>Decremento:</strong> Riduce il valore del contatore di 1.</li>
  <li><strong>Reset:</strong> Riporta il valore del contatore a 0.</li>
  <li><strong>Cambio di colore:</strong> Il colore del numero cambia in base al valore del contatore (verde se è positivo, rosso se è negativo).</li>
</ul>

<h2>⚒️ Struttura del codice:</h2>
<ol>
  <li><strong>Selezione degli elementi dal DOM</strong>: ho utilizzato <code>document.querySelector</code> per ottenere gli elementi del contatore e i relativi pulsanti dal DOM.
    <ul>
      <li><code>displayContatore</code>: Mostra il valore del contatore.</li>
      <li><code>bottoneIncremento</code>, <code>bottoneDecremento</code>, <code>bottoneReset</code>: Sono i pulsanti di interazione.</li>
    </ul>
  </li>
  <li><strong>Gestione degli eventi</strong>: Con (<code>addEventListener</code>) ho gestito gli eventi per i pulsanti.
    <ul>
      <li><strong>Incremento</strong>: Incrementa il valore e aggiorna il display.</li>
      <li><strong>Decremento</strong>: Decrementa il valore e aggiorna il display.</li>
      <li><strong>Reset</strong>: Resetta il valore, tornando a 0 e aggiornando il display.</li>
    </ul>
  </li>
  <li><strong>Funzione di aggiornamento colore</strong>: La funzione <code>colore()</code> cambia il colore del numero mostrato in base al suo valore:
    <ul>
      <li>Verde se il numero è positivo.</li>
      <li>Rosso se il numero è negativo.</li>
      <li>Il colore rimane invariato se il numero è uguale a 0.</li>
    </ul>
  </li>
</ol>

<h2>👨🏻‍💻 Testa il progetto:</h2>
Basta che clicchi il link qui in basso:<br>
<a href="https://dgmichele.github.io/Counter/" rel="noopener" target="_blank">Counter JS ↗️</a>
