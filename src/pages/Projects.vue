<template>
  <div class="content">
    <div class="md-layout">
      <div
        class="md-layout-item md-medium-size-30 md-xsmall-size-50 md-size-25"
      >
        <stats-card data-background-color="green">

          <template slot="header">
          Project 1
          </template>

          <template slot="content">
            <h4 class="title">Group Project</h4>
          </template>

          <template slot="footer">
            <div class="stats">
              <md-icon>date_range</md-icon>
              Due 2 Mar 2020 23:59
            </div>
          </template>
        </stats-card>
      </div>
    </div>
  </div>
</template>

<script>
import {
  StatsCard
} from "@/components";

export default {
  components: {
    StatsCard
  },
  data() {
    return {
      
    };
  }
};
</script>

