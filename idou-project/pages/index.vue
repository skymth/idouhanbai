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
          <span class="md-display-1">近くのイベント</span>
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
                  <img src="https://user-images.githubusercontent.com/28649418/49335002-609f2500-f627-11e8-9a68-73b953e1f4ad.jpg">
              </md-card-media>

              <md-card-header>
                  <div class="md-title">VR 城下町</div>
                  <div class="md-subhead">さあ取り乱せ</div>
              </md-card-header>

              <md-card-expand>
                  <md-card-actions md-alignment="space-between">
                      <div>
                          <md-button class="md-icon-button md-accent">
                              <md-icon>thumb_up</md-icon>
                          </md-button>
                      </div>

                      <md-card-expand-trigger>
                          <md-button class="md-icon-button">
                              <md-icon>keyboard_arrow_down</md-icon>
                          </md-button>
                      </md-card-expand-trigger>
                  </md-card-actions>

                  <md-card-expand-content>
                      <md-card-content>
                          <h4>場所</h4>福島県会津若松市追手町４−４８ ミニストップ 会津鶴ヶ城前店<br>
                          <h4>日時</h4>12/18 15:00<br>
                          <h4>料金</h4>500円<br>
                          <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3165.7747730850706!2d139.93134191557166!3d37.48964097981237!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x5ff55497f9ee833b%3A0x4994f5b084f08535!2z44Of44OL44K544OI44OD44OXIOS8mua0pem2tOODtuWfjuWJjeW6lw!5e0!3m2!1sja!2sjp!4v1543718917230" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>
                      </md-card-content>
                  </md-card-expand-content>
              </md-card-expand>
          </md-card>
          <md-card>
              <md-card-media>
                  <img src="https://camo.githubusercontent.com/ba41f8c6abfb0e5197c8c7a57c56afcea6763e73/68747470733a2f2f6d656469612e74696d656f75742e636f6d2f696d616765732f3130323536313139312f696d6167652e6a7067">
              </md-card-media>

              <md-card-header>
                  <div class="md-title">映画鑑賞</div>
                  <div class="md-subhead">森の中で映画鑑賞！</div>
              </md-card-header>

              <md-card-expand>
                  <md-card-actions md-alignment="space-between">
                      <div>
                          <md-button class="md-icon-button md-accent">
                              <md-icon>thumb_up</md-icon>
                          </md-button>
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
                          <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d335.39406105405544!2d139.9469449918852!3d37.51339952808608!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x5f8aacbab17b7d51%3A0x7c9f6650e0a06ac4!2z44CSOTY1LTAwMTUg56aP5bO255yM5Lya5rSl6Iul5p2-5biC5YyX5rud5rKi77yS5LiB55uu77yV4oiS77yWIOS4gOeuleW4guawkeOCu-ODs-OCv-ODvA!5e0!3m2!1sja!2sjp!4v1543714502402" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>
                      </md-card-content>
                  </md-card-expand-content>
              </md-card-expand>
          </md-card>
      </md-app-content>
    </md-app>
    <bottom-bar></bottom-bar>
  </div>
</template>

<style lang="scss" scoped>
  .md-app {
    max-height: 755px;
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

  .md-card {
    width: 320px;
    margin: 5px;
    display: inline-block;
    vertical-align: top;
  }

</style>

<script>
import BottomBarComponent from '~/components/BottomBarComponent.vue'

export default {
  name: 'Flexible',
  components: {
    'bottom-bar': BottomBarComponent
  },
  data: () => ({
    menuVisible: false
  })
}
</script>
