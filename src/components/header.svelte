<script>
    let image = '../img/149598732_125943059343558_546061543934208612_n.jpg';
</script>

<div class="w-full h-auto flex flex-col lg:flex-row py-10 lg:py-32">
    <div class="w-full lg:w-1/2 px-3 flex flex-col justify-center">
        <h1 class="text-6xl text-blue-800 font-bold mb-5 leading-tight">¡Te amo tanto mucho mi amor!</h1>
        <p class="text-gray-600 text-2xl mb-10">
            Son 7 años de <strong>mucho mucho amor</strong>! 7 añitos donde he aprendido tanto
            de ti, desde que despiertas y te acuestas, sobre todo juntos que es algo que me encanta! 🥰
        </p>
        <p class="text-gray-600 text-2xl font-bold">
            ¿Sabías que nos vimos por primera vez desde hace 14 años?
        </p>
        <button class="appearance-none mt-10 font-bold text-xl border-none bg-green-500 text-white rounded-full px-4 py-2 w-full lg:w-1/2 shadow-lg">Naah en serio?</button>
    </div>
    <div class="w-full lg:w-1/2 flex items-center justify-center mt-32 lg:m-0">
            <img src={image} class="w-2/3 shadow-lg heart-clip" />
    </div>
</div>

<style global>
    .heart-clip {
        width: 250px;
        height: 250px;
        object-fit: cover;
        clip-path: path('M213.1,6.7c-32.4-14.4-73.7,0-88.1,30.6C110.6,4.9,67.5-9.5,36.9,6.7C2.8,22.9-13.4,62.4,13.5,110.9 C33.3,145.1,67.5,170.3,125,217c59.3-46.7,93.5-71.9,111.5-106.1C263.4,64.2,247.2,22.9,213.1,6.7z');
        transform: scale(1.7);
        animation: heartbeat 2s infinite;
    }

    @keyframes heartbeat {
        0%
        {
            transform: scale( 1.75 );
        }
        20%
        {
            transform: scale( 1.20 );
        }
        40%
        {
            transform: scale( 1.75 );
        }
        60%
        {
            transform: scale( 1.20 );
        }
        80%
        {
            transform: scale( 1.75 );
        }
        100%
        {
            transform: scale( 1.75 );
        }
    }
</style>
