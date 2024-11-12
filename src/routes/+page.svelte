<script>
    import banner from "$lib/assets/bg1.webp";
    import tie from "$lib/assets/tie.webp";
    import material from "$lib/assets/material.png";
    import MaterialTwo from "$lib/assets/MaterialTwo.jpg";
    import Icon from "$lib/assets/icon.png";
    import Construction from "$lib/assets/construction.webp";
    import FirstSlide from "$lib/assets/FirstSlide.jpg";
    import SecondSlide from "$lib/assets/SecondSlide.jpg";
    import ThirdSlide from "$lib/assets/ThirdSlide.jpg";
    import Headphone from "$lib/assets/headphone.png";
</script>

<section class="px-4 md:px-8">
    <div class="relative">
        <p class="bg-[#003f72] bg-opacity-50 rounded-xl text-white p-8 md:p-20 leading-normal absolute z-10 top-0 left-0 md:w-[80vw] lg:w-[60vw] text-2xl md:text-5xl">
            "MSW scaffolding utilizes an outstanding access system that effectively overcomes various engineering challenges."
        </p>
        <img src={banner} class="w-full h-[50vh] md:h-[70vh] lg:h-[80vh] object-cover opacity-80" alt="Banner">
    </div>
</section>

<section class="flex flex-col md:flex-row justify-center items-center py-8 space-y-8 md:space-y-0 md:space-x-8 px-4 md:px-8">
    <img src={tie} class="h-auto w-full md:w-1/2 object-cover rounded-lg" alt="Tie">
    <div class="text-lg md:text-xl space-y-4 md:w-1/2">
        <h1 class="text-[#003f72] font-semibold">More About Company</h1>
        <p>At Mainee Steel Works Pvt Ltd. (MSW), we take immense pride in being your trusted rental scaffolding service provider based in India. Our commitment is to offer specialized scaffolding solutions designed to meet the diverse needs of clients across India.

Our team, comprised of experienced engineering professionals, possesses an in-depth understanding of the construction industry. We prioritize your requirements, recognizing the pivotal elements on a job site. Above all, your safety holds the utmost importance to us. Scaffolding safety isn't merely a consideration; it serves as the cornerstone of everything we do.

At MSW, our commitment to scaffolding safety is reflected in various ways. As an ISO certified company, we adhere rigorously to the highest safety and environmental standards. Our dedication surpasses mere compliance, as we strive to set new industry benchmarks.

Every scaffolding solution we offer embodies our commitment to safety, quality, and excellence. We aim to provide you with peace of mind on every job site.</p>
        <button class="bg-[#003f72] text-white hover:bg-black py-2 px-4 rounded">Make Appointment</button>
    </div>
</section>

<section class="flex flex-col items-center py-8 px-4 md:px-8 space-y-8">
    <h1 class="text-3xl md:text-5xl lg:text-6xl font-serif text-[#003f72] text-center">Journey Of Sustainable Growth</h1>
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6 w-full max-w-6xl">
        <div class="relative">
            <img src={material} alt="Material Selection" class="w-full h-[30vh] md:h-64 object-cover rounded-lg">
            <h1 class="absolute bottom-2 left-2 w-full text-center text-white bg-black bg-opacity-70 py-2 text-xl md:text-2xl font-semibold">Material Selection</h1>
        </div>
        <div class="relative">
            <img src={MaterialTwo} alt="Monitoring and Reporting" class="w-full h-[30vh] md:h-64 object-cover rounded-lg">
            <h1 class="absolute bottom-2 left-2 w-full text-center text-white bg-black bg-opacity-70 py-2 text-xl md:text-2xl font-semibold">Monitoring and Reporting</h1>
        </div>
        <div class="relative">
            <img src={MaterialTwo} alt="Material Selection" class="w-full h-[30vh] md:h-64 object-cover rounded-lg">
            <h1 class="absolute bottom-2 left-2 w-full text-center text-white bg-black bg-opacity-70 py-2 text-xl md:text-2xl font-semibold">Material Selection</h1>
        </div>
        <div class="relative">
            <img src={MaterialTwo} alt="Material Selection" class="w-full h-[30vh] md:h-64 object-cover rounded-lg">
            <h1 class="absolute bottom-2 left-2 w-full text-center text-white bg-black bg-opacity-70 py-2 text-xl md:text-2xl font-semibold">Material Selection</h1>
        </div>
    </div>
