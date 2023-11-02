<template>
  <main class="flex flex-col gap-y-8">
    <section class="top">
      <div class="flex flex-col items-center gap-5">
        <h3 class="text-4xl font-extrabold pt-5">Hello it's me</h3>
        <img src="/public/main.jpg" class="h-55 w-50 rounded-full" />
        <p class="text-justify w-2/3">
          Lorem ipsum dolor sit amet, ei quodsi disputando vix. Pro at lorem quidam, no
          harum dicit nam. Te augue laoreet adversarium has. Duo eu discere volutpat
          adversarium, duo error accusamus te. Tempor mnesarchum nam cu, saperet
          efficiendi mea an. Vis facilis invenire convenire an, eos et lorem commodo
          praesent, aperiam utroque has ne.
        </p>
        <div class="flex flex-row gap-4">
          <a class="btn text-white rounded-md bg-red-600 hover:bg-red-600">Linkedin</a>
          <a class="btn text-white rounded-md bg-green-600 hover:bg-green-600">Resume</a>
          <a class="btn text-white rounded-md bg-blue-600 hover:bg-blue-600">Github</a>
        </div>
      </div>
    </section>
    <section class="flex flex-col gap-8 p-10">
      <h1 class="text-4xl font-extrabold p-4"><a href="#">Projects</a></h1>
      <div class="grid lg:grid-cols-2 gap-10 items-center justify-items-center mx-20">
        <a class="card h-full w-full shadow-2xl group p-5" href="#">
          <figure>
            <img class="scale-75" src="/public/text-to-speech.png" alt="text-to-speech" />
          </figure>
          <div class="card-body">
            <h3 class="text-xl lg:text-2xl font-bold group-hover:link">
              Convert text file format to mp3 format using of Google api.
            </h3>
            <span class="text-sm">27 Aug 2023 | 5 minutes</span>
            <p>
              How to convert text file format to audio format by using google translate
              api to translate to TAMIL language.
            </p>
          </div>
        </a>
        <a class="card h-full w-full shadow-2xl group p-5" href="#">
          <figure>
            <img class="scale-75" src="/public/text-to-speech.png" alt="text-to-speech" />
          </figure>
          <div class="card-body">
            <h3 class="text-xl lg:text-2xl font-bold group-hover:link">
              Convert txt file format to mp3 format using of Google api.
            </h3>
            <span class="text-sm">27 Aug 2023 | 5 minutes</span>
            <p>
              An article on how to convert text file format to audio format by using
              google translate api to translate to TAMIL language.
            </p>
          </div>
        </a>
      </div>
    </section>
  </main>
</template>
