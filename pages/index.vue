<template>
  <div class="w-full h-full min-h-screen bg-gray-200">
    <div class="p-12">
      <div
        class="w-1/2 flex flex-col p-8 mx-auto bg-white border-t-8 border-purple-400 rounded-lg shadow-xl"
      >
        <div class="flex">
          <Logo class="w-16 h-12" />
          <div class="font-bold p-2">Me comi un paraguas y ahora soy impermeable</div>
        </div>
        <div class="text-sm p-2">
          <span class="break-words">
            La increible historia de como empece fumadisimo a pensar que podia aprender a
            programar con AI y acabe en un yate con JoJo al timon surcando el espacio tiempo.
          </span>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Logo from "~/components/Logo";
export default {
  name: "Indice",
  components: { Logo }
};
</script>