</section>

<section class="bg-[#003f72] py-12 px-4 md:px-8 text-white text-center">
    <h2 class="text-3xl md:text-5xl font-bold">Our Achievements and Strengths</h2>
    <button class="mt-6 px-6 py-3 bg-black hover:bg-transparent border transition-colors">Make An Appointment</button>
    <div class="grid grid-cols-2 md:grid-cols-4 gap-6 mt-8">
        <div>
            <img src={Icon} alt="icon" class="mx-auto mb-2">
            <h1 class="text-3xl md:text-6xl">3658+</h1>
            <p>Satisfied Customers</p>
        </div>
        <div>
            <img src={Icon} alt="icon" class="mx-auto mb-2">
            <h1 class="text-3xl md:text-6xl">200+</h1>
            <p>Experts Members</p>
        </div>
        <div>
            <img src={Icon} alt="icon" class="mx-auto mb-2">
            <h1 class="text-3xl md:text-6xl">50+</h1>
            <p>Modern Equipment</p>
        </div>
        <div >
         <img src={Icon} alt="icon" class="mx-auto ">
            <h2 class="text-3xl md:text-6xl">200000+</h2>
            <p>Millions Of Tons</p>
        </div>
    </div>
</section>

<section class="relative h-[100vh] md:h-[80vh]">
    <img src={Construction} alt="Construction" class="absolute inset-0 w-full h-full object-cover">
    <div class="absolute inset-0 bg-gradient-to-t from-white/75 via-white/50 to-transparent p-8 lg:p-16 max-w-lg lg:max-w-2xl">
        <h3 class="text-2xl text-[#003f72] font-serif">Our History</h3>
        <h1 class="text-3xl md:text-5xl font-serif font-semibold text-[#003f72]">Where Innovation Meets Excellence</h1>
        <p class="mt-4 font-semibold">We thrive on pioneering inventive solutions that redefine industry standards...</p>
    </div>
</section>

<section class="px-4 md:px-8 py-8 text-center">
    <h1 class="text-3xl md:text-5xl text-[#003f72]">List Of Projects</h1>
    <div class="flex justify-center space-x-4 mt-8">
        <button class="h-16 w-16 bg-[#003f72] rounded-full flex items-center justify-center text-white">
            <i class="ph ph-arrow-left"></i>
        </button>
        <button class="h-16 w-16 bg-[#003f72] rounded-full flex items-center justify-center text-white">
            <i class="ph ph-arrow-right"></i>
        </button>
    </div>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-6 mt-8">
        <img src={FirstSlide} alt="First Slide" class="w-full h-48 object-cover rounded-lg">
        <img src={SecondSlide} alt="Second Slide" class="w-full h-48 object-cover rounded-lg">
        <img src={ThirdSlide} alt="Third Slide" class="w-full h-48 object-cover rounded-lg">
    </div>
</section>

<section class="h-auto py-8 bg-gray-200 text-center">
    <h2 class="text-3xl md:text-5xl font-semibold text-[#003f72]">Our Progress Flow</h2>
    <div class="grid grid-cols-2 md:grid-cols-4 gap-8 mt-8">
        <div>
            <img src={Headphone} alt="Consultation" class="w-16 h-16 mx-auto mb-4">
            <h2 class="text-2xl font-serif text-[#003f72]">Consultation</h2>
            <p class="mt-2 font-sans font-semibold">"Your trusted consultation partner is just one call away!"</p>
        </div>
        <!-- Add additional steps here with similar layout -->
    </div>
</section>
