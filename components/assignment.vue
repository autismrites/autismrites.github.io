<template>
  <div>
    <div class="my-8 flex items-center justify-between md:justify-center">
      <span
        class="border-b-2 border-indigo-500 border-t-2 w-8 md:w-24 inline-block mr-2 rounded"
      ></span>

      <h1 class="text-gray-800 md:text-2xl font-bold text-center font-serif">
        Students Assignment Info
      </h1>

      <span
        class="border-b-2 border-indigo-500 border-t-2 w-8 md:w-24 inline-block ml-2 rounded"
      ></span>
    </div>

    <p class="mb-10">
      All assignments will be listed here in order from latest to oldest. once the class
      has completed each respective assignment, the list will be removed.
    </p>

    <div class="text-left mb-8 font-serif">
      <h1 class="text-gray-800 text-4xl font-bold mb-2">Scratch Assignment</h1>
      <p class="text-gray-800 text-2xl mb-2">17 July 2021</p>

      <div class="border-indigo-500 border-b-2 border-t-2 w-32 md:w-40 rounded"></div>
    </div>
    <p class="mb-10">
      In this assigmnet, you will investigate what is wrong with the code and find a
      solution for each of the five Debugging challenges.
    </p>
    <div>
      <div class="grid grid-flow-col gap-4 mb-10">
        <a href="https://scratch.mit.edu/projects/24271192" target="#"
          ><button class="btn-indigo">Debug-it 4.1</button></a
        >
        <a href="https://scratch.mit.edu/projects/24271303" target="#"
          ><button class="btn-indigo">Debug-it 4.2</button></a
        >
        <a href="https://scratch.mit.edu/projects/24271446" target="#"
          ><button class="btn-indigo">Debug-it 4.3</button></a
        >
        <a href="https://scratch.mit.edu/projects/24271475" target="#"
          ><button class="btn-indigo">Debug-it 4.4</button></a
        >
        <a href="https://scratch.mit.edu/projects/24271560" target="#"
          ><button class="btn-indigo">Debug-it 4.5</button></a
        >
      </div>

      <div class="text-left mb-8 font-serif">
        <h1 class="text-gray-800 text-4xl font-bold mb-2">English Assignment</h1>
        <p class="text-gray-800 text-2xl mb-2">12 July 2021</p>

        <!-- change "border-indigo-500" to change the color -->
        <div class="border-indigo-500 border-b-2 border-t-2 w-32 md:w-40 rounded"></div>
      </div>

      <div class="grid justify-center mb-8">
        <div>
          <div class="text-center mb-8">
            <h1 class="text-4xl mb-2">Interviewing Guides</h1>
            <h3 class="text-xl">What NOT to do</h3>
          </div>
          <ul class="text-lg">
            <li class="mb-3">
              &bull; Don’t ask something that you already know the answer to
            </li>
            <li class="mb-3">&bull; Don’t answer your own questions</li>
            <li class="mb-3">&bull; Don’t speak more than the interviewee</li>
            <li class="mb-3">&bull; Don’t show agreement or disagreement</li>
            <li class="mb-3">&bull; Don’t forget to take notes!!!</li>
          </ul>
        </div>
        <div>
          <div class="text-center mb-8">
            <h1 class="text-4xl mb-2">Historic Research</h1>
            <h3 class="text-xl">Yes, it's homework! :)</h3>
          </div>
          <h3 class="mb-6 text-2xl">
            Interview Relatives who are in their 20’s, 40’s, 60’s
          </h3>
          <ul class="text-lg">
            <li class="mb-3">&bull; How did they used to send messages</li>
            <li class="mb-3">&bull; How did they travel</li>
            <li class="mb-3">
              &bull; What technology that exists today, that didn't exist 20, 40 and 60
              years ago.
            </li>
            <li class="mb-3">&bull; What they did to have fun when they were your age</li>
          </ul>
        </div>
      </div>

      <a href="https://bit.ly/3iiE95d" target="#"
        ><button class="btn-indigo mb-10">English Assignment Portal</button></a
      >

      <div></div>
      <div class="text-left mb-8 font-serif">
        <h1 class="text-gray-800 text-4xl font-bold mb-2">Scratch Assignment</h1>
        <p class="text-gray-800 text-2xl mb-2">10 July 2021</p>

        <div class="border-indigo-500 border-b-2 border-t-2 w-32 md:w-40 rounded"></div>
      </div>

      <h1 class="mb-6 text-xl font-bold">Interactive Maze Game</h1>
      <div class="flex mb-6">
        <h3 class="mr-4 btn-outline">Abdullah</h3>
        <h3 class="btn-outline">Faiq</h3>
      </div>
      <div class="mb-4"><img src="~/static/img/maze_img.jpg" alt="" /></div>
      <p class="mb-6">
        In this project, you will create a game. This game includes interactions between
        sprites, score, and levels. You move a sprite from the start of a maze to the end
        without touching the walls.
        <span class="font-bold">Work with your partner</span> and show us how can you add
        the three game elements below?
      </p>

      <ul class="mb-10">
        <li>&bull; Add Multiple Levels</li>
        <li>&bull; Display Score</li>
        <li>&bull; Time Limit</li>
      </ul>
      <h1 class="mb-6 text-xl font-bold">Interactive Srolling Game</h1>
      <div class="flex mb-6">
        <h3 class="mr-4 btn-outline">Abdurrahman</h3>
        <h3 class="btn-outline">Najmi</h3>
      </div>
      <div class="mb-4"><img src="~/static/img/scroll_img.jpg" alt="" /></div>
      <p class="mb-6">
        In this project, you will create a game. This game includes interactions between
        sprites, score, and levels. The game is similar to Flappy Bird, where the goal is
        to keep an object from falling to the ground or touching certain objects.

        <span class="font-bold">Work with your partner</span> and show us how can you add
        the three game elements below?
      </p>

      <ul class="mb-10">
        <li>&bull; Add Difficulty Levels</li>
        <li>&bull; Changes Backdrop</li>
        <li>&bull; Use Different Input</li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style></style>
