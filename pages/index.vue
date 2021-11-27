<template>
  <div>
    <Page1 :words="words" />
    <Page2 />
    <Page3 />
    <Page4 />
    <Page5 />
    <Page6 />
    <Page7
      :truecolor="truecolor"
      :falsecolor="falsecolor"
      :aswer="aswer"
      :warnedtrue="warnedtrue"
      :warnedfalse="warnedfalse"
      :warned="warned"
      :mentionedtrue="mentionedtrue"
      :mentionedfalse="mentionedfalse"
      :referredtrue="referredtrue"
      :referredfalse="referredfalse"
      :installedtrue="installedtrue"
      :installedfalse="installedfalse"
      :scrolledtrue="scrolledtrue"
      :scrolledfalse="scrolledfalse"
      :attachedtrue="attachedtrue"
      :attachedfalse="attachedfalse"
      :generationtrue="generationtrue"
      :generationfalse="generationfalse"
      :origintrue="origintrue"
      :originfalse="originfalse"
      :shifttrue="shifttrue"
      :shiftfalse="shiftfalse"
      :compulsorytrue="compulsorytrue"
      :compulsoryfalse="compulsoryfalse"
      :qualifiedtrue="qualifiedtrue"
      :qualifiedfalse="qualifiedfalse"
      :protectivetrue="protectivetrue"
      :protectivefalse="protectivefalse"
      :sayingtrue="sayingtrue"
      :sayingfalse="sayingfalse"
      :tellingtrue="tellingtrue"
      :tellingfalse="tellingfalse"
      :explainingtrue="explainingtrue"
      :explainingfalse="explainingfalse"
      :effectivetrue="effectivetrue"
      :effectivefalse="effectivefalse"
      :practicaltrue="practicaltrue"
      :practicalfalse="practicalfalse"
      :portabletrue="portabletrue"
      :portablefalse="portablefalse"
      :deactivatedtrue="deactivatedtrue"
      :deactivatedfalse="deactivatedfalse"
      :obtainedtrue="obtainedtrue"
      :obtainedfalse="obtainedfalse"
      :evacuatedtrue="evacuatedtrue"
      :evacuatedfalse="evacuatedfalse"
      :complainedtrue="complainedtrue"
      :complainedfalse="complainedfalse"
      :gossipedtrue="gossipedtrue"
      :gossipedfalse="gossipedfalse"
      :socializedtrue="socializedtrue"
      :socializedfalse="socializedfalse"
      :gesturetrue="gesturetrue"
      :gesturefalse="gesturefalse"
      :lawtrue="lawtrue"
      :lawfalse="lawfalse"
      :permissiontrue="permissiontrue"
      :permissionfalse="permissionfalse"
      :warningtrue="warningtrue"
      :warningfalse="warningfalse"
      :hazardtrue="hazardtrue"
      :hazardfalse="hazardfalse"
      :cautiontrue="cautiontrue"
      :cautionfalse="cautionfalse"
    :mentioned="mentioned"
    :referred="referred"
    :installed="installed"
    :scrolled="scrolled"
    :attached="attached"
    :generation="generation"
    :origin="origin"
    :shift="shift"
    :compulsory="compulsory"
    :qualified="qualified"
    :protective="protective"
    :saying="saying"
    :telling="telling"
    :explaining="explaining"
    :effective="effective"
    :practical="practical"
    :portable="portable"
    :deactivated="deactivated"
    :obtained="obtained"
    :evacuated="evacuated"
    :complained="complained"
    :gossiped="gossiped"
    :socialized="socialized"
    :gesture="gesture"
    :law="law"
    :permission="permission"
    :warning="warning"
    :hazard="hazard"
    :caution="caution"

    />
    <Page8 />
    <Page9 />
    <Page10 />
  </div>
</template>

