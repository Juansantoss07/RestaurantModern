<script>
export default {
  name: "TextHome",
};
</script>

<template>
  <div class="content">
    <div class="text-home">
      <div class="flavour">
        <p>Chase The New Flavour</p>
      </div>
      <div class="title">
        <h1>The Key To Fine Dining</h1>
      </div>
      <div class="desc">
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Cumque atque
          debitis et? Nostrum dolores quibusdam id nemo consequatur, unde ipsam
          exercitationem odio dicta natus soluta itaque earum obcaecati repellat
          sint!
        </p>
      </div>
      <div>
        <button class="btn-home">Explorer Menu</button>
      </div>
    </div>
  </div>
</template>

<style scoped>
.text-home {
  display: flex;
  flex-direction: column;
  justify-content: space-around;
  padding: 0 2rem;
}
.flavour p {
  color: #fff;
  font-family: "Dancing Script", cursive;
}

.title h1 {
  color: #ffa500;
  font-size: 64px;
  font-family: "Dancing Script", cursive;
  margin: 1rem 0;
}

.desc p {
  color: #fff;
}

@media(max-width:680px){
    .text-home{
        align-items: center;
        text-align: center;
        margin-bottom: 1rem;
    }
}
</style>