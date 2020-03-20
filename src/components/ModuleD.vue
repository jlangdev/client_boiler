<template>
  <v-container>
    <v-hover>
      <v-card
        slot-scope="{ hover }"
        :class="`elevation-${hover ? 8 : 2} clickable`"
      >
        <v-card-title
          primary-title
          size="100%"
        >
          <div>
            <h3 class="headline mb-0">Module D</h3>
            <h4 class="subtitle-1">Vulnerability 4</h4>
          </div>
        </v-card-title>

        <v-card-text>
          <div id="desc">component body</div>
        </v-card-text>
      </v-card>
    </v-hover>
  </v-container>
</template>
<script>
export default {
  name: "ModuleD",
  props: {},
  methods: {
    clicked: function() {}
  }
};
</script>