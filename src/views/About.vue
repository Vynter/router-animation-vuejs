<template>
  <div class="about page">
    <div class="layout">
      <h1>This is an about page</h1>
      <div class="circle"></div>

      <p>
        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Blanditiis
        officia aut quae repellat ullam doloribus harum aliquam tenetur
        molestias, quasi accusamus alias fuga veniam minima eos deleniti
        delectus ex aperiam. Voluptas tempora necessitatibus omnis distinctio
        deleniti aliquam numquam dolor cupiditate fugit quasi. Alias odit
        voluptates quam dicta error repellendus quos totam voluptatibus officia
        amet aspernatur repudiandae, illo repellat recusandae eum. Quae
        voluptatem, repellat laborum explicabo ad saepe itaque recusandae.
        Distinctio ipsam dolores illo voluptatibus, ea dolore, maxime modi nisi
        sint ipsum similique beatae ab impedit nemo molestiae libero? Vero, ab.
        Est, ut accusantium saepe praesentium recusandae, odit assumenda ducimus
        aliquam modi eveniet facere dicta at mollitia beatae! Similique nesciunt
        quis blanditiis ducimus atque quisquam quia itaque ullam. Qui, deleniti
        optio. Iure fugiat aut fugit id blanditiis nesciunt voluptates
        repellendus sunt. Voluptate expedita sunt perferendis. Quidem, modi,
        officiis fuga cupiditate tempore, numquam atque consequuntur sapiente
        dicta alias at placeat! Ratione, laborum!
      </p>
    </div>
  </div>
</template>

<style scoped>
.layout {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);

  padding: 5px;
  border-radius: 10px;
  box-shadow: 0 15px 50px rgba(0, 0, 0, 0.2);
  height: 90%;
  width: 90%;
}

.circle {
  width: 200px;
  background: url("https://static.wixstatic.com/media/0e963a_93643e3ea541417eb87daaad143bcc7c~mv2.jpg/v1/fill/w_498,h_498,al_c,q_50,usm_0.66_1.00_0.01/0e963a_93643e3ea541417eb87daaad143bcc7c~mv2.jpg");
  height: 200px;
  background-size: 100% 100%;
  border-radius: 50%;
  float: left;
  shape-outside: circle();
  margin: 20px;
}
p {
  text-align: justify;
}
.about {
  background: red;
}
</style>
