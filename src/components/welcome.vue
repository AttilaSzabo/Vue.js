<script setup></script>

<template>

    <div class="container">
        
        <div class="header">
            <h1>Welcome!</h1>
            <h3>Enter your details to register.</h3>
        </div>
    
        <div class="inputContainer">
            <font-awesome-icon class="icon" icon="fa-solid fa-user-secret" />
            <form class="input">
                <input type="text" name="fullname" placeholder="Your fullname">
                <input type="email" name="email" placeholder="Your Email adress">
                <input type="password" name="passwords" placeholder="your password">
                <input class="button" type="button" value="Submit">
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