<template>
  <div>
  <mu-list>
    <mu-list-item title="Inbox">
      <mu-icon slot="left" value="inbox"/>
    </mu-list-item>
    <mu-list-item title="Starred">
      <mu-icon slot="left" value="grade"/>
    </mu-list-item>
    <mu-list-item title="Sent mail">
      <mu-icon slot="left" value="send"/>
    </mu-list-item>
    <mu-list-item title="Drafts">
      <mu-icon slot="left" value="drafts"/>
    </mu-list-item>
  </mu-list>
  <mu-divider />
  <mu-list>
    <mu-list-item title="All mail">
      <mu-icon slot="right" value="info"/>
    </mu-list-item>
    <mu-list-item title="Trash">
      <mu-icon slot="right" value="info"/>
    </mu-list-item>
    <mu-list-item title="Spam">
      <mu-icon slot="right" value="info"/>
    </mu-list-item>
    <mu-list-item title="Follow up">
      <mu-icon slot="right" value="info"/>
    </mu-list-item>
  </mu-list>
  </div>
</template>

<style scoped>
.mobile-tear-sheet{
  width : 300
}
</style>

<script>
import Vue from 'vue'
import MuseUI from 'muse-ui'
import AppMenu from '../components/menulist.vue'
import 'muse-ui/dist/muse-ui.css'

Vue.use(MuseUI)

export default {
    data(){
        return {
            title:"component"
        }
    }
}
</script>