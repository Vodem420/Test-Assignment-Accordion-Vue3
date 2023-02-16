<script setup>
import { ref } from "vue";
import Accordion from "../components/accordion.vue";
const picked = ref("One");
</script>

<template>
  <div class="AccordionSection">
    <accordion>
      <template #title>
        <span class="AccordionSection__title">The analysis</span>
      </template>

      <template #content>
        <div class="AccordionSection__text">
          <h2>To take into account on user level data</h2>
          <div>
            <input name="radio" type="radio" />
            <p>
              Do you have one user in more than one variant of the same AB test?
            </p>
          </div>
          <div>
            <input name="radio" type="radio" />
            <p>
              Are you users actually getting the treatment we expect them to
              get?
            </p>
          </div>
          <div>
            <input name="radio" type="radio" />
            <p>
              Do we have enough users in our AB test? Are those users
              representative for the total population?
            </p>
          </div>
        </div>
      </template>
    </accordion>
    <accordion>
      <template #title>
        <span class="AccordionSection__title">Our data</span>
      </template>

      <template #content>
        <div class="AccordionSection__text">
          <h2>To take into account on user level data</h2>
          <div>
            <input name="radio" type="radio" />
            <p>
              Do you have one user in more than one variant of the same AB test?
            </p>
          </div>
          <div>
            <input name="radio" type="radio" />
            <p>
              Are you users actually getting the treatment we expect them to
              get?
            </p>
          </div>
          <div>
            <input name="radio" type="radio" />
            <p>
              Do we have enough users in our AB test? Are those users
              representative for the total population?
            </p>
          </div>
        </div>
      </template> </accordion
    ><accordion>
      <template #title>
        <span class="AccordionSection__title">Our study case</span>
      </template>

      <template #content>
        <div class="AccordionSection__text">
          <h2>To take into account on user level data</h2>
          <div>
            <input name="radio" type="radio" />
            <p>
              Do you have one user in more than one variant of the same AB test?
            </p>
          </div>
          <div>
            <input name="radio" type="radio" />
            <p>
              Are you users actually getting the treatment we expect them to
              get?
            </p>
          </div>
          <div>
            <input name="radio" type="radio" />
            <p>
              Do we have enough users in our AB test? Are those users
              representative for the total population?
            </p>
          </div>
        </div>
      </template> </accordion
    ><accordion>
      <template #title>
        <span class="AccordionSection__title">Hands on analyzing</span>
      </template>

      <template #content>
        <div class="AccordionSection__text">
          <h2>To take into account on user level data</h2>
          <div>
            <input name="radio" type="radio" />
            <p>
              Do you have one user in more than one variant of the same AB test?
            </p>
          </div>
          <div>
            <input name="radio" type="radio" />
            <p>
              Are you users actually getting the treatment we expect them to
              get?
            </p>
          </div>
          <div>
            <input name="radio" type="radio" />
            <p>
              Do we have enough users in our AB test? Are those users
              representative for the total population?
            </p>
          </div>
        </div>
      </template> </accordion
    ><accordion>
      <template #title>
        <span class="AccordionSection__title">Initialization</span>
      </template>

      <template #content>
        <div class="AccordionSection__text">
          <h2>To take into account on user level data</h2>
          <div>
            <input name="radio" type="radio" />
            <p>
              Do you have one user in more than one variant of the same AB test?
            </p>
          </div>
          <div>
            <input name="radio" type="radio" />
            <p>
              Are you users actually getting the treatment we expect them to
              get?
            </p>
          </div>
          <div>
            <input name="radio" type="radio" />
            <p>
              Do we have enough users in our AB test? Are those users
              representative for the total population?
            </p>
          </div>
        </div>
      </template>
    </accordion>
  </div>
</template>
