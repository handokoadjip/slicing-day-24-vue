<template>
  <section>
    <div className="container">
      <div className="row min-vh-50">
        <div className="col-lg-6 py-3" v-for="(list, index) in lists" :key="index" :id="list.name">
          <figure className="m-0">
            <img className="img-fluid w-100 h-image" :src="list.image" :alt="list.name" />
          </figure>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "ContentComponent",
  data() {
    return {
      lists: [
        {
          image: require("@/assets/source/image/img-1.jpg"),
          name: "image-1",
        },
        {
          image: require("@/assets/source/image/img-2.jpg"),
          name: "image-2",
        },
        {
          image: require("@/assets/source/image/img-3.jpg"),
          name: "image-3",
        },
        {
          image: require("@/assets/source/image/img-4.jpg"),
          name: "image-4",
        },
        {
          image: require("@/assets/source/image/img-5.png"),
          name: "image-5",
        },
        {
          image: require("@/assets/source/image/img-6.jpg"),
          name: "image-6",
        },
        {
          image: require("@/assets/source/image/img-7.png"),
          name: "image-7",
        },
        {
          image: require("@/assets/source/image/img-8.jpg"),
          name: "image-8",
        },
      ]
    }
  }
}
</script>