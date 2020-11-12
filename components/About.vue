<template>
    <div class="bg-black background py-32 lg:grid lg:grid-cols-2 lg:py-0 md:grid md:grid-cols-2 md:py-0">
        <div>
            <img src="../assets/img/Johnlennon.png" alt="gambar" class="hidden lg:block h-full md:block w-3/4">
        </div>
        <div class="text-white flex flex-col text-right mr-10 ml-10 lg:my-auto lg:mr-24 lg:mb-32">
            <h5>ROCKINTERVIEW</h5>
            <h4>JOHN ANGELZ</h4>
            <p class="ml-24">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quasi nihil explicabo, quisquam ipsam quam aliquam alias nam eum quas at recusandae tempora inventore expedita iure in veniam reprehenderit! Maiores, animi.</p>
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
    .background{
        background-image: url(../assets/img/Roadmann.png);
        background-repeat: no-repeat;
        background-position: center;
    }
    h5{
        font-family: 'Poppins', sans-serif;
        font-size: 18px;
        font-style: normal;
        font-weight: 600;
        line-height: 27px;
    }
    h4{
        font-family: "Playfair Display";
        font-size: 72px;
        font-style: normal;
        font-weight: 700;
        line-height: 95.98px;
        color: #ED1B24;
    }
    p{
        font-family: 'Poppins', sans-serif;
        font-style: normal;
        font-weight: normal;
        font-size: 18px;
        line-height: 27px;
    }
</style>