<template>
  <div class="container mx-auto my-10 w-[950px] border p-8">
    <div class="flex gap-3">
      <div class="cursor-pointer opacity-50 hover:opacity-100">
        <svg
          class="h-6 w-6"
          fill="none"
          stroke="currentColor"
          viewBox="0 0 24 24"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M19 7l-.867 12.142A2 2 0 0116.138 21H7.862a2 2 0 01-1.995-1.858L5 7m5 4v6m4-6v6m1-10V4a1 1 0 00-1-1h-4a1 1 0 00-1 1v3M4 7h16"
          ></path>
        </svg>
      </div>
      <div class="cursor-pointer opacity-50 hover:opacity-100">
        <svg
          class="h-6 w-6"
          fill="none"
          stroke="currentColor"
          viewBox="0 0 24 24"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M15.232 5.232l3.536 3.536m-2.036-5.036a2.5 2.5 0 113.536 3.536L6.5 21.036H3v-3.572L16.732 3.732z"
          ></path>
        </svg>
      </div>
    </div>
    <h2 class="text-center text-4xl font-bold">(title)Lorem ipsum dolor</h2>
    <h6 class="mt-10 text-sm font-semibold text-gray-600">
      (date)28/09/2022 07:46
    </h6>
    <div>
      <h2 class="text-xl font-semibold">Description:</h2>
      <p class="">
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Commodi nihil
        optio qui rem pariatur saepe incidunt at itaque maxime accusamus?
      </p>
    </div>
    <div class="mt-2 mb-8 flex flex-wrap gap-5">
      <p class="rounded-lg bg-gray-300 p-1 text-sm text-gray-700">#tag</p>
    </div>
    <div>
      <div class="flex">
        <svg
          class="mx-5 h-6 w-6"
          fill="none"
          stroke="currentColor"
          viewBox="0 0 24 24"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M5 13l4 4L19 7"
          ></path>
        </svg>
        <span class="text-lg font-semibold text-green-700"> task finish</span>
      </div>
      <div class="flex">
        <svg
          class="mx-5 h-6 w-6"
          fill="currentColor"
          viewBox="0 0 20 20"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            fill-rule="evenodd"
            d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z"
            clip-rule="evenodd"
          ></path>
        </svg>
        <span class="text-lg font-semibold text-red-700">
          task not finished
        </span>
      </div>
    </div>
  </div>
</template>