<script>
export default {
  data() {
    return {
      words: [
        {
          span: "face-to face",
        },
        {
          span: "instant messaging",
        },
        { span: "Skype" },
        { span: "video chat" },
        { span: "keep in touch" },
        { span: "download" },
        { span: "uploat" },
        { span: "post" },
        { span: "touchscreen" },
        { span: "functions of a computer" },
        { span: "internet access" },
        { span: "apps" },
        { span: "user-friendly" },
        { span: "handy" },
        { span: "practical" },
        { span: "portable" },
        { span: "time-saving" },
        { span: "time-consuming" },
        { span: "viruses" },
        { span: "(in)convenient" },
        { span: "outdated" },
        { span: "costly" },
        { span: " need to keep up to date" },
        { span: "store huge amounst of data" },
        { span: "know latest news instantly" },
        { span: "not socialize" },
      ],
      warnedtrue: false,
      warnedfalse: true,
      truecolor: false,
      falsecolor: true,
      mentionedtrue: false,
      mentionedfalse: true,
      referredtrue: false,
      referredfalse: true,
      installedtrue: false,
      installedfalse: true,
      scrolledtrue: false,
      scrolledfalse: true,
      attachedtrue: false,
      attachedfalse: true,
      generationtrue: false,
      generationfalse: true,
      origintrue: false,
      originfalse: true,
      shifttrue: false,
      shiftfalse: true,
      compulsorytrue: false,
      compulsoryfalse: true,
      qualifiedtrue: false,
      qualifiedfalse: true,
      protectivetrue: false,
      protectivefalse: true,
      sayingtrue: false,
      sayingfalse: true,
      tellingtrue: false,
      tellingfalse: true,
      explainingtrue: false,
      explainingfalse: true,
      effectivetrue: false,
      effectivefalse: true,
      practicaltrue: false,
      practicalfalse: true,
      portabletrue: false,
      portablefalse: true,
      deactivatedtrue: false,
      deactivatedfalse: true,
      obtainedtrue: false,
      obtainedfalse: true,
      evacuatedtrue: false,
      evacuatedfalse: true,
      complainedtrue: false,
      complainedfalse: true,
      gossipedtrue: false,
      gossipedfalse: true,
      socializedtrue: false,
      socializedfalse: true,
      gesturetrue: false,
      gesturefalse: true,
      lawtrue: false,
      lawfalse: true,
      permissiontrue: false,
      permissionfalse: true,
      warningtrue: false,
      warningfalse: true,
      hazardtrue: false,
      hazardfalse: true,
      cautiontrue: false,
      cautionfalse: true,
    };
  },
  methods: {
    aswer() {
      if (this.falsecolor == false && this.truecolor == true) {
        return (this.falsecolor = true), (this.truecolor = false);
      } else {
        return (this.falsecolor = false), (this.truecolor = true);
      }
    },
    warned() {
      if (this.warnedfalse == false && this.warnedtrue == true) {
        return (this.warnedfalse = true), (this.warnedtrue = false);
      } else {
        return (this.warnedfalse = false), (this.warnedtrue = true);
      }
    },
    mentioned() {
        if (this.mentionedfalse == false && this.mentionedtrue == true) {
        return (this.mentionedfalse = true), (this.mentionedtrue = false);
      } else {
        return (this.mentionedfalse = false), (this.mentionedtrue = true);
      }
    },
    referred() {
        if (this.referredfalse == false && this.referredtrue == true) {
        return (this.referredfalse = true), (this.referredtrue = false);
      } else {
        return (this.referredfalse = false), (this.referredtrue = true);
      }
    },
    installed() {
        if (this.installedfalse == false && this.installedtrue == true) {
        return (this.installedfalse = true), (this.installedtrue = false);
      } else {
        return (this.installedfalse = false), (this.installedtrue = true);
      }
    },
    scrolled() {
        if (this.scrolledfalse == false && this.scrolledtrue == true) {
        return (this.scrolledfalse = true), (this.scrolledtrue = false);
      } else {
        return (this.scrolledfalse = false), (this.scrolledtrue = true);
      }
    },
    attached() {
        if (this.attachedfalse == false && this.attachedtrue == true) {
        return (this.attachedfalse = true), (this.attachedtrue = false);
      } else {
        return (this.attachedfalse = false), (this.attachedtrue = true);
      }
    },
    generation() {
        if (this.generationfalse == false && this.generationtrue == true) {
        return (this.generationfalse = true), (this.generationtrue = false);
      } else {
        return (this.generationfalse = false), (this.generationtrue = true);
      }
    },
    origin() {
        if (this.originfalse == false && this.origintrue == true) {
        return (this.originfalse = true), (this.origintrue = false);
      } else {
        return (this.originfalse = false), (this.origintrue = true);
      }
    },
    shift() {
        if (this.shiftfalse == false && this.shifttrue == true) {
        return (this.shiftfalse = true), (this.shifttrue = false);
      } else {
        return (this.shiftfalse = false), (this.shifttrue = true);
      }
    },
    compulsory() {
        if (this.compulsoryfalse == false && this.compulsorytrue == true) {
        return (this.compulsoryfalse = true), (this.compulsorytrue = false);
      } else {
        return (this.compulsoryfalse = false), (this.compulsorytrue = true);
      }
    },
    qualified() {
        if (this.qualifiedfalse == false && this.qualifiedtrue == true) {
        return (this.qualifiedfalse = true), (this.qualifiedtrue = false);
      } else {
        return (this.qualifiedfalse = false), (this.qualifiedtrue = true);
      }
    },
    protective() {
        if (this.protectivefalse == false && this.protectivetrue == true) {
        return (this.protectivefalse = true), (this.protectivetrue = false);
      } else {
        return (this.protectivefalse = false), (this.protectivetrue = true);
      }
    },
    saying() {
        if (this.sayingfalse == false && this.sayingtrue == true) {
        return (this.sayingfalse = true), (this.sayingtrue = false);
      } else {
        return (this.sayingfalse = false), (this.sayingtrue = true);
      }
    },
    telling() {
        if (this.tellingfalse == false && this.tellingtrue == true) {
        return (this.tellingfalse = true), (this.tellingtrue = false);
      } else {
        return (this.tellingfalse = false), (this.tellingtrue = true);
      }
    },
    explaining() {
        if (this.explainingfalse == false && this.explainingtrue == true) {
        return (this.explainingfalse = true), (this.explainingtrue = false);
      } else {
        return (this.explainingfalse = false), (this.explainingtrue = true);
      }
    },
    effective() {
        if (this.effectivefalse == false && this.effectivetrue == true) {
        return (this.effectivefalse = true), (this.effectivetrue = false);
      } else {
        return (this.effectivefalse = false), (this.effectivetrue = true);
      }
    },
    practical() {
        if (this.practicalfalse == false && this.practicaltrue == true) {
        return (this.practicalfalse = true), (this.practicaltrue = false);
      } else {
        return (this.practicalfalse = false), (this.practicaltrue = true);
      }
    },
    portable() {
        if (this.portablefalse == false && this.portabletrue == true) {
        return (this.portablefalse = true), (this.portabletrue = false);
      } else {
        return (this.portablefalse = false), (this.portabletrue = true);
      }
    },
    deactivated() {
        if (this.deactivatedfalse == false && this.deactivatedtrue == true) {
        return (this.deactivatedfalse = true), (this.deactivatedtrue = false);
      } else {
        return (this.deactivatedfalse = false), (this.deactivatedtrue = true);
      }
    },
    obtained() {
        if (this.obtainedfalse == false && this.obtainedtrue == true) {
        return (this.obtainedfalse = true), (this.obtainedtrue = false);
      } else {
        return (this.obtainedfalse = false), (this.obtainedtrue = true);
      }
    },
    evacuated() {
        if (this.evacuatedfalse == false && this.evacuatedtrue == true) {
        return (this.evacuatedfalse = true), (this.evacuatedtrue = false);
      } else {
        return (this.evacuatedfalse = false), (this.evacuatedtrue = true);
      }
    },
    complained() {
        if (this.complainedfalse == false && this.complainedtrue == true) {
        return (this.complainedfalse = true), (this.complainedtrue = false);
      } else {
        return (this.complainedfalse = false), (this.complainedtrue = true);
      }
    },
    gossiped() {
        if (this.gossipedfalse == false && this.gossipedtrue == true) {
        return (this.gossipedfalse = true), (this.gossipedtrue = false);
      } else {
        return (this.gossipedfalse = false), (this.gossipedtrue = true);
      }
    },
    socialized() {
        if (this.socializedfalse == false && this.socializedtrue == true) {
        return (this.socializedfalse = true), (this.socializedtrue = false);
      } else {
        return (this.socializedfalse = false), (this.socializedtrue = true);
      }
    },
    gesture() {
        if (this.gesturefalse == false && this.gesturetrue == true) {
        return (this.gesturefalse = true), (this.gesturetrue = false);
      } else {
        return (this.gesturefalse = false), (this.gesturetrue = true);
      }
    },
    law() {
        if (this.lawfalse == false && this.lawtrue == true) {
        return (this.lawfalse = true), (this.lawtrue = false);
      } else {
        return (this.lawfalse = false), (this.lawtrue = true);
      }
    },
    permission() {
        if (this.permissionfalse == false && this.permissiontrue == true) {
        return (this.permissionfalse = true), (this.permissiontrue = false);
      } else {
        return (this.permissionfalse = false), (this.permissiontrue = true);
      }
    },
     warning() {
        if (this.warningfalse == false && this.warningtrue == true) {
        return (this.warningfalse = true), (this.warningtrue = false);
      } else {
        return (this.warningfalse = false), (this.warningtrue = true);
      }
    },
    hazard() {
        if (this.hazardfalse == false && this.hazardtrue == true) {
        return (this.hazardfalse = true), (this.hazardtrue = false);
      } else {
        return (this.hazardfalse = false), (this.hazardtrue = true);
      }
    },
    caution() {
        if (this.cautionfalse == false && this.cautiontrue == true) {
        return (this.cautionfalse = true), (this.cautiontrue = false);
      } else {
        return (this.cautionfalse = false), (this.cautiontrue = true);
      }
    },
  },
};
</script>
<style>
.page {
  width: 600px;
  height: 800px;
}
</style>