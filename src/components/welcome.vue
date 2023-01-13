<script setup>

    import {ref} from 'vue'
    
    const name = ref('')
    const email = ref( '')
    const pass = ref('')
    const error = ref('')

    const  login = () => {
        if (!name.value  || !email.value || !pass.value ) {
            error.value = 'Fill in all the fields!'
        } else {
            console.log(name.value,"\n",email.value, "\n",pass.value)
            
        }
    }
</script>

<template>

    <div class="container">
        
        <div class="header">
            <h1>Welcome!</h1>
            <h3>Enter your details to register.</h3>
            <div class="error">
                {{ error }}
            </div>
        </div>
        
        <div class="inputContainer">
            <font-awesome-icon class="icon" icon="fa-solid fa-user-secret" />
            <form class="input" @submit.prevent="login">
                <input type="text" placeholder="Your fullname" v-model="name">
                <input type="email" placeholder="Your Email adress" v-model="email">
                <input type="password" placeholder="your password" v-model="pass">
                <input class="button" type="submit" value="Submit">
            </form>
        </div>

        <div class="corporation">
            <h2>&copy; TailorStyle</h2>
            <h2>13.01.2023</h2>
        </div>


    </div>

</template>

<style scoped>
</style>