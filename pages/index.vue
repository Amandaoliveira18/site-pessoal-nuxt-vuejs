<template>
    <ProfileInfo 
        :photo="photo"
        title="Jaison Schmidt" 
        subtitle="@jaisonschmidt" 
        headline="Front-end Developer" 
    />
    
    <div class="max-w-xs mx-auto">
        <ButtonAction 
            link="https://wa.me/+5554999776648" 
            icon="💬" 
            text="Whatsapp" />

        <ButtonAction 
            link="https://www.linkedin.com/in/jaison-schmidt-19b80725/" 
            icon="💼" 
            text="Linkedin" />

        <ButtonAction 
            link="https://github.com/jaisonschmidt" 
            icon="🛠" 
            text="Github" />

        <ButtonAction 
            link="https://www.instagram.com/jaisonschmidt/" 
            icon="👨🏽‍💻" 
            text="Instagram" />
    </div>
</template>

<script setup>
    import photo from "../assets/img/picture.jpg";
</script>
