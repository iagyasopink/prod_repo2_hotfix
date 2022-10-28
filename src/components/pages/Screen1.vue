<template>
  <NucGridPage v-bind:gap="{'col':0,'row':0}" v-bind:rows="[1]"
    v-bind:schema="{'r0-c0':{'col':0,'row':0,'showIn':['xs','sm','md','lg'],'colSpan':1,'rowSpan':1}}"
    v-bind:columns="[1]" overflow="auto" v-bind:designMode="false" v-bind:minNsLimit="350"
    v-bind:style="{'background':'#FFFFFF','paddingTop':'0px','paddingLeft':'0px','paddingRight':'0px','paddingBottom':'0px'}">
    <NucGridCell v-bind:wrap="true" v-bind:reverse="false" overflow="hidden" direction="column"
      v-bind:showInDevice="['xs','sm','md','lg']" verticalAlignment="top" horizontalAlignment="left"
      id="f1ad4c02-50c1-4ec2-9ee3-b6e66e88bcf9" v-bind:col="0" v-bind:row="0" v-bind:colSpan="1" v-bind:rowSpan="1"
      v-bind:marginTop="0" v-bind:marginLeft="0" v-bind:marginRight="0" v-bind:marginBottom="0"
      v-bind:style="{'height':'auto','background':'transparent','paddingTop':'0px','borderColor':'','borderStyle':'solid','borderWidth':'0px','paddingLeft':'0px','borderRadius':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'1px','borderTopRightRadius':'1px','borderBottomLeftRadius':'1px','borderBottomRightRadius':'1px'}"
      slot="r0-c0" area="r0-c0">
      <WAspect
        src="https://quotefancy.com/media/wallpaper/800x450/1471043-Kapil-Dev-Quote-When-you-have-to-work-work-with-a-smile.jpg"
        tag="div" top="27.2078125%" left="28.304347826086957%" aspect="16:9"
        v-bind:aspects="[{'text':'4:3 (SD)','value':'4:3'},{'text':'1:1 (Square)','value':'1:1'},{'text':'16:9 (HD)','value':'16:9'},{'text':'1.85:1 (Widescreen)','value':'1.85:1'},{'text':'2:1 (Univisium/Superscope)','value':'2:1'},{'text':'21:9 (Anamorphic)','value':'21:9'},{'text':'1.43:1 (IMAX)','value':'1.43:1'},{'text':'3:2 (35mm Film)','value':'3:2'},{'text':'3:1 (APS-P)','value':'3:1'},{'text':'4/3 (Same as 4:3)','value':'4/3'},{'text':'16/9 (Same as 16:9)','value':'16/9'},{'text':'3 (Same as 3:1)','value':'3'},{'text':'2 (Same as 2:1)','value':'2'},{'text':'1.85 (Same as 1.85:1)','value':'1.85'},{'text':'1.5','value':'1.5'},{'text':'1 (Same as 1:1)','value':'1'}]"
        cardText="" position="absolute" bgVariant=""
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'src','displayName':'ImageUrl'},{'type':'string','propName':'cardText','displayName':'CardText'}]}"
        v-bind:textVisibility="true" id="a3fd1919-094c-4004-886e-ba0570ebaf4b"
        v-bind:style="{'color':'#000000','width':'','zIndex':2,'fontSize':'6.755999999999999px','maxWidth':'','minWidth':'','fontStyle':'normal','marginTop':'','maxHeight':'','minHeight':'','textAlign':'left','background':'#ffffff','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','marginLeft':'','paddingTop':'','visibility':'visible','marginRight':'','paddingLeft':'','marginBottom':'','paddingRight':'','paddingBottom':'','textDecoration':'none'}"/>
      <WAdvertisement v-bind:blank="true" imgSrc="" v-bind:overlay="true" cardText="Medium Rectangle" imgWidth="300px"
        bgVariant="secondary" imgHeight="300px" textVariant="white"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'imgSrc','displayName':'ImageUrl'},{'type':'string','propName':'cardText','displayName':'Value'}]}"
        verticalPosition="align-items-center" horizontalPosition="justify-content-center" position="absolute"
        top="12.9859375%" left="9.520652173913044%" id="8a603257-809c-453a-bb44-33367a4ff0e8"
        v-bind:style="{'width':'197.04999999999998','height':'33.779999999999994','maxWidth':'','minWidth':'','marginTop':'0px','maxHeight':'','minHeight':'','marginLeft':'0px','paddingTop':'0px','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','zIndex':3}"/>
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