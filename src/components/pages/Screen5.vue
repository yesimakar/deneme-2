<template>
  <NucGridPage v-bind:gap="{'row':0,'col':0}" v-bind:designMode="false" overflow="auto" v-bind:rows="[1]"
    v-bind:columns="[1]"
    v-bind:schema="{'r0-c0':{'row':0,'col':0,'rowSpan':1,'colSpan':1,'showIn':['xs','sm','md','lg']}}"
    v-bind:minNsLimit="0"
    v-bind:style="{'background':'#FFFFFF','paddingTop':'0px','paddingBottom':'0px','paddingLeft':'0px','paddingRight':'0px'}">
    <NucGridCell v-bind:wrap="true" v-bind:reverse="false" overflow="hidden" direction="column"
      v-bind:showInDevice="['xs','sm','md','lg']" verticalAlignment="top" horizontalAlignment="left" v-bind:row="0"
      v-bind:col="0" v-bind:rowSpan="1" v-bind:colSpan="1" v-bind:marginLeft="0" v-bind:marginRight="0"
      v-bind:marginTop="0" v-bind:marginBottom="0" id="6d5f1b50-6b8d-4984-a059-1a651061a229"
      v-bind:style="{'height':'auto','background':'transparent','paddingTop':'0px','borderColor':'','borderStyle':'solid','borderWidth':'0px','paddingLeft':'0px','borderRadius':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'1px','borderTopRightRadius':'1px','borderBottomLeftRadius':'1px','borderBottomRightRadius':'1px'}"
      slot="r0-c0" area="r0-c0"/>
  </NucGridPage>
</template>
<script>
export default {
  name: 'Screen5',
  data() {
    return {};
  },
  props: {},
  created() {},
  mounted() {},
  computed: {},
  methods: {},
  watch: {},
};
</script>

<style scoped></style>