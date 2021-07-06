<template>
  <div class="text-center w-full h-screen">
    <h2 class="text-3xl">Some photos</h2>

    <VueMasonryGallery :imgsArr="imgsArr" height="100%"></VueMasonryGallery>
  </div>
</template>
<script>
import VueMasonryGallery from 'vue-masonry-gallery'

export default {
  components: {
    VueMasonryGallery,
  },
  data() {
    return {
      imgsArr: [
        {
          src: 'gallery/2.jpg',
          srcBig: 'gallery/2.jpg',
          href: null,
          target: 'modal',
        },
        {
          src: 'gallery/1.jpg',
          srcBig: 'gallery/1.jpg',
          href: null,
          target: 'modal',
        },
        {
          src: 'gallery/3.jpg',
          srcBig: 'gallery/3.jpg',
          href: null,
          target: 'modal',
        },
        {
          src: 'gallery/4.jpg',
          srcBig: 'gallery/4.jpg',
          href: null,
          target: 'modal',
        },
        {
          src: 'gallery/5.jpg',
          srcBig: 'gallery/5.jpg',
          href: null,
          target: 'modal',
        },
        {
          src: 'gallery/6.jpg',
          srcBig: 'gallery/6.jpg',
          href: null,
          target: 'modal',
        },
        {
          src: 'gallery/7.jpg',
          srcBig: 'gallery/7.jpg',
          href: null,
          target: 'modal',
        },
        {
          src: 'gallery/8.jpg',
          srcBig: 'gallery/8.jpg',
          href: null,
          target: 'modal',
        },
        {
          src: 'gallery/9.jpg',
          srcBig: 'gallery/9.jpg',
          href: null,
          target: 'modal',
        },
        {
          src: 'gallery/10.jpg',
          srcBig: 'gallery/10.jpg',
          href: null,
          target: 'modal',
        },
        {
          src: 'gallery/11.jpg',
          srcBig: 'gallery/11.jpg',
          href: null,
          target: 'modal',
        },
        {
          src: 'gallery/12.jpg',
          srcBig: 'gallery/12.jpg',
          href: null,
          target: 'modal',
        },
        {
          src: 'gallery/13.jpg',
          srcBig: 'gallery/13.jpg',
          href: null,
          target: 'modal',
        },
        {
          src: 'gallery/14.jpg',
          srcBig: 'gallery/14.jpg',
          href: null,
          target: 'modal',
        },
        {
          src: 'gallery/15.jpg',
          srcBig: 'gallery/15.jpg',
          href: null,
          target: 'modal',
        },
        {
          src: 'gallery/16.jpg',
          srcBig: 'gallery/16.jpg',
          href: null,
          target: 'modal',
        },
        {
          src: 'gallery/17.jpg',
          srcBig: 'gallery/17.jpg',
          href: null,
          target: 'modal',
        },
        {
          src: 'gallery/18.jpg',
          srcBig: 'gallery/18.jpg',
          href: null,
          target: 'modal',
        },
        {
          src: 'gallery/19.jpg',
          srcBig: 'gallery/19.jpg',
          href: null,
          target: 'modal',
        },
        {
          src: 'gallery/20.jpg',
          srcBig: 'gallery/20.jpg',
          href: null,
          target: 'modal',
        },
      ],
      group: 0, // request param
    }
  },
  components: {
    VueMasonryGallery,
  },
}
</script>
