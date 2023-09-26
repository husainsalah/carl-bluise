<template>
  <main class="mx-auto max-w-4xl space-y-6">
    <div class="flex gap-14 align-center grid grid-flow-col h-full w-full p-64">
      <div class="flex bg-white min-h-full min-w-full">
        <div class="container flex align-center grid grid-flow-col h-full w-full p-64">
          <div class="logo">
            <a class="link" href="/indexBKP">
              <div class="flex w-full mx-auto my-auto">
                <img src="~/assets/images/logo.png" alt="Carl Craig Logo" />
              </div>
            </a>
          </div>
        </div>
        <a href="/indexBKP">Music</a> | <a href="/indexBKP">Art</a>
      </div>
    </div>
  </main>
</template>
<style scoped>
.container {
  /*background-image: url('~/assets/images/robot_webpage-wh-op-20.png');*/
  background-repeat: no-repeat;
  background-position: center;
  max-width: none;
  height: 100%;
  width: 100vw;
  transition: opacity 0.3s ease-in;
  object-fit: cover;
  position: fixed;
  top: 0;
  left: 0;
}
video {
  object-fit: cover;
  position: fixed;
  top: 0;
  left: 0;
}
.logo {
  @apply flex w-full h-full my-auto mx-auto object-cover;

  vertical-align: middle;
  width: 60%;
}

.link {
  @apply flex min-h-full mx-auto min-w-full my-auto object-cover;
}

.logo:hover {
  @apply object-cover -translate-y-1;
}

.logo img {
  vertical-align: middle;
}
</style>
