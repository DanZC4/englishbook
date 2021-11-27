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
                    <p class="font-bold text-pink-900 mr-2">B.</p>
                    Complete with the verbs in the box.
                  </h2>
                </div>
                <div class="bg-pink-900 p-4 flex justify-center mb-4 text-gray-100 font-bold shadow-xl">
                  <div class="flex flex-wrap justify-center w-full px-24">
                    <p class="pr-4">Install</p>
                    <p class="pr-4">drop</p>
                    <p class="pr-4">shut down</p>
                    <p class="pr-4">scroll</p>
                    <p class="pr-4">drag</p>
                    <p class="pr-4">tap</p>
                    <p class="pr-4">attach</p>
                    <p class="pr-4">press</p>
                    <p class="pr-4">deactivate</p>
                  </div>
                </div>
                <ul class="space-y-2">
                  <li>
                    <span class="font-bold">1.</span> Another way of saying
                    "turn off" your computer is  <input
                      type="text"
                      class="
                        bg-transparent
                        focus:outline-none
                        border-b border-gray-600
                        focus:border-pink-900
                        w-24
                        px-1
                        transition
                        duration-300
                      "
                      value="shut down"
                    /> .
                  </li>
                  <li>
                    <span class="font-bold">2.</span> To make the keys on a
                    keyboard or phone write letters, numbers, etc. you have to
                    <input
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
                      value="tap"
                    /> them.
                  </li>
                  <li>
                    <span class="font-bold">3.</span> When you select part of a
                    text or image, then move it and place it in its new
                    position, you <input
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
                      " value="drag"
                    /> and <input
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
                      " value="drop"
                    /> it.
                  </li>
                  <li>
                    <span class="font-bold">4.</span> After you download a new
                    program onto your computer, you need to <input
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
                      value="install"
                    />
                    it.
                  </li>
                  <li>
                    <span class="font-bold">5.</span> The verb used instead of
                    "press" or "click" on a touchscreen device is
                    <input
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
                      value="press"
                    />.
                  </li>
                  <li>
                    <span class="font-bold">6.</span> When you want to send an
                    image or a separate document with an e-mail, you have to
                    <input
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
                      " value="attach"
                    /> it.
                  </li>
                  <li>
                    <span class="font-bold">7.</span> When you want to stop
                    using an e-mail account you <input
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
                      " value="deactivate

"
                    /> it.
                  </li>
                  <li>
                    <span class="font-bold">8.</span>When you move up or down a
                    web page or document, you <input
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
                      value="scroll"
                    />.
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