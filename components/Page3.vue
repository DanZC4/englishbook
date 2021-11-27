<template>
  <div class="flex justify-center pt-24">
    <div class="page bg-gray-100 shadow-2xl text-sm text-gray-900">
      <div class="p-6">
        <div>
          <div>
            <h1 class="text-xl font-bold text-pink-900">Vocabulary</h1>
            <div class="mb-2">
              <div class="w-96">
                <h2 class="font-bold text-gray-800 my-2 flex">
                  <p class="font-bold text-pink-900 mr-2">R.</p>
                  Read the extracts from the text. What do the phrases in bold
                  mean?
                </h2>
              </div>
              <div class="mb-2 w-72">
                <div>
                  <i>it's difficult to </i
                  ><span class="font-bold">tell the difference </span
                  ><i
                    >between humans "talking" and birds "tweeting." At least,
                    most foreigners would </i
                  ><span class="font-bold">say so.</span>
                </div>
              </div>
              <div>
                <div class="w-96">
                  <h2 class="font-bold text-gray-800 mb-2 flex">
                    <p class="font-bold text-pink-900 mr-2">B.</p>
                    Complete the sentences with the correct form of tell or say
                    to form collocations.
                  </h2>
                </div>
                <ul class="space-y-2">
                  <li>
                    1. You should <input
                      type="text"
                      class="
                        bg-gray-100
                        focus:outline-none
                        border-b border-gray-600
                        focus:border-pink-900
                        w-24
                        px-1
                        transition
                        duration-300
                      "
                     value="say"/> <span class="font-bold">thank you</span> to Amanda for buying you
                    such a nice gift.
                  </li>
                  <li>
                    2. I was in the neighborhood so I decided to stop by and <input
                      type="text"
                      class="
                        bg-gray-100
                        focus:outline-none
                        border-b border-gray-600
                        focus:border-pink-900
                        w-24
                        px-1
                        transition
                        duration-300
                      "
                      value="say"
                    /> <span class="font-bold">hello</span>.
                  </li>
                  <li>
                    3. Rita would never <input
                      type="text"
                      class="
                        bg-gray-100
                        focus:outline-none
                        border-b border-gray-600
                        focus:border-pink-900
                        w-24
                        px-1
                        transition
                        duration-300
                      "
                      value="tell"
                    /> <span class="font-bold">a secret</span> that she promised to keep. You
                    can trust her.
                  </li>
                  <li>
                    4. Tina <input
                      type="text"
                      class="
                        bg-gray-100
                        focus:outline-none
                        border-b border-gray-600
                        focus:border-pink-900
                        w-24
                        px-1
                        transition
                        duration-300
                      "
                      value="tell"
                    /> us <span class="font-bold">a joke</span> yesterday but I don't
                    remenber it.
                  </li>
                  <li>
                    5. I can't believe that Frank didn't <input
                      type="text"
                      class="
                        bg-gray-100
                        focus:outline-none
                        border-b border-gray-600
                        focus:border-pink-900
                        w-24
                        px-1
                        transition
                        duration-300
                      "
                      value="say"
                    /> <span class="font-bold">sorry</span> after he
                    accidentally pushed me. How rude!
                  </li>
                  <li>
                    6. Now that my younger brother has learned to <input
                      type="text"
                      class="
                        bg-gray-100
                        focus:outline-none
                        border-b border-gray-600
                        focus:border-pink-900
                        w-24
                        px-1
                        transition
                        duration-300
                      "
                      value="say"
                    /> <span class="font-bold">time</span>, I'm
                    going to buy him a watch.
                  </li>
                  <li>7. Don't just sit there. <input
                      type="text"
                      class="
                        bg-gray-100
                        focus:outline-none
                        border-b border-gray-600
                        focus:border-pink-900
                        w-24
                        px-1
                        transition
                        duration-300
                      "
                      value="say"
                    /> <span class="font-bold">something</span>!</li>
                  <li>8. OK, childen. Let me <input
                      type="text"
                      class="
                        bg-gray-100
                        focus:outline-none
                        border-b border-gray-600
                        focus:border-pink-900
                        w-24
                        px-1
                        transition
                        duration-300
                      "
                      value="tell"
                    /> you a <span class="font-bold">story</span>.</li>
                  <li>
                    9. I asked my brother if I could borrow his car and he <input
                      type="text"
                      class="
                        bg-gray-100
                        focus:outline-none
                        border-b border-gray-600
                        focus:border-pink-900
                        w-24
                        px-1
                        transition
                        duration-300
                      "
                      value="say"
                    /> <span class="font-bold">yes</span>.
                  </li>
                  <li>
                    10. I always know when Jack is <input
                      type="text"
                      class="
                        bg-gray-100
                        focus:outline-none
                        border-b border-gray-600
                        focus:border-pink-900
                        w-24
                        px-1
                        transition
                        duration-300
                      "
                      value="tell"
                    /> <span class="font-bold">lies</span> and when he's <input
                      type="text"
                      class="
                        bg-gray-100
                        focus:outline-none
                        border-b border-gray-600
                        focus:border-pink-900
                        w-24
                        px-1
                        transition
                        duration-300
                      "
                      value="say"
                    /> <span class="font-bold">the truth</span>.
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
    words: Array,
  },
};
</script>