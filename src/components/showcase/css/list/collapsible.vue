<template>
  <div>
    <div class="layout-padding">
      <p class="light-paragraph">
        You'll learn the <strong>List basics</strong> here then you can jump to the other sections
        to see how you can beatifully combine the List elements.
      </p>

      <div class="list">
        <quasar-collapsible icon="inbox" label="Inbox">
          <div class="item" v-for="n in 3">
            <i class="item-primary">mail</i>
            <div class="item-content">
              Email {{ n + 1 }}
            </div>
          </div>
          <quasar-collapsible icon="favorites" label="Favorites">
            <div class="item" v-for="n in 3">
              <i class="item-primary">mail</i>
              <div class="item-content">
                Favorite {{ n + 1 }}
              </div>
            </div>
          </quasar-collapsible>
        </quasar-collapsible>
        <quasar-collapsible icon="send" label="Sent">
          <div class="item" v-for="n in 3">
            <i class="item-primary">mail</i>
            <div class="item-content">
              Email {{ n + 1 }}
            </div>
          </div>
        </quasar-collapsible>
        <quasar-collapsible icon="delete" label="Trash">
          <div class="item" v-for="n in 3">
            <i class="item-primary">mail</i>
            <div class="item-content">
              Email {{ n + 1 }}
            </div>
          </div>
        </quasar-collapsible>
      </div>
    </div>
  </div>
</template>
