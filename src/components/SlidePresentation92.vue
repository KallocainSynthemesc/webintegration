<template>
  <div class="slide">
    <div class="heading">Extra Markup - Escape Characters</div>
    <div class="content">
      <p>
        Certains caractères sont utilisés dans et réservés par le code HTML.
      </p>
      <br />
      <div class="escape-container">
        <div class="Less-than-sign">
          <div class="flex-container" style="width: 40%">
            <div style="width: 45%">
              <span>&lt;</span>
            </div>
            <div style="width: 45%">
              <p>&amp;lt;</p>
              <p>&amp;#60;</p>
            </div>
          </div>
        </div>
        <div class="Cent-sign">
          <div class="flex-container" style="width: 40%">
            <div style="width: 45%">
              <span>¢</span>
            </div>
            <div style="width: 45%">
              <p>&amp;cent;</p>
              <p>&amp;#162;</p>
            </div>
          </div>
        </div>
        <div class="Left-single-quote">
          <div class="flex-container" style="width: 40%">
            <div style="width: 45%">
              <span>&#8216;</span>
            </div>
            <div style="width: 45%">
              <p>&amp;lsquo;</p>
              <p>&amp;#8216;</p>
            </div>
          </div>
        </div>
        <div class="Greater-than-sign">
          <div class="flex-container" style="width: 40%">
            <div style="width: 45%">
              <span>></span>
            </div>
            <div style="width: 45%">
              <p>&amp;gt;</p>
              <p>&amp;amp;</p>
            </div>
          </div>
        </div>
        <div class="Pound-sign">
          <div class="flex-container" style="width: 40%">
            <div style="width: 45%">
              <span>£</span>
            </div>
            <div style="width: 45%">
              <p>&amp;pound;</p>
              <p>&amp;#163;</p>
            </div>
          </div>
        </div>
        <div class="Right-single-quote">
          <div class="flex-container" style="width: 40%">
            <div style="width: 45%">
              <span>&#8217;</span>
            </div>
            <div style="width: 45%">
              <p>&amp;rsquo;</p>
              <p>&amp;#8217;</p>
            </div>
          </div>
        </div>
        <div class="Ampersand">
          <div class="flex-container" style="width: 40%">
            <div style="width: 45%">
              <span>&amp;</span>
            </div>
            <div style="width: 45%">
              <p>&amp;amp;</p>
              <p>&amp;#38;</p>
            </div>
          </div>
        </div>
        <div class="Yen-sign">
          <div class="flex-container" style="width: 40%">
            <div style="width: 45%">
              <span>¥</span>
            </div>
            <div style="width: 45%">
              <p>&amp;yen;</p>
              <p>&amp;#165;</p>
            </div>
          </div>
        </div>
        <div class="Left-double-quotes">
          <div class="flex-container" style="width: 40%">
            <div style="width: 45%">
              <span>“</span>
            </div>
            <div style="width: 45%">
              <p>&amp;ldquo;</p>
              <p>&amp;#8220;</p>
            </div>
          </div>
        </div>
        <div class="Quotation-mark">
          <div class="flex-container" style="width: 40%">
            <div style="width: 45%">
              <span>"</span>
            </div>
            <div style="width: 45%">
              <p>&amp;quot;</p>
              <p>&amp;#34;</p>
            </div>
          </div>
        </div>
        <div class="Euro-sign">
          <div class="flex-container" style="width: 40%">
            <div style="width: 45%">
              <span>€</span>
            </div>
            <div style="width: 45%">
              <p>&amp;euro;</p>
              <p>&amp;#8364;</p>
            </div>
          </div>
        </div>
        <div class="Right-double-quotes">
          <div class="flex-container" style="width: 40%">
            <div style="width: 45%">
              <span>”</span>
            </div>
            <div style="width: 45%">
              <p>&amp;rdquo;</p>
              <p>&amp;#8221;</p>
            </div>
          </div>
        </div>
        <div class="Copyright-symbol">
          <div class="flex-container" style="width: 40%">
            <div style="width: 45%">
              <span>©</span>
            </div>
            <div style="width: 45%">
              <p>&amp;copy;</p>
              <p>&amp;#169;</p>
            </div>
          </div>
        </div>
        <div class="Multiplication-sign">
          <div class="flex-container" style="width: 40%">
            <div style="width: 45%">
              <span>&times;</span>
            </div>
            <div style="width: 45%">
              <p>&amp;times;</p>
              <p>&amp;#215;</p>
            </div>
          </div>
        </div>
        <div class="Registered-trademark">
          <div class="flex-container" style="width: 40%">
            <div style="width: 45%">
              <span>®</span>
            </div>
            <div style="width: 45%">
              <p>&amp;reg;</p>
              <p>&amp;#174;</p>
            </div>
          </div>
        </div>
        <div class="Division-sign">
          <div class="flex-container" style="width: 40%">
            <div style="width: 45%">
              <span>÷</span>
            </div>
            <div style="width: 45%">
              <p>&amp;divide;</p>
              <p>&amp;#247;</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.escape-container {
  display: grid;
  margin-left: 10%;
  grid-template-columns: 1fr 1fr 1fr 1fr;
  grid-template-rows: 1fr 1fr 1fr 1fr;
  gap: 3% 3%;
  grid-template-areas:
    "Less-than-sign Cent-sign Left-single-quote Greater-than-sign"
    "Pound-sign Right-single-quote Ampersand Yen-sign"
    "Left-double-quotes Quotation-mark Euro-sign Right-double-quotes"
    "Copyright-symbol Multiplication-sign Registered-trademark Division-sign";
}

.escape-container div span {
  font-size: 3.5rem;
  color: #db290eff;
}

.escape-container div:hover {
  transform: scale(1.2);
}

.escape-container div {
  transition: all 0.2s ease-in-out;
}
.Less-than-sign {
  grid-area: Less-than-sign;
}
.Cent-sign {
  grid-area: Cent-sign;
}
.Left-single-quote {
  grid-area: Left-single-quote;
}
.Greater-than-sign {
  grid-area: Greater-than-sign;
}
.Pound-sign {
  grid-area: Pound-sign;
}
.Right-single-quote {
  grid-area: Right-single-quote;
}
.Ampersand {
  grid-area: Ampersand;
}
.Yen-sign {
  grid-area: Yen-sign;
}
.Left-double-quotes {
  grid-area: Left-double-quotes;
}
.Quotation-mark {
  grid-area: Quotation-mark;
}
.Euro-sign {
  grid-area: Euro-sign;
}
.Right-double-quotes {
  grid-area: Right-double-quotes;
}
.Copyright-symbol {
  grid-area: Copyright-symbol;
}
.Multiplication-sign {
  grid-area: Multiplication-sign;
}
.Registered-trademark {
  grid-area: Registered-trademark;
}
.Division-sign {
  grid-area: Division-sign;
}
</style>
