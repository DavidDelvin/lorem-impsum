<template>
  <div class="container">
    <h1>Welcome to Ipsum Generator</h1>
    <form class="lipsum-form">
      <input type="text" id="lipsum-input" name="lipsum-input" placeholder="Enter amount...">
      <div class="sentence">
        <input type="radio" name="words" id="sentence-input" checked>
        <label for="sentence-input">Sentence(s)</label>
      </div>
      <div class="paragraph">
        <input type="radio" name="words" id="paragraph-input">
        <label for="sentence-input">Paragraph(s)</label>
      </div>
    </form>
    <button type="submit" class="submit-lipsum">Generate</button>

    <div class="ipsum-body">
      <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Facere provident autem magni iste sunt. Quis est aperiam temporibus fugit? Quasi eos fuga ducimus. Quidem reiciendis animi consequatur non porro illo aspernatur quo deserunt. Nobis laboriosam repellat porro debitis, aliquam sequi perferendis? Consequatur, optio ab similique exercitationem quo praesentium odit est!</p>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.container {
  margin-top: 4rem;
}

.lipsum-form {
  display: flex;
  justify-content: center;
  margin-top: 3rem;
}

.lipsum-form .sentence,
.lipsum-form .paragraph {
  margin-left: 1rem;
}

.submit-lipsum {
  margin-top: 2rem;
  padding: 0.6rem 1.2rem;
  font-size: 1.2rem;
  border-radius: 5px;
  background: #000;
  color: #fff;
  outline: none;
  border: none;
  cursor: pointer;
}

.ipsum-body {
  margin-top: 3rem;
}
</style>
