<template>
    <div>
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
                    <md-button v-on:click="count++" class="md-icon-button md-accent">
                        <md-icon>thumb_up</md-icon>
                        <i class="badge" v-if="count">{{ count }}</i>
                    </md-button>
                    <md-button class="md-icon-button">
                        <md-icon>phone</md-icon>
                    </md-button>
                    <md-button class="md-icon-button">
                        <md-icon>share</md-icon>
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
            <img src="https://campfire-pub.s3.amazonaws.com/media/filter/l/img/53be953d-d26c-45bc-b4ff-76cf0a804936.png">
        </md-card-media>

        <md-card-header>
            <div class="md-title">野外映画鑑賞</div>
            <div class="md-subhead">猪苗代湖で映画鑑賞！</div>
        </md-card-header>

        <md-card-expand>
            <md-card-actions md-alignment="space-between">
                <div>
                    <md-button class="md-icon-button md-accent">
                        <md-icon>thumb_up</md-icon>
                    </md-button>
                    <md-button class="md-icon-button">
                        <md-icon>phone</md-icon>
                    </md-button>
                    <md-button class="md-icon-button">
                        <md-icon>share</md-icon>
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
                    <h4>場所</h4>〒965-0201 福島県会津若松市湊町大字赤井笹山原 湊町大字赤井字笹山原４０８<br>
                    <h4>日時</h4>12/18 19:00<br>
                    <h4>料金</h4>500円<br>
                    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d54024.678751300744!2d139.9431414631887!3d37.51551871219728!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0xd6b4ab347f3e1eac!2z77yy77y244Oq44K-44O844OI54yq6IuX5Luj5rmW44Oi44OT44Os44O844K4!5e0!3m2!1sja!2sjp!4v1543719460132" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>
                </md-card-content>
            </md-card-expand-content>
        </md-card-expand>
    </md-card>
    <md-card>
        <md-card-media>
            <img src="http://image.photohito.k-img.com/uploads/photo21/user20122/d50d9646f4dc716bcb233021f5fc567e/d50d9646f4dc716bcb233021f5fc567e_l.jpg">
        </md-card-media>

        <md-card-header>
            <div class="md-title">廃屋ホラーナイト</div>
            <div class="md-subhead">ハイオクでホラー映画鑑賞！</div>
        </md-card-header>

        <md-card-expand>
            <md-card-actions md-alignment="space-between">
                <div>
                    <md-button class="md-icon-button md-accent">
                        <md-icon>thumb_up</md-icon>
                    </md-button>
                    <md-button class="md-icon-button">
                        <md-icon>phone</md-icon>
                    </md-button>
                    <md-button class="md-icon-button">
                        <md-icon>share</md-icon>
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
                    <h4>場所</h4>〒965-0201 福島県会津若松市湊町大字赤井笹山原 湊町大字赤井字笹山原４０８<br>
                    <h4>日時</h4>12/18 19:00<br>
                    <h4>料金</h4>500円<br>
                    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d54024.678751300744!2d139.9431414631887!3d37.51551871219728!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0xd6b4ab347f3e1eac!2z77yy77y244Oq44K-44O844OI54yq6IuX5Luj5rmW44Oi44OT44Os44O844K4!5e0!3m2!1sja!2sjp!4v1543719460132" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>
                </md-card-content>
            </md-card-expand-content>
        </md-card-expand>
    </md-card>
    </div>
</template>

<style lang="scss" scoped>
  .md-card {
    width: 320px;
    margin: 5px;
    display: inline-block;
    vertical-align: top;
  }
</style>

<script>
export default {
  data: function () {
    return {
      count: 0
    }
  }
}
</script>
