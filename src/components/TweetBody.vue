<template>
    <div class="flex flex-col px-3">
        <h1 class="text-2xl mb-2">Real talk. Are hotdogs sandwiches?</h1>
        <img class="rounded-2xl h-60" 
        src="https://images.unsplash.com/photo-1541214113241-21578d2d9b62?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80" alt="">
        <p class="text-gray-400 text-sm py-2 border-b">
            <span>9:15 AM </span>
            <span> 10/12/2020</span>
            <span class="main-color font-normal"> Twitter for Android</span>
        </p>
        <p class="text-gray-400 py-2 border-b">
            <span class="text-black font-bold">3</span>
            <span class="mr-4"> Retweets</span>
            <span class="text-black font-bold">22 </span>
            <span>Likes</span>
        </p>
    </div>
</template>

<script>
export default {
    name: "TweetBody"
}
</script>