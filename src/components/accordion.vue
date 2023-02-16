<script setup>
import { ref } from "vue";
const isOpen = ref(false);

const toggleAccordion = function () {
  isOpen.value = !isOpen.value;
};
</script>

<template>
  <div class="accordion">
    <button
      class="accordion__button"
      :aria-expanded="isOpen"
      :aria-controls="`collapse${_uid}`"
      @click="toggleAccordion()"
    >
      <slot name="title" />

      <svg
        class="w-3 transition-all duration-200 transform arrow"
        :class="{
          'rotate-180': isOpen,
          'rotate-0': !isOpen,
        }"
        fill="none"
        stroke="currentColor"
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 16 10"
        aria-hidden="true"
      >
        <path
          d="M15 1.2l-7 7-7-7"
          stroke-width="2"
          stroke-linecap="round"
          stroke-linejoin="round"
        />
      </svg>
    </button>
    <Transition>
      <div v-show="isOpen" :id="`collapse${_uid}`">
        <slot name="content" />
      </div>
    </Transition>
  </div>
</template>
<style>
.v-enter-active,
.v-leave-active {
  transition: opacity 0.5s ease;
}

.v-enter-from,
.v-leave-to {
  opacity: 0;
}
</style>
