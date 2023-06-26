<template>
  <div className="My_portfolio gmarket5">
    <h1>portfolio</h1>
    <iframe src="https://portfolio-45429.web.app/" title="내용"></iframe>
  </div>
  <div className="minbox_title">
    <h2>포트폴리오 참고 사이트</h2>
  </div>
  <div className="port_minbox">
    <div className="portbox_title1">
      <a href="https://www.awwwards.com/websites/portfolio/">
        awwwards<em> .com</em>
      </a>
    </div>
    <div className="portbox1">
      <a href="https://wantedfornothing.com/">
        <img src="../assets/images/portfolio/portimg1.png" alt="포트폴리오1" />
      </a>
    </div>
    <div className="portbox1">
      <a href="https://katsuakiutsunomiya.com/">
        <img src="../assets/images/portfolio/portimg2.png" alt="포트폴리오2" />
      </a>
    </div>
    <div className="portbox1">
      <a href="https://www.artembui.pro/">
        <img src="../assets/images/portfolio/portimg3.png" alt="포트폴리오3" />
      </a>
    </div>
    <div className="portbox_title2">
      <a
        href="https://webflow.com/tag/portfolio-websites?utm_source=google&utm_medium=search&utm_campaign=SS-GS-NB-DynamicSearchAds-Global&utm_term=dsa-1480385100845___617245336966___ss_paid-bb&gclid=Cj0KCQjw4s-kBhDqARIsAN-ipH2zb5XUQo0u3ChFGzTOwS0pDxOlENSCmkDQ2B7TZG0bR4uG1A_trsAaAmY3EALw_wcB"
      >
        webflow<em> .com</em>
      </a>
    </div>
    <div className="portbox1">
      <a href="https://az-boston.webflow.io/">
        <img src="../assets/images/portfolio/portimg4.png" alt="포트폴리오4" />
      </a>
    </div>
    <div className="portbox1">
      <a href="https://az-istanbul.webflow.io/">
        <img src="../assets/images/portfolio/portimg5.png" alt="포트폴리오5" />
      </a>
    </div>
    <div className="portbox1">
      <a href="https://devfolio-5eb48a.webflow.io/">
        <img src="../assets/images/portfolio/portimg6.png" alt="포트폴리오6" />
      </a>
    </div>
  </div>
</template>

<style lang="scss">
.My_portfolio {
  width: 80%;
  height: 80vh;
  margin: 0 auto;
  font-size: 5vw;
  color: #f5efe7;
  text-align: center;
  margin-bottom: 100px;

  h1 {
    font-size: 5vw;
    margin-top: 100px;
    margin-bottom: 100px;
    text-transform: uppercase;
  }

  iframe {
    width: 100%;
    height: 100%;
  }
}
.minbox_title {
  h2 {
    font-family: "GmarketSans";
    font-weight: 400;
    font-size: 50px;
    color: #f5efe7;
    padding-top: 200px;
    padding-bottom: 100px;
    text-align: center;
  }
}
.port_minbox {
  font-family: "GmarketSans";
  width: 80%;
  height: 1000px;
  margin: 0 auto;
  display: flex;
  flex-wrap: wrap;
  position: relative;
  .portbox_title1 a {
    font-size: 28px;
    color: #f5efe7;
    position: absolute;
    top: 0;
    left: 0;
    padding-left: 5px;
    em {
      color: #6d6d6d8f;
    }
  }
  .portbox_title2 a {
    font-size: 28px;
    color: #f5efe7;
    position: absolute;
    top: 500px;
    left: 0;
    padding-left: 5px;
    em {
      color: #6d6d6d8f;
    }
  }

  .portbox1 {
    margin: 50px auto 0 auto;
    width: 32.2222%;
    height: 300px;
    border: 1px solid #000;
    background-color: #fff;

    img {
      width: 100%;
      height: 100%;
    }
  }
}
</style>
