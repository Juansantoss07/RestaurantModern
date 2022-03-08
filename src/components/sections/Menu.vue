<script>
export default {
  name: "Menu",
};
</script>

<template>
  <div class="content">
      <section>
            <div class="title">
      <p>Menu That Fits Your Palette</p>
      <h1>Today's Special</h1>
    </div>
    <div class="container-menus">
      <div class="box-menus">
        <div class="title-box">
            <h1>Cocktails</h1>
        </div>
        <div class="item">
          <div class="item-name">
            <h3>Chapel Hill Shiraz</h3>
            <p>AU | Battle</p>
          </div>
          <div class="item-price"><p>--------- $36</p></div>
        </div>
         <div class="item">
          <div class="item-name">
            <h3>Chapel Hill Shiraz</h3>
            <p>AU | Battle</p>
          </div>
          <div class="item-price"><p>--------- $36</p></div>
        </div>
         <div class="item">
          <div class="item-name">
            <h3>Chapel Hill Shiraz</h3>
            <p>AU | Battle</p>
          </div>
          <div class="item-price"><p>--------- $36</p></div>
        </div>
         <div class="item">
          <div class="item-name">
            <h3>Chapel Hill Shiraz</h3>
            <p>AU | Battle</p>
          </div>
          <div class="item-price"><p>--------- $36</p></div>
        </div>
         <div class="item">
          <div class="item-name">
            <h3>Chapel Hill Shiraz</h3>
            <p>AU | Battle</p>
          </div>
          <div class="item-price"><p>--------- $36</p></div>
        </div>
      </div>
      <div class="box-menus">
        <div class="title-box">
            <h1>Winne bers</h1>
        </div>
        <div class="item">
          <div class="item-name">
            <h3>Chapel Hill Shiraz</h3>
            <p>AU | Battle</p>
          </div>
          <div class="item-price"><p>--------- $36</p></div>
        </div>
         <div class="item">
          <div class="item-name">
            <h3>Chapel Hill Shiraz</h3>
            <p>AU | Battle</p>
          </div>
          <div class="item-price"><p>--------- $36</p></div>
        </div>
         <div class="item">
          <div class="item-name">
            <h3>Chapel Hill Shiraz</h3>
            <p>AU | Battle</p>
          </div>
          <div class="item-price"><p>--------- $36</p></div>
        </div>
         <div class="item">
          <div class="item-name">
            <h3>Chapel Hill Shiraz</h3>
            <p>AU | Battle</p>
          </div>
          <div class="item-price"><p>--------- $36</p></div>
        </div>
         <div class="item">
          <div class="item-name">
            <h3>Chapel Hill Shiraz</h3>
            <p>AU | Battle</p>
          </div>
          <div class="item-price"><p>--------- $36</p></div>
        </div>
      </div>
    </div>
      </section>

  </div>
</template>

<style scoped>

section{
    height: 100vh;
    width:100%;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}
.title {
  width: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

.title p {
  color: #fff;
  font-family: "Dancing Script", cursive;
}

.title h1 {
  color: #ffa500;
  font-family: "Dancing Script", cursive !important;
  font-size: 3.5em;
  text-align: center;
}

.container-menus {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 1rem 2rem;
  width: 100%;
}

.box-menus {
    display: flex;
    flex-direction: column;
    width: 45%;
    background: #000;
    padding: 1rem;
}

.title-box{
    display: flex;
    align-items: center;
    justify-content: center;
    width: 100%;
}

.title-box h1{
    font-family: "Dancing Script", cursive !important;
    color: #fff;
}

.item{
    display: flex;
    width:100%;
    justify-content: space-between;
    align-items: center;
    margin: 1rem 0;
}

.item-name h3{
    color: #ffa500;
    font-family: "Dancing Script", cursive !important;
}

.item-name p{
    color: rgba(255, 255, 255, 0.726);
}
.item-price p{
    color: #fff;
}

@media(max-width:620px){

    section{
        height: auto !important;
        margin-top: 1rem;
        padding: 2rem 0;
    }
    .container-menus{
        flex-direction: column;
    }

    .box-menus{
        width: 100%;
        margin: 0.5rem 0;
    }
}

@media(max-height:580px){
  section{
    height: auto !important;
    padding:2rem 0;
  }
}
</style>