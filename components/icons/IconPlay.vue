<template>
  <svg
    xmlns="http://www.w3.org/2000/svg"
    viewBox="0 0 24 24"
    :width="width"
    :height="height"
    :aria-labelledby="iconName"
  >
    <rect
      id="Rectangle_138"
      data-name="Rectangle 138"
      width="24"
      height="24"
      fill="#fff"
      opacity="0"
    />
    <path
      id="Path_2572"
      data-name="Path 2572"
      d="M256.676,3086.067a1.685,1.685,0,0,1-1.682-1.687v-14.626a1.681,1.681,0,0,1,2.566-1.435l11.637,7.067a1.69,1.69,0,0,1,.041,2.844l-11.637,7.559A1.659,1.659,0,0,1,256.676,3086.067Zm0-16.419a.109.109,0,0,0-.051.015.1.1,0,0,0-.052.09v14.626a.1.1,0,0,0,.159.086l11.637-7.559a.1.1,0,0,0,.046-.088.1.1,0,0,0-.049-.086l-11.637-7.067A.094.094,0,0,0,256.676,3069.649Z"
      transform="translate(-250.494 -3065.072)"
      :fill="color"
    />
  </svg>
</template>
<script>
export default {
  props: {
    iconName: {
      type: String,
      default: 'box'
    },
    width: {
      type: [Number, String],
      default: 18
    },
    height: {
      type: [Number, String],
      default: 18
    },
    color: {
      type: String,
      default: 'currentColor'
    }
  }
}
</script>
