<template>
  <div class="cakes">
    <h1>Our Cakes</h1>
    <div id="header">
      <header>
        <h1>Cake Gallery</h1>
      </header>
      <div class="cake-container">
        <div v-for="cake in cakes" :key="cake.id">
          <!-- <h2>{{ cake.name }}</h2> -->
          <img
            :src="cake.image"
            alt="cake"
            class="cakes"
            height="300"
            width="300"
          />
          <p>{{ cake.description }}</p>
          <p>{{ cake.price }}</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import cake1 from "../assets/Cakes/cake1.avif";
import cake2 from "../assets/Cakes/cake2.avif";
import cake3 from "../assets/Cakes/cake3.avif";
import cake4 from "../assets/Cakes/cake4.avif";
import cake5 from "../assets/Cakes/cake5.avif";
import cake6 from "../assets/Cakes/cake6.avif";
import cake7 from "../assets/Cakes/cake7.avif";
import cake8 from "../assets/Cakes/cake8.avif";
import cake9 from "../assets/Cakes/cake9.avif";
import cake10 from "../assets/Cakes/cake10.avif";
import cake11 from "../assets/Cakes/cake11.avif";
import cake12 from "../assets/Cakes/cake12.avif";
import cupcake1 from "../assets/Cakes/cupcake1.avif";
import cupcake2 from "../assets/Cakes/cupcake2.avif";
import cupcake3 from "../assets/Cakes/cupcake3.avif";
import cupcake4 from "../assets/Cakes/cupcake4.avif";
import cupcake5 from "../assets/Cakes/cupcake5.avif";
import cupcake6 from "../assets/Cakes/cupcake6.avif";
import cupcake7 from "../assets/Cakes/cupcake7.avif";
import cupcake8 from "../assets/Cakes/cupcake8.avif";
import cupcake9 from "../assets/Cakes/cupcake9.avif";
import cupcake10 from "../assets/Cakes/cupcake10.avif";
import cupcake11 from "../assets/Cakes/cupcake11.avif";
import cupcake12 from "../assets/Cakes/cupcake12.avif";


export default {
  data() {
    return {
      cakes: [
        {
          id: 1,
          name: "Cake 1",
          image: cake1,
          description: "This is cake 1",
          price: 10,
        },
        {
          id: 2,
          name: "Cake 2",
          image: cake2,
          description: "This is cake 2",
          price: 20,
        },
        {
          id: 3,
          name: "Cake 3",
          image: cake3,
          description: "This is cake 3",
          price: 30,
        },
        {
          id: 4,
          name: "Cake 4",
          image: cake4,
          description: "This is cake 4",
          price: 40,
        },
        {
          id: 5,
          name: "Cake 5",
          image: cake5,
          description: "This is cake 5",
          price: 50,
        },
        {
          id: 6,
          name: "Cake 6",
          image: cake6,
          description: "This is cake 6",
          price: 60,
        },
        {
          id: 7,
          name: "Cake 7",
          image: cake7,
          description: "This is cake 7",
          price: 70,
        },
        {
          id: 8,
          name: "Cake 8",
          image: cake8,
          description: "This is cake 8",
          price: 80,
        },
        {
          id: 9,
          name: "Cake 9",
          image: cake9,
          description: "This is cake 9",
          price: 90,
        },
        {
          id: 10,
          name: "Cake 10",
          image: cake10,
          description: "This is cake 10",
          price: 100,
        },
        {
          id: 11,
          name: "Cake 11",
          image: cake11,
          description: "This is cake 11",
          price: 110,
        },
        {
          id: 12,
          name: "Cake 12",
          image: cake12,
          description: "This is cake 12",
          price: 120,
        },
        {
          id: 13,
          name: "Cupcake 1",
          image: cupcake1,
          description: "This is cupcake 1",
          price: "10,000",
        },
        {
          id: 14,
          name: "Cupcake 2",
          image: cupcake2,
          description: "This is cupcake 2",
          price: "20,000",
        },
        {
          id: 15,
          name: "Cupcake 3",
          image: cupcake3,
          description: "This is cupcake 3",
          price: "30,000",
        },
        {
          id: 16,
          name: "Cupcake 4",
          image: cupcake4,
          description: "This is cupcake 4",
          price: "40,000",
        },
        {
          id: 17,
          name: "Cupcake 5",
          image: cupcake5,
          description: "This is cupcake 5",
          price: "50,000",
        },
        {
          id: 18,
          name: "Cupcake 6",
          image: cupcake6,
          description: "This is cupcake 6",
          price: "60,000",
        },
        {

          id: 19,
          name: "Cupcake 7",
          image: cupcake7,
          description: "This is cupcake 7",
          price: "70,000",
        },
        {
          id: 20,
          name: "Cupcake 8",
          image: cupcake8,
          description: "This is cupcake 8",
          price: "80,000",
        },
        {
          id: 21,
          name: "Cupcake 9",
          image: cupcake9,
          description: "This is cupcake 9",
          price: "90,000",
        },
        {
          id: 22,
          name: "Cupcake 10",
          image: cupcake10,
          description: "This is cupcake 10",
          price: "100,000",
        },
        {
          id: 23,
          name: "Cupcake 11",
          image: cupcake11,
          description: "This is cupcake 11",
          price: "110,000",
        },
        {
          id: 24,
          name: "Cupcake 12",
          image: cupcake12,
          description: "This is cupcake 12",
          price: "120,000",
        }
      ],
    };
  },
};
</script>
<style scoped>
.cake-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
  align-items: center;
  align-content: center;
  margin: 0 auto;
  padding: 0 20px;
}
.cakes {
  border-radius: 10px;
}
h1 {
  color: white;
}
@media (max-width: 768px) {
  .cake-container {
    display: grid;
    grid-template-columns: repeat(1fr, 1fr);
    justify-items: center;
    align-items: center;
    grid-gap: 20px;
  }
  .cakes {
    width: 200px;
    height: 200px;
    display: inline;
  }
}
</style>
