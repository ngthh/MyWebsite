<template>
  <!-- <q-header elevated class="bg-deep-purple-4 text-white" height-hint="98">
    <q-toolbar>
      <q-btn dense flat round icon="menu" @click="left = !left" />
      <q-toolbar-title>
        <q-avatar>
          <img src="~assets/logo.jpg">
        </q-avatar>
        My View
      </q-toolbar-title>
    </q-toolbar>
  </q-header>
  <q-drawer
    v-model="left"
    show-if-above
    :width="300"
    :breakpoint="400"
  >
    <q-scroll-area style="height: calc(100% - 150px); margin-top: 150px; border-right: 1px solid #ddd">
      <q-list padding>
        <q-item
          clickable
          v-ripple>
          <q-item-section avatar>
            <q-icon name="inbox" />
          </q-item-section>

          <q-item-section>
            Inbox
          </q-item-section>
        </q-item>

        <q-item active clickable v-ripple>
          <q-item-section avatar>
            <q-icon name="star" />
          </q-item-section>

          <q-item-section>
            Star
          </q-item-section>
        </q-item>

        <q-item clickable v-ripple>
          <q-item-section avatar>
            <q-icon name="send" />
          </q-item-section>

          <q-item-section>
            Send
          </q-item-section>
        </q-item>

        <q-item clickable v-ripple>
          <q-item-section avatar>
            <q-icon name="drafts" />
          </q-item-section>

          <q-item-section>
            Drafts
          </q-item-section>
        </q-item>
      </q-list>
    </q-scroll-area>

    <q-img class="absolute-top" src="~assets/purpletemplate.jpg" style="height: 150px">
      <div class="absolute-bottom bg-transparent">
        <q-avatar size="56px" class="q-mb-sm">
          <img src="https://cdn.quasar.dev/img/boy-avatar.png">
        </q-avatar>
        <div class="text-weight-bold">Razvan Stoenescu</div>
        <div>@rstoenescu</div>
      </div>
    </q-img>
  </q-drawer> -->
  <div>Menu Bar is here</div>
</template>

<script>
export default {
  name: 'MenuBar',
  data () {
    return {
      left: false
    }
  }
}
</script>