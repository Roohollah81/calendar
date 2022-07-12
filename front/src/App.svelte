<script>
</script>

<style>
  :root {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
  }

  main {
    text-align: center;
    padding: 1em;
    margin: 0 auto;
  }

  h1 {
    color: #ff3e00;
    text-transform: uppercase;
    font-size: 4rem;
    font-weight: 100;
    line-height: 1.1;
    margin: 2rem auto;
    max-width: 14rem;
  }

  @media (min-width: 480px) {
    h1 {
      max-width: none;
    }
  }

  .cadr {
    width: 450px;
    height: 600px;
    margin: 2rem auto;
    padding: 15px;
    box-shadow: 0 1px 6px rgb(0 0 0 / 12%), 0 1px 4px rgb(0 0 0 / 24%);
  }

  .top {
    width: 450px;
    height: 130px;
    background-color: rgb(255, 255, 255);
    position: relative;
  }

  .fa {
    left: 45%;
    top: 23px;
  }

  .en {
    left: 35%;
    top: 50px;
  }

  .arab {
    left: 30%;
    top: 75px;
    color: gray;
  }

  .left {
    left: 0;
    padding: 35px !important;
  }

  .right {
    right: 0;
    padding: 35px !important;
  }

  .top > span {
    position: absolute;
    padding: 15px 5px 0 5px;
  }

  .navar {
    display: grid;
    grid-template-columns: auto auto auto auto auto auto auto;
    background-color: #575757;
    padding: 8px;
    direction: rtl;
    border-radius: 4px;
  }

  .letter {
    color: white;
    font-size: 11px;
  }

  .day {
    background-color: rgba(255, 255, 255, 0.8);
    padding: 18px;
    font-weight: bold !important;
    font-size: 22px !important;
  }

  .month {
    display: grid;
    grid-template-columns: auto auto auto auto auto auto auto;
    background-color: white;
    padding: 8px;
    direction: rtl;
  }

  .jalali {
    color: #4c4c4c;
  }

  .qamari {
    color: gray;
    font-size: 8px;
    float: left;
  }

  .miladi {
    color: gray;
    font-size: 8px;
    float: right;
    margin: 1px 0 0;
  }

  .button {
    display: inline-block;
    width: 86%;
    padding: 12px 15px !important;
    color: #fff !important;
    font-size: 14px !important;
    font-family: SDF !important;
    font-weight: bold !important;
    background: #ed1c24;
    border: 1px solid #ed1c24;
    text-shadow: none !important;
    position: relative;
    transition: all 400ms ease-in-out;
    z-index: 0;
    border-radius: 4px;
  }

</style>

