<script>
    import Section from './section.svelte';
    let image = '../img/IMG_20201114_211139.jpg';
    let image2 = '../img/IMG_20210128_145855.jpg';
    let image3 = '../img/IMG_20200129_000050.jpg';
</script>

<Section>
    <h2 class="text-5xl text-blue-800 mb-5">¡Cariño no solo contigo, con tú familia!</h2>
    <p class="text-gray-600 text-2xl my-3">
        Es que son tan pero tan simpáticos, cariñosos y amables! Tus papás, hermanos, sobrinas, cuñados, todos todos en verdad
        siempre me han ofrecido apoyo, energía y ganas, pero por sobre todo decirme que te ven contenta, feliz y emocionada cuando
        estamos juntos.
    </p>
    <div class="flex py-10">
        <div class="flex flex-col items-center justify-center w-1/2">
            <img alt="familia" src="{image}" class="w-2/3 shadow-lg rounded-md" style="transform: rotate(-5deg);" />
            <img alt="familia" src="{image2}" class="w-2/3 shadow-lg rounded-md" style="transform: rotate(5deg) translate(0, -10px);" />
            <img alt="familia" src="{image3}" class="w-2/3 shadow-lg rounded-md" style="transform: rotate(-10deg) translate(10px, -15px);" />
        </div>
        <div class="flex flex-col w-1/2">
            <p class="text-gray-600 text-2xl mb-5">
                Es que la paso tan bien contigo y tú familia! Tus sobrinas han llegado a traerte un mar de aventuras, locuras y diversión.
                Sobre todo para mí, porque puta que lo paso bien con los tornaditos con patitas!
                <br /><br />
                jajaja las fotos están locas, pero me gustan porque demuestra el lazo confianza y cariño que se ha ido generando durante nuestra
                relación, lo que creo que hace que estemos seguros uno del otro.
                <br /><br />
                Me alegro poder viajar contigo y tu familia! Estoy tan agradecido de poder vacacionar contigo y tu familia, que me contemplen en sus
                planes de viajes, paseos, panoramas, etc. y conocerte más en esos aspectos de entorno de familia, que es íntimo y de mucha confianza.
            </p>
            <p class="text-gray-600 text-2xl mb-5">
                Bueno, pronto en nuestros planes estarán los viajes solos, donde aprenderemos mucho más uno del otro, y tendremos más tiempo 100% para nosotros 😏.
            </p>
            <p class="text-gray-600 text-2xl mb-5">
                En verdad solo me queda decir que tu familia me encanta y a veces la envidio en la unión y cariño que tienen 🙊!
            </p>
            <p class="text-gray-600 text-2xl">
                Ahh! Hay que sacarnos fotos con la Fefa y la Victoria!
            </p>
        </div>
    </div>
</Section>
