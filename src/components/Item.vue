<template>
  <div>
    <v-expansion-panels class="mb-6">
      <v-expansion-panel v-for="i in 3" :key="i">
        <v-expansion-panel-title expand-icon="mdi-menu-down"
          >NIKE</v-expansion-panel-title
        >
        <v-expansion-panel-text>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Adipisci sint
          eligendi culpa in aperiam obcaecati ratione! Cupiditate minima debitis
          commodi.
        </v-expansion-panel-text>
      </v-expansion-panel>
      <v-expansion-panel>
        <v-expansion-panel-title
          expand-icon="mdi-plus"
          collapse-icon="mdi-minus"
          >MODEL</v-expansion-panel-title
        >
        <v-expansion-panel-text>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellendus
          delectus dolorum vero non earum itaque nihil! Impedit accusamus veniam
          cupiditate?
        </v-expansion-panel-text>
      </v-expansion-panel>
    <v-expansion-panel>
      <v-expansion-panel-title>
        MARQUE
        <template v-slot:actions="{expanded}">
            <v-icon :color="!expanded ? 'teal' : ''" :icon="expanded ? 'mdi-pencil' :'mdi-check'"></v-icon>
        </template>
      </v-expansion-panel-title>
      <v-expansion-panel-text>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellendus
          delectus dolorum vero non earum itaque nihil! Impedit accusamus veniam
          cupiditate?
        </v-expansion-panel-text>
    </v-expansion-panel>
    </v-expansion-panels>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>