<main>
  <h1>Time.ir!</h1>

  <div class="cadr">
    <div class="top">
      <span class="fa">تير 1401</span>
      <span class="en">June - July 2022</span>
      <span class="arab">ذوالقعده - ذوالحجه - ١٤٤٣</span>
      <span class="left">ماه بعد</span>
      <span class="right">ماه قبل</span>
    </div>
    <div class="navar">
      <div class="letter">ش</div>
      <div class="letter">ي</div>
      <div class="letter">د</div>
      <div class="letter">س</div>
      <div class="letter">چ</div>
      <div class="letter">پ</div>
      <div class="letter">ج</div>
    </div>
    <div class="month">
      <div class="day">
        <div class="jalali" style="color: gray;">۲۸</div>
      </div>
      <div class="day">
        <div class="jalali" style="color: gray;">۲۹</div>
      </div>
      <div class="day">
        <div class="jalali" style="color: gray;">۳۰</div>
      </div>
      <div class="day">
        <div class="jalali" style="color: gray;">۳۱</div>
      </div>
      <div class="day">
        <div class="jalali">۱</div>
        <div class="miladi">22</div>
        <div class="qamari">۲۲</div>
      </div>
      <div class="day">
        <div class="jalali">۲</div>
        <div class="miladi">23</div>
        <div class="qamari">۲۳</div>
      </div>
      <div class="day">
        <div class="jalali">۳</div>
        <div class="miladi">24</div>
        <div class="qamari">۲۴</div>
      </div>
      <div class="day">
        <div class="jalali">۴</div>
        <div class="miladi">25</div>
        <div class="qamari">۲۵</div>
      </div>
      <div class="day">
        <div class="jalali">۵</div>
        <div class="miladi">26</div>
        <div class="qamari">۲۶</div>
      </div>
      <div class="day">
        <div class="jalali">۶</div>
        <div class="miladi">27</div>
        <div class="qamari">۲۷</div>
      </div>
      <div class="day">
        <div class="jalali">۷</div>
        <div class="miladi">28</div>
        <div class="qamari">۲۸</div>
      </div>
      <div class="day">
        <div class="jalali">۸</div>
        <div class="miladi">29</div>
        <div class="qamari">۲۹</div>
      </div>
      <div class="day">
        <div class="jalali">۹</div>
        <div class="miladi">30</div>
        <div class="qamari">۳۰</div>
      </div>
      <div class="day">
        <div class="jalali">۱۰</div>
        <div class="miladi">1</div>
        <div class="qamari">۱</div>
      </div>
      <div class="day">
        <div class="jalali">۱۱</div>
        <div class="miladi">2</div>
        <div class="qamari">۲</div>
      </div>
      <div class="day">
        <div class="jalali">۱۲</div>
        <div class="miladi">3</div>
        <div class="qamari">۳</div>
      </div>
      <div class="day">
        <div class="jalali">۱۳</div>
        <div class="miladi">4</div>
        <div class="qamari">۴</div>
      </div>
      <div class="day">
        <div class="jalali">۱۴</div>
        <div class="miladi">5</div>
        <div class="qamari">۵</div>
      </div>
      <div class="day">
        <div class="jalali">۱۵</div>
        <div class="miladi">6</div>
        <div class="qamari">۶</div>
      </div>
      <div class="day">
        <div class="jalali">۱۶</div>
        <div class="miladi">7</div>
        <div class="qamari">۷</div>
      </div>
      <div class="day">
        <div class="jalali">۱۷</div>
        <div class="miladi">8</div>
        <div class="qamari">۸</div>
      </div>
      <div class="day">
        <div class="jalali">۱۸</div>
        <div class="miladi">9</div>
        <div class="qamari">۹</div>
      </div>
      <div class="day">
        <div class="jalali">۱۹</div>
        <div class="miladi">10</div>
        <div class="qamari">۱۰</div>
      </div>
      <div class="day">
        <div class="jalali">۲۰</div>
        <div class="miladi">11</div>
        <div class="qamari">۱۱</div>
      </div>
      <div class="day">
        <div class="jalali">۲۱</div>
        <div class="miladi">12</div>
        <div class="qamari">۱۲</div>
      </div>
      <div class="day">
        <div class="jalali">۲۲</div>
        <div class="miladi">13</div>
        <div class="qamari">۱۳</div>
      </div>
      <div class="day">
        <div class="jalali">۲۳</div>
        <div class="miladi">14</div>
        <div class="qamari">۱۴</div>
      </div>
      <div class="day">
        <div class="jalali">۲۴</div>
        <div class="miladi">15</div>
        <div class="qamari">۱۵</div>
      </div>
      <div class="day">
        <div class="jalali">۲۵</div>
        <div class="miladi">16</div>
        <div class="qamari">۱۶</div>
      </div>
      <div class="day">
        <div class="jalali">۲۶</div>
        <div class="miladi">27</div>
        <div class="qamari">۲۷</div>
      </div>
      <div class="day">
        <div class="jalali">۲۷</div>
        <div class="miladi">18</div>
        <div class="qamari">۱۸</div>
      </div>
      <div class="day">
        <div class="jalali">۲۸</div>
        <div class="miladi">19</div>
        <div class="qamari">۱۹</div>
      </div>
      <div class="day">
        <div class="jalali">۲۹</div>
        <div class="miladi">20</div>
        <div class="qamari">۲۰</div>
      </div>
      <div class="day">
        <div class="jalali">۳۰</div>
        <div class="miladi">21</div>
        <div class="qamari">۲۱</div>
      </div>
      <div class="day">
        <div class="jalali">۳۱</div>
        <div class="miladi">22</div>
        <div class="qamari">۲۲</div>
      </div>
    </div>
    <div>
      <span class="button">برو به امروز</span>
    </div>
  </div>
</main>
