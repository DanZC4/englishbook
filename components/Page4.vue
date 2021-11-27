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
                    Complete with who, which, that, whose or where. If they can be omitted, put them in parentheses.
                  </h2>
                </div>
                <ul class="space-y-2">
                  <li>
                    <span class="font-bold">A:</span> Do you know a good language school <span class="font-bold">1</span> <input
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
                      value="where"
                    /> I can learn Russian?
                  </li>
                  <li>
                    <span class="font-bold">B:</span> Yes. Actually, I have a colleague <span class="font-bold">2</span> <input
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
                      " value="whose"
                    /> wife is a secretary at a very good language school downtown.
                  </li>
                  <li>
                    <span class="font-bold">A:</span> Great! 
                  </li>
                  <li>
                      <span class="font-bold">B:</span> Hold on! I'm pretty sure you met him at my barbecue last summer. His name is George.
                  </li>
                  <li>
                     <span class="font-bold">A:</span> Is that the guy <span class="font-bold">3</span> <input
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
                      value="who"
                    /> was making the sandwiches?
                  </li>
                  <li>
                    <span class="font-bold">B:</span> No, that was Brian. George is the one <span class="font-bold">4</span> <input
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
                      " value="that"
                    /> I was talking to about sports.
                  </li>
                  <li>
                    <span class="font-bold">A:</span> Oh, I remember him. The Mets fan.
                  </li>
                  <li>
                    <span class="font-bold">B:</span>Right! Well, I can give you his number and you can talk to his wife about the details. But why Russian?
                  </li>
                  <li>
                   <span class="font-bold">A:</span>It's a language <span class="font-bold">5</span> <input
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
                      value="which"
                    /> has always fascinated me and it's something <span class="font-bold">6</span> <input
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
                      value="that"
                    /> I've wanted to do since I visited Moscow.
                  </li>
                   <li>
                   <span class="font-bold">B:</span>You've been to Moscow? Wow! It's certainly a city <span class="font-bold">7</span> <input
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
                      value="which"
                    /> is worth visiting.
                  </li>
                   <li>
                   <span class="font-bold">A:</span>You can say that again!
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