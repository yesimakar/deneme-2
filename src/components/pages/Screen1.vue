<template>
  <NucGridPage v-bind:gap="{'col':0,'row':0}" v-bind:rows="[1]"
    v-bind:schema="{'r0-c0':{'col':0,'row':0,'showIn':['xs','sm','md','lg'],'colSpan':1,'rowSpan':1}}"
    v-bind:columns="[1]" overflow="auto" v-bind:designMode="false" v-bind:minNsLimit="525"
    v-bind:style="{'background':'#FFFFFF','paddingTop':'0px','paddingLeft':'0px','paddingRight':'0px','paddingBottom':'0px'}">
    <NucGridCell v-bind:wrap="true" v-bind:reverse="false" overflow="hidden" direction="column"
      v-bind:showInDevice="['xs','sm','md','lg']" verticalAlignment="top" horizontalAlignment="left"
      id="5797993d-073f-4c47-946a-a045243a7a57" v-bind:col="0" v-bind:row="0" v-bind:colSpan="1" v-bind:rowSpan="1"
      v-bind:marginTop="0" v-bind:marginLeft="0" v-bind:marginRight="0" v-bind:marginBottom="0"
      v-bind:style="{'height':'auto','background':'transparent','paddingTop':'0px','borderColor':'','borderStyle':'solid','borderWidth':'0px','paddingLeft':'0px','borderRadius':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'1px','borderTopRightRadius':'1px','borderBottomLeftRadius':'1px','borderBottomRightRadius':'1px'}"
      slot="r0-c0" area="r0-c0">
      <NucGroupElement v-bind:isLock="false" bgColor="" ncTooltipText="" position="absolute" top="26.663800515907138%"
        left="31.447549019607845%" id="7c690512-1dd7-491b-9523-7031c15e1ff9"
        v-bind:style="{'color':'#FFFFFF','width':'525','height':'300','fontSize':'15px','maxWidth':'','minWidth':'','tabIndex':'-1','boxShadow':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'center','background':'','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','lineHeight':'1.25','marginLeft':'0px','paddingTop':'','textShadow':'','visibility':'visible','borderColor':'#767676','borderStyle':'solid','marginRight':'0px','paddingLeft':'','marginBottom':'0px','paddingRight':'','paddingBottom':'','borderTopWidth':'1px','textDecoration':'none','borderLeftWidth':'1px','borderRightWidth':'1px','borderBottomWidth':'1px','borderTopLeftRadius':'0px','borderTopRightRadius':'0px','borderBottomLeftRadius':'0px','borderBottomRightRadius':'0px','zIndex':2}">
        <WLightButton tag="button" v-bind:pill="false" size="md" text="Light" type="button" v-bind:block="false"
          color="" theme="theme--light01" v-bind:squared="false" variant="light" v-bind:isEnabled="true" background=""
          borderColor="#F8F9FA" ncTypography="body1" v-bind:resetTrigger="false" ncTooltipText="" verticalWidth="60px"
          v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'text','displayName':'Value'}]}"
          verticalHeight="60px" horizontalWidth="72.4479px" horizontalHeight="37.5347px" ncClickFontColor="#FFFFFF"
          ncFocusFontColor="#FFFFFF" ncHoverFontColor="#FFFFFF" ncClickBorderColor="#4285f4"
          ncDisableFontColor="#FFFFFF" ncFocusBorderColor="#4285f4" ncHoverBorderColor="#4285f4"
          ncDisableBorderColor="transparent" ncClickBackgroundColor="#4285f4" ncFocusBackgroundColor="#4285f4"
          ncHoverBackgroundColor="#4285f4" ncDisableBackgroundColor="#969696" position="absolute"
          top="32.662083333333335%" left="33.4275%" id="61af5f6e-8add-4daa-91c2-e716fea70086"
          v-bind:style="{'width':'','height':'','fontSize':'12px','maxWidth':'','minWidth':'','tabIndex':'0px','boxShadow':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'center','fontFamily':'OpenSans-Bold,Open Sans','fontWeight':'bold','lineHeight':'1.4','marginLeft':'0px','paddingTop':'','textShadow':'','visibility':'visible','borderStyle':'solid','marginRight':'0px','paddingLeft':'','marginBottom':'0px','paddingRight':'','paddingBottom':'','borderTopWidth':'1px','textDecoration':'none','borderLeftWidth':'1px','borderRightWidth':'1px','horizontalHeight':'37.5347px','borderBottomWidth':'1px','borderTopLeftRadius':'4px','borderTopRightRadius':'4px','borderBottomLeftRadius':'4px','borderBottomRightRadius':'4px','zIndex':4}"/>
      </NucGroupElement>
    </NucGridCell>
  </NucGridPage>
</template>
<script>
export default {
  name: 'Screen1',
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