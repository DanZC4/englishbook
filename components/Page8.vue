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
                    Rewrite the sentences using the word given.
                  </h2>
                </div>

                <ul class="space-y-2">
                  <li>
                    <div class="flex justify-between">
                      <p>
                        <span class="font-bold">1.</span> It is illegal to talk
                        on your cell while driving.
                      </p>
                      <span class="font-bold">law</span>
                    </div>

                    <br />
                    <input
                      type="text"
                      class="
                        bg-gray-100
                        focus:outline-none
                        border-b border-gray-600
                        w-full
                        focus:border-pink-900
                        p-1
                        transition
                        duration-300
                      "
                      value="it is against the law to talk on the phone while driving"
                    />
                  </li>
                  <li>
                    <div class="flex justify-between">
                      <p>
                        <span class="font-bold">2.</span> Smoking in this
                        building is not allowed.
                      </p>
                      <span class="font-bold">permitted</span>
                    </div>
                    <br />
                    <input
                      type="text"
                      class="
                        bg-gray-100
                        focus:outline-none
                        border-b border-gray-600
                        w-full
                        focus:border-pink-900
                        p-1
                        transition
                        duration-300
                      "
                      value="Smoking in this building is not permitted"
                    />
                  </li>
                  <li>
                    <div class="flex justify-between">
                      <p>
                        <span class="font-bold">3.</span> You mustn't use the
                        staff elevator.
                      </p>
                      <span class="font-bold">forbidden</span>
                    </div>
                    <br />
                    <input
                      type="text"
                      class="
                        bg-gray-100
                        focus:outline-none
                        border-b border-gray-600
                        w-full
                        focus:border-pink-900
                        p-1
                        transition
                        duration-300
                      " value="it's forbidden use the staff elevator"
                    />
                  </li>
                  <li>
                    <div class="flex justify-between">
                      <p>
                        <span class="font-bold">4.</span> I know I should be
                        home in bed, but I came to work anyway.
                      </p>
                      <span class="font-bold">supposed</span>
                    </div>
                    <br />
                    <input
                      type="text"
                      class="
                        bg-gray-100
                        focus:outline-none
                        border-b border-gray-600
                        w-full
                        focus:border-pink-900
                        p-1
                        transition
                        duration-300
                      "
                      value="supposed I should be home in bed, but I came to work anyway"
                    />
                  </li>
                </ul>
              </div>
            </div>
            <div class="my-6">
              <div class="w-96">
                <h2 class="font-bold text-gray-800 my-2 flex">
                  <p class="font-bold text-pink-900 mr-2">[.</p>
                  Circle the correct words and add commas where necessary.
                </h2>
              </div>
              <div>
                <ul class="space-y-2">
                  <li>
                    <span class="font-bold">1.</span> George <span class="font-bold text-red-600">whose</span>/ <span class="font-bold">who</span>  wife
                    works as a teacher is coming over for dinner tonight.
                  </li>
                  <li>
                    <span class="font-bold">2.</span> We can meet at the coffee
                    shop <span class="font-bold text-red-600">where</span> / <span class="font-bold">which</span>  is on Grandview Avenue.
                  </li>
                  <li>
                    <span class="font-bold">3.</span> Brenda <span class="font-bold text-red-600">who</span> /  <span class="font-bold">that</span> lives in
                    Denver will visit me next week.
                  </li>
                  <li>
                    <span class="font-bold">4.</span> The hotel <span class="font-bold">which</span>/  <span class="font-bold text-red-600">where</span>  we
                    stayed was kind of far from the beach.
                  </li>
                  <li>
                    <span class="font-bold">5.</span> The elevator <span class="font-bold">where</span> / <span class="font-bold text-red-600">that</span> 
                    is next to the reception desk is out of order.
                  </li>
                  <li>
                    <span class="font-bold">6.</span> Facebook <span class="font-bold">that</span> / <span class="font-bold text-red-600">which</span> is a
                    social media site is popular with young people.
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