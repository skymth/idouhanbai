<template>
  <div class="page-container">
    <md-app md-waterfall md-mode="flexible">
      <md-app-toolbar class="md-large md-primary">
        <div class="md-toolbar-row">
          <div class="md-toolbar-section-start">
            <md-button class="md-icon-button" @click="menuVisible = !menuVisible">
              <md-icon>menu</md-icon>
            </md-button>
          </div>

          <div class="md-toolbar-section-end">
            <md-button class="md-icon-button">
              <md-icon>more_vert</md-icon>
            </md-button>
          </div>
        </div>

        <div class="md-toolbar-row md-toolbar-offset">
          <span class="md-display-1">My Title</span>
        </div>
      </md-app-toolbar>

      <md-app-drawer :md-active.sync="menuVisible">
        <md-toolbar class="md-transparent" md-elevation="0">Navigation</md-toolbar>

        <md-list>
          <md-list-item>
            <md-icon>move_to_inbox</md-icon>
            <span class="md-list-item-text">Inbox</span>
          </md-list-item>

          <md-list-item>
            <md-icon>send</md-icon>
            <span class="md-list-item-text">Sent Mail</span>
          </md-list-item>

          <md-list-item>
            <md-icon>delete</md-icon>
            <span class="md-list-item-text">Trash</span>
          </md-list-item>

          <md-list-item>
            <md-icon>error</md-icon>
            <span class="md-list-item-text">Spam</span>
          </md-list-item>
        </md-list>
      </md-app-drawer>

      <md-app-content>
          <md-card>
              <md-card-media>
                  <img src="https://camo.githubusercontent.com/ba41f8c6abfb0e5197c8c7a57c56afcea6763e73/68747470733a2f2f6d656469612e74696d656f75742e636f6d2f696d616765732f3130323536313139312f696d6167652e6a7067" style="width: 50%; height: 50%">
              </md-card-media>

              <md-card-header>
                  <div class="md-title">Title goes here</div>
                  <div class="md-subhead">Subtitle here</div>
              </md-card-header>

              <md-card-expand>
                  <md-card-actions md-alignment="space-between">
                      <div>
                          <md-button>Action</md-button>
                          <md-button>Action</md-button>
                      </div>

                      <md-card-expand-trigger>
                          <md-button class="md-icon-button">
                              <md-icon>keyboard_arrow_down</md-icon>
                          </md-button>
                      </md-card-expand-trigger>
                  </md-card-actions>

                  <md-card-expand-content>
                      <md-card-content>
                          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Optio itaque ea, nostrum odio. Dolores, sed accusantium quasi non, voluptas eius illo quas, saepe voluptate pariatur in deleniti minus sint. Excepturi.
                      </md-card-content>
                  </md-card-expand-content>
              </md-card-expand>
          </md-card>
      </md-app-content>
    </md-app>
  </div>
</template>

<style lang="scss" scoped>
  .md-app {
    border: 1px solid rgba(#000, .12);
  }

  .md-app-toolbar {
    height: 196px;
  }

   // Demo purposes only
  .md-drawer {
    width: 230px;
    max-width: calc(100vw - 125px);
  }
</style>

<script>
export default {
  name: 'Flexible',
  data: () => ({
    menuVisible: false
  })
}
</script>
