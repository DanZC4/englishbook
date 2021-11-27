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
                    <p class="font-bold text-pink-900 mr-2">[.</p>
                    Join the sentences using who, which, that, whose or where.
                  </h2>
                </div>

                <ul class="space-y-2">
                  <li>
                    <span class="font-bold">1.</span> UNICEF is an organization.
                    It helps take care of the health and education of children
                    around the world.
                    <br />
                    <input type="text" class="bg-gray-100 focus:outline-none border-b border-gray-600 w-full focus:border-pink-900 p-1 transition duration-300" value=" UNICEF is an organization. which It helps take care of the health and education of children around the world." />
                  </li>
                  <li>
                    <span class="font-bold">2.</span> Mrs. Sanders lives on the
                    third floor. Her son is a gadget freak.
                    <br />
                    <input type="text" class="bg-gray-100 focus:outline-none border-b border-gray-600 w-full focus:border-pink-900 p-1 transition duration-300" value="Mrs. Sanders lives on the third floor. whose Her son is a gadget freak.
" />
                  </li>
                  <li>
                    <span class="font-bold">3.</span> Mr. Henderson is my
                    employer. He was on the news last night.
                    <br />
                    <input type="text" class="bg-gray-100 focus:outline-none border-b border-gray-600 w-full focus:border-pink-900 p-1 transition duration-300" value="3. Mr. Henderson is my employer.who He was on the news last night.
"/>
                  </li>
                  <li>
                    <span class="font-bold">4.</span> Toronto is a beautiful
                    city. My cousin lives there.
                    <br />
                    <input type="text" class="bg-gray-100 focus:outline-none border-b border-gray-600 w-full focus:border-pink-900 p-1 transition duration-300" value="Toronto is a beautiful city.Where My cousin lives there."/>
                  </li>
                  <li>
                    <span class="font-bold">5.</span> You've met my aunt. She
                    makes amazing pasta dishes.
                    <br />
                    <input type="text" class="bg-gray-100 focus:outline-none border-b border-gray-600 w-full focus:border-pink-900 p-1 transition duration-300" value="5. You've met my aunt. who She makes amazing pasta dishes."/>
                  </li>
                  <li>
                    <span class="font-bold">6.</span> Twitter is used by many
                    people nowadays. It is an online social networking service.
                    <br />
                    <input type="text" class="bg-gray-100 focus:outline-none border-b border-gray-600 w-full focus:border-pink-900 p-1 transition duration-300" value="Twitter is used by many people nowadays. which It is an online social networking service.
"/>
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