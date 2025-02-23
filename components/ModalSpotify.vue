<template>
    <div v-if="isOpen" class="fixed inset-0 flex items-center justify-center bg-black bg-opacity-50">
        <div class="bg-white p-6 rounded-lg shadow-lg w-11/12 max-w-lg">
            <h2 class="text-xl font-semibold mb-4">Minha playlist Spotify</h2>
            <iframe style="border-radius:12px"
                src="https://open.spotify.com/embed/playlist/3utu1iPk88ICUsW1mlOxvH?utm_source=generator" width="100%"
                height="352" frameBorder="0" allowfullscreen=""
                allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture"
                loading="lazy"></iframe>
            <button @click="closeModal" class="mt-4 px-4 py-2 bg-red-500 text-white rounded">Fechar</button>
        </div>
    </div>
</template>

<script setup>
import { defineProps, defineEmits } from "vue";

defineProps({
    isOpen: Boolean, // Recebe do pai se o modal está aberto
});
const emit = defineEmits(["close"]);

function closeModal() {
    emit("close"); // Dispara evento para fechar o modal
}
</script>