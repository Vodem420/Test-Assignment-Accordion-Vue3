<script setup>
import Accordion from "../components/accordion.vue";
</script>

<template>
  <div class="AccordionSection">
    <accordion>
      <template #title>
        <span class="AccordionSection__title">The analysis</span>
      </template>
      <template #content>
        <p class="AccordionSection__text">
          <b>Lorem</b>, ipsum dolor sit amet consectetur adipisicing elit. Quia,
          porro. Non a excepturi, voluptatibus ipsam magnam, eligendi,
          accusantium ipsa quae quis praesentium voluptate saepe ullam sint ea
          itaque consectetur impedit?
        </p>
      </template>
    </accordion>
    <accordion>
      <template #title>
        <span class="AccordionSection__title">Our data</span>
      </template>
      <template #content>
        <p class="AccordionSection__text">
          <b>Lorem</b>, ipsum dolor sit amet consectetur adipisicing elit. Quia,
          porro. Non a excepturi, voluptatibus ipsam magnam, eligendi,
          accusantium ipsa quae quis praesentium voluptate saepe ullam sint ea
          itaque consectetur impedit?
        </p>
      </template>
    </accordion>
    <accordion>
      <template #title>
        <span class="AccordionSection__title">Our study case</span>
      </template>
      <template #content>
        <p class="AccordionSection__text">
          <b>Lorem</b>, ipsum dolor sit amet consectetur adipisicing elit. Quia,
          porro. Non a excepturi, voluptatibus ipsam magnam, eligendi,
          accusantium ipsa quae quis praesentium voluptate saepe ullam sint ea
          itaque consectetur impedit?
        </p>
      </template>
    </accordion>
    <accordion>
      <template #title>
        <span class="AccordionSection__title">Hands on analyzing</span>
      </template>
      <template #content>
        <p class="AccordionSection__text">
          <b>Lorem</b>, ipsum dolor sit amet consectetur adipisicing elit. Quia,
          porro. Non a excepturi, voluptatibus ipsam magnam, eligendi,
          accusantium ipsa quae quis praesentium voluptate saepe ullam sint ea
          itaque consectetur impedit?
        </p>
      </template>
    </accordion>
    <accordion>
      <template #title>
        <span class="AccordionSection__title">Initialization</span>
      </template>
      <template #content>
        <p class="AccordionSection__text">
          <b>Lorem</b>, ipsum dolor sit amet consectetur adipisicing elit. Quia,
          porro. Non a excepturi, voluptatibus ipsam magnam, eligendi,
          accusantium ipsa quae quis praesentium voluptate saepe ullam sint ea
          itaque consectetur impedit?
        </p>
      </template>
    </accordion>
  </div>
</template>
