<template>
  <div class="flex justify-center pt-24">
    <div class="page bg-gray-100 shadow-2xl text-sm text-gray-900">
      <div class="p-6">
        <div>
          <div>
            <div class="mb-2">
              <div>
                <div class="w-96">
                  <h2 class="font-bold text-gray-800 my-2 flex">
                    <p class="font-bold text-pink-900 mr-2">A.</p>
                    Choose a, b or c.
                  </h2>
                </div>
                <ul class="space-y-4">
                  <li>
                    <div>
                      <span class="font-bold">1.</span> Dylan might be at the
                      mail because he ____ something about going shopping.
                    </div>
                   
                    <div class="flex space-x-12 mx-4">
                      <button
                        @click="warned()"
                        class="transition duration-300 p-1"
                        :class="{
                          'bg-red-600 text-white  rounded': warnedtrue,
                          'bg-transparent': warnedfalse,
                        }"
                      >
                        <p><span class="font-bold">a.</span> warned</p>
                      </button>
                      <button
                        @click="mentioned()"
                        class="transition duration-300 p-1"
                        :class="{
                          'bg-green-300 text-white  rounded': mentionedtrue,
                          'bg-transparent': mentionedfalse,
                        }"
                      >
                        <p><span class="font-bold">b.</span> mentioned</p>
                      </button>
                      <button
                        @click="referred()"
                        class="transition duration-300 p-1"
                        :class="{
                          'bg-red-600 text-white  rounded': referredtrue,
                          'bg-transparent': referredfalse,
                        }"
                      >
                        <p><span class="font-bold">c.</span> referred</p>
                      </button>
                    </div>
                  </li>
                  <li>
                    <div>
                      <span class="font-bold">2.</span> I ____ a new antivirus
                      program on my computer today.
                    </div>          
                    <div class="flex space-x-12 mx-4">
                      <button
                        @click="installed()"
                        class="transition duration-300 p-1"
                        :class="{
                          'bg-green-300 text-white  rounded': installedtrue,
                          'bg-transparent': installedfalse,
                        }"
                      >
                        <p><span class="font-bold">a.</span> installed</p>
                      </button>
                      <button
                        @click="scrolled()"
                        class="transition duration-300 p-1"
                        :class="{
                          'bg-red-600 text-white  rounded': scrolledtrue,
                          'bg-transparent': scrolledfalse,
                        }"
                      >
                        <p><span class="font-bold">b.</span> scrolled</p>
                      </button>
                      <button
                        @click="attached()"
                        class="transition duration-300 p-1"
                        :class="{
                          'bg-red-600 text-white  rounded': attachedtrue,
                          'bg-transparent': attachedfalse,
                        }"
                      >
                        <p><span class="font-bold">c.</span> attached</p>
                      </button>
                    </div>
                  </li>
                  <li>
                    <div>
                      <span class="font-bold">3.</span> the younger ____ uses
                      social media sites much more often than mine does.
                    </div>
                    <div class="flex space-x-12 mx-4">
                      <button
                        @click="generation()"
                        class="transition duration-300 p-1"
                        :class="{
                          'bg-green-300 text-white  rounded': generationtrue,
                          'bg-transparent': generationfalse,
                        }"
                      >
                        <p><span class="font-bold">a.</span> generation</p>
                      </button>
                      <button
                        @click="origin()"
                        class="transition duration-300 p-1"
                        :class="{
                          'bg-red-600 text-white  rounded': origintrue,
                          'bg-transparent': originfalse,
                        }"
                      >
                        <p><span class="font-bold">b.</span> origin</p>
                      </button>
                      <button
                        @click="shift()"
                        class="transition duration-300 p-1"
                        :class="{
                          'bg-red-600 text-white  rounded': shifttrue,
                          'bg-transparent': shiftfalse,
                        }"
                      >
                        <p><span class="font-bold">c.</span> shift</p>
                      </button>
                    </div>
                  </li>
                  <li>
                    <div>
                      <span class="font-bold">4.</span> It is ____ for all
                      drivers to wear seat belts.
                    </div>
                   
                    <div class="flex space-x-12 mx-4">
                      <button
                        @click="compulsory()"
                        class="transition duration-300 p-1"
                        :class="{
                          'bg-green-300 text-white  rounded': compulsorytrue,
                          'bg-transparent': compulsoryfalse,
                        }"
                      >
                        <p><span class="font-bold">a.</span> compulsory</p>
                      </button>
                      <button
                        @click="qualified()"
                        class="transition duration-300 p-1"
                        :class="{
                          'bg-red-600 text-white  rounded': qualifiedtrue,
                          'bg-transparent': qualifiedfalse,
                        }"
                      >
                        <p><span class="font-bold">b.</span> qualified</p>
                      </button>
                      <button
                        @click="protective()"
                        class="transition duration-300 p-1"
                        :class="{
                          'bg-red-600 text-white  rounded': protectivetrue,
                          'bg-transparent': protectivefalse,
                        }"
                      >
                        <p><span class="font-bold">c.</span> protective</p>
                      </button>
                    </div>
                  </li>
                  <li>
                    <div>
                      <span class="font-bold">5.</span> Jack's no good at ____
                      jokes. Nobody laughs when he does.
                    </div>
                   
                    <div class="flex space-x-12 mx-4">
                      <button
                        @click="saying()"
                        class="transition duration-300 p-1"
                        :class="{
                          'bg-red-600 text-white  rounded': sayingtrue,
                          'bg-transparent': sayingfalse,
                        }"
                      >
                        <p><span class="font-bold">a.</span> saying</p>
                      </button>
                      <button
                        @click="telling()"
                        class="transition duration-300 p-1"
                        :class="{
                          'bg-green-300 text-white  rounded': tellingtrue,
                          'bg-transparent': tellingfalse,
                        }"
                      >
                        <p><span class="font-bold">b.</span> telling</p>
                      </button>
                      <button
                        @click="explaining()"
                        class="transition duration-300 p-1"
                        :class="{
                          'bg-red-600 text-white  rounded': explainingtrue,
                          'bg-transparent': explainingfalse,
                        }"
                      >
                        <p><span class="font-bold">c.</span> explaining</p>
                      </button>
                    </div>
                  </li>
                  <li>
                    <div>
                      <span class="font-bold">6.</span> This ____ gadget is very
                      handy, since I can take it with me anywhere I go.
                    </div>
                   
                    <div class="flex space-x-12 mx-4">
                      <button
                        @click="effective()"
                        class="transition duration-300 p-1"
                        :class="{
                          'bg-red-600 text-white  rounded': effectivetrue,
                          'bg-transparent': effectivefalse,
                        }"
                      >
                        <p><span class="font-bold">a.</span> effective</p>
                      </button>
                      <button
                        @click="practical()"
                        class="transition duration-300 p-1"
                        :class="{
                          'bg-red-600 text-white  rounded': practicaltrue,
                          'bg-transparent': practicalfalse,
                        }"
                      >
                        <p><span class="font-bold">b.</span> practical</p>
                      </button>
                      <button
                        @click="portable()"
                        class="transition duration-300 p-1"
                        :class="{
                          'bg-green-300 text-white  rounded': portabletrue,
                          'bg-transparent': portablefalse,
                        }"
                      >
                        <p><span class="font-bold">c.</span> portable</p>
                      </button>
                    </div>
                  </li>
                  <li>
                    <div>
                      <span class="font-bold">7.</span> Everybody ____ the
                      building because of the fire on the fifth floor.
                    </div>
                   
                    <div class="flex space-x-12 mx-4">
                      <button
                        @click="deactivated()"
                        class="transition duration-300 p-1"
                        :class="{
                          'bg-red-600 text-white  rounded': deactivatedtrue,
                          'bg-transparent': deactivatedfalse,
                        }"
                      >
                        <p><span class="font-bold">a.</span> deactivated</p>
                      </button>
                      <button
                        @click="obtained()"
                        class="transition duration-300 p-1"
                        :class="{
                          'bg-red-600 text-white  rounded': obtainedtrue,
                          'bg-transparent': obtainedfalse,
                        }"
                      >
                        <p><span class="font-bold">b.</span> obtained</p>
                      </button>
                      <button
                        @click="evacuated()"
                        class="transition duration-300 p-1"
                        :class="{
                          'bg-green-300 text-white  rounded': evacuatedtrue,
                          'bg-transparent': evacuatedfalse,
                        }"
                      >
                        <p><span class="font-bold">c.</span> evacuated</p>
                      </button>
                    </div>
                  </li>
                  <li>
                    <div>
                      <span class="font-bold">8.</span> I ____ to the manager
                      about the bad service at the restaurant.
                    </div>
                   
                    <div class="flex space-x-12 mx-4">
                      <button
                        @click="complained()"
                        class="transition duration-300 p-1"
                        :class="{
                          'bg-green-300 text-white  rounded': complainedtrue,
                          'bg-transparent': complainedfalse,
                        }"
                      >
                        <p><span class="font-bold">a.</span> complained</p>
                      </button>
                      <button
                        @click="gossiped()"
                        class="transition duration-300 p-1"
                        :class="{
                          'bg-red-600 text-white  rounded': gossipedtrue,
                          'bg-transparent': gossipedfalse,
                        }"
                      >
                        <p><span class="font-bold">b.</span> gossiped</p>
                      </button>
                      <button
                        @click="socialized()"
                        class="transition duration-300 p-1"
                        :class="{
                          'bg-red-600 text-white  rounded': socializedtrue,
                          'bg-transparent': socializedfalse,
                        }"
                      >
                        <p><span class="font-bold">c.</span> socialized</p>
                      </button>
                    </div>
                  </li>
                  <li>
                    <div>
                      <span class="font-bold">9.</span> The boy asked for his
                      mother's ____ to go to the park.
                    </div>
                   
                    <div class="flex space-x-12 mx-4">
                      <button
                        @click="gesture()"
                        class="transition duration-300 p-1"
                        :class="{
                          'bg-red-600 text-white  rounded': gesturetrue,
                          'bg-transparent': gesturefalse,
                        }"
                      >
                        <p><span class="font-bold">a.</span> gesture</p>
                      </button>
                      <button
                        @click="law()"
                        class="transition duration-300 p-1"
                        :class="{
                          'bg-red-600 text-white  rounded': lawtrue,
                          'bg-transparent': lawfalse,
                        }"
                      >
                        <p><span class="font-bold">b.</span> law</p>
                      </button>
                      <button
                        @click="permission()"
                        class="transition duration-300 p-1"
                        :class="{
                          'bg-green-300 text-white  rounded': permissiontrue,
                          'bg-transparent': permissionfalse,
                        }"
                      >
                        <p><span class="font-bold">c.</span> permission</p>
                      </button>
                    </div>
                  </li>
                  <li>
                    <div>
                      <span class="font-bold">10.</span> We walked through the
                      construction site with extreme ____.
                    </div>
                   
                    <div class="flex space-x-12 mx-4">
                      <button
                        @click="warning()"
                        class="transition duration-300 p-1"
                        :class="{
                          'bg-red-600 text-white  rounded': warningtrue,
                          'bg-transparent': warningfalse,
                        }"
                      >
                        <p><span class="font-bold">a.</span> warning</p>
                      </button>
                      <button
                        @click="hazard()"
                        class="transition duration-300 p-1"
                        :class="{
                          'bg-green-300 text-white  rounded': hazardtrue,
                          'bg-transparent': hazardfalse,
                        }"
                      >
                        <p><span class="font-bold">b.</span> hazard</p>
                      </button>
                      <button
                        @click="caution()"
                        class="transition duration-300 p-1"
                        :class="{
                          'bg-red-600 text-white  rounded': cautiontrue,
                          'bg-transparent': cautionfalse,
                        }"
                      >
                        <p><span class="font-bold">c.</span> caution</p>
                      </button>
                    </div>
                  </li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    falsecolor: Boolean,
    truecolor: Boolean,
    aswer: Function,
    warnedfalse: Boolean,
    warnedtrue: Boolean,
    warned: Function,
    mentionedtrue: Boolean,
    mentionedfalse: Boolean,
    referredtrue: Boolean,
    referredfalse: Boolean,
    installedtrue: Boolean,
    installedfalse: Boolean,
    scrolledtrue: Boolean,
    scrolledfalse: Boolean,
    attachedtrue: Boolean,
    attachedfalse: Boolean,
    generationtrue: Boolean,
    generationfalse: Boolean,
    origintrue: Boolean,
    originfalse: Boolean,
    shifttrue: Boolean,
    shiftfalse: Boolean,
    compulsorytrue: Boolean,
    compulsoryfalse: Boolean,
    qualifiedtrue: Boolean,
    qualifiedfalse: Boolean,
    protectivetrue: Boolean,
    protectivefalse: Boolean,
    sayingtrue: Boolean,
    sayingfalse: Boolean,
    tellingtrue: Boolean,
    tellingfalse: Boolean,
    explainingtrue: Boolean,
    explainingfalse: Boolean,
    effectivetrue: Boolean,
    effectivefalse: Boolean,
    practicaltrue: Boolean,
    practicalfalse: Boolean,
    portabletrue: Boolean,
    portablefalse: Boolean,
    deactivatedtrue: Boolean,
    deactivatedfalse: Boolean,
    obtainedtrue: Boolean,
    obtainedfalse: Boolean,
    evacuatedtrue: Boolean,
    evacuatedfalse: Boolean,
    complainedtrue: Boolean,
    complainedfalse: Boolean,
    gossipedtrue: Boolean,
    gossipedfalse: Boolean,
    socializedtrue: Boolean,
    socializedfalse: Boolean,
    gesturetrue: Boolean,
    gesturefalse: Boolean,
    lawtrue: Boolean,
    lawfalse: Boolean,
    permissiontrue: Boolean,
    permissionfalse: Boolean,
    warningtrue: Boolean,
    warningfalse: Boolean,
    hazardtrue: Boolean,
    hazardfalse: Boolean,
    cautiontrue: Boolean,
    cautionfalse: Boolean,

    mentioned: Function,
    referred: Function,
    installed: Function,
    scrolled: Function,
    attached: Function,
    generation: Function,
    origin: Function,
    shift: Function,
    compulsory: Function,
    qualified: Function,
    protective: Function,
    saying: Function,
    telling: Function,
    explaining: Function,
    effective: Function,
    practical: Function,
    portable: Function,
    deactivated: Function,
    obtained: Function,
    evacuated: Function,
    complained: Function,
    gossiped: Function,
    socialized: Function,
    gesture: Function,
    law: Function,
    permission: Function,
    warning: Function,
    hazard: Function,
    caution: Function,
  },
};
</script>