<template>
  <div class="min-h-screen grid place-items-center bg-gradient-to-r from-[#232526] to-[#7e7e7e] z-10 px-4">
    <div class="grid gap-1 justify-items-center p-6 w-full sm:max-w-lg rounded-3xl overflow-hidden backdrop-blur-lg bg-black/5 z-10  shadow-2xl shadow-neutral-400">
        <img src="../assets/img/profile.webp" alt="ProfileImage" class="mx-auto rounded-full h-44" >
        <h1 class="text-white text-4xl font-extralight">Marco Rizzato</h1>
        <p class="text-gray-400">A passionate full stack developer</p>
        <div class="flex justify-evenly w-full mt-10">
          <SocialIcon url="https://www.facebook.com/marco.rizzato95/" name="Facebook" icon-path="social-icons/facebook.svg"></SocialIcon>
          <SocialIcon url="https://www.instagram.com/rizzato_95/" name="Instagram" icon-path="social-icons/instagram.svg"></SocialIcon>
          <SocialIcon url="https://www.linkedin.com/in/marco-rizzato-954646bb/" name="LinkedIn" icon-path="social-icons/linkedin.svg"></SocialIcon>
          <SocialIcon url="https://github.com/Rizzato95/" name="Instagram" icon-path="social-icons/github.svg"></SocialIcon>
          <SocialIcon url="mailto:rizzato.marco95@gmail.com" name="Mail" icon-path="social-icons/mail.svg"></SocialIcon>
        </div>
      </div>
  </div>
</template>