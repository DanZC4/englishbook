<template>
  <div class="flex justify-center pt-24">
    <div class="page bg-gray-100 shadow-2xl text-sm text-gray-900">
      <div class="p-6">
        <div>
          <div>
            <h1 class="text-2xl font-bold text-pink-900">Speaking</h1>
            <div class="mb-2">
              <h2 class="font-bold text-gray-800 mb-2">Discuss in groups. Use some of the words/phrases given</h2>
              <div>
                <ul class="space-y-2">
                  <li>
                    How do you communicate with the different people in your
                    life?
                  </li>
                  <li>
                    What are some popular social networking sites people your
                    age use and what do they use them for?
                  </li>
                  <li>
                    What are the advantages and disadvantages of smartphones?
                  </li>
                  <li>How has communication changed pleple's lives?</li>
                  <li>
                    What do you think the future of communication will be like?
                  </li>
                </ul>
              </div>
            </div>
            <div class="flex flex-wrap">
              <div class="bg-blue-200 p-2 mb-4 ">
                <div class=" flex flex-wrap w-full ">
                  <p v-for="word in words" :key="word.id" class="pr-4">
                      {{ word.span }}
                  </p>
                </div>
              </div>
              <div class="border-4 border-gray-400 w-80 mr-4">
                <div class="border-b border-gray-400 pl-2 py-2">
                  <h3 class="font-bold">Talking time to think</h3>
                  <ul>
                    <li>Well, let's see now...</li>
                    <li>Well, let me think...</li>
                    <li>Umm, give me a minute..</li>
                    <li>You know,...</li>
                  </ul>
                </div>
                  <div class="border-b border-gray-400 pl-2 py-2">
                  <h3 class="font-bold">Interrupting politely</h3>
                  <ul>
                    <li>Sorry to interrupt, but...</li>
                    <li>Can I add something?</li>
                    <li>Could I say somehting before you continue?</li>
                    <li>May i interrupt you for a second?</li>
                    <li>Holp on. Are you saying that...?</li>
                  </ul>
                </div>
                  <div class="border-b border-gray-400 pl-2 py-2">
                  <h3 class="font-bold">Getting back to the topic</h3>
                  <ul>
                    <li>Anyway, as I was saying...</li>
                    <li>Now, what was I saying?</li>
                    <li>Now, where I was?</li>
                  </ul>
                </div>
              </div>
              <div class="bg-gray-600 text-gray-100 p-2 pt-4 text-xs w-48 h-56 space-y-2 font-bold">
                <p>
                  When discussing a topic, take turns to speak. Listen to what the other person is saying and try not to interrupt him/her frequently. If you need to interrupt, do it politely.
                </p>
                <p>When it's your turn to speak and you need more time to think about what to say, avoid long pauses. Use phrases which help you gain time.</p>
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