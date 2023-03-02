<template>
    <div class="font lg:ml-32 lg:mr-32 ml-10 mt-7 mr-10">
        <!-- Titulo de seccion -->
        <div>
            <h2 class="text-back text-5xl md:text-6xl font-medium mb-3">Funcionaria</h2>
            <hr class="color-gray-600">
        </div>
        <!-- Contenido -->
        <div class="flex-col md:flex md:flex-row mt-5">
            <!-- imagen -->
            <div class="h-70 w-80 md:min-h-64 md:min-w-72 md:w-96 md:h-96 shrink-0">
                <img class="rounded-lg md:w-80 md:h-72" src="../public/img/Captura.PNG" alt="">
            </div>

            <div class="flex-col">
                <!-- Nombre funcionario -->
                <h2 class="text-back font-medium text-4xl md:text-5xl mb-5 mt-3">Dra. Cintia Smith</h2>
                <!-- Descripción funcionario -->
                <p class="leading-6">La Secretaria de Innovación y Gobierno Abierto del Municipio de Monterrey es doctora en Ciencia Política por la Universidad Autónoma de Nuevo León. Se desempeñó como profesora e investigadora en el Tecnológico de Monterrey, Campus Monterrey, por más de 20 años. Impartió clases de políticas públicas, ciudadanía y tecnología, comunicación política y filosofía política. En el 2020, participó en el Comité de Selección del Sistema Estatal Anticorrupción.</p>
                <!-- Collapse menu -->
                <div id="carrousel" class="mt-8 relative mb:w-[740px] overflow-hidden">
                    <input type="checkbox" class="peer absolute top-o inset-x-0 w-full h-12 opacity-0 z-10 cursor-pointer">
                    <div class="border-gray-600 border-2 rounded-lg h-12 w-full md:pl-5 flex items-center peer-checked:rounded-b">
                        <h1 class="md:text-lg ml-1 font-semibold text-back">
                            Compromisos con Monterrey
                        </h1>
                    </div>
                    <!-- Flecha -->
                    <div class="absolute top-3 right-3 text-primary-gray transition-tran
                    duration-500 rotate-0 peer-checked:rotate-180">
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 8.25l-7.5 7.5-7.5-7.5" />
                        </svg>
                    </div>
                    <!-- Contenido -->
                    <div class="max-h-0 border-t-0 border-b-0 overflow-hidden transition-all duration-500 border-gray-600 border-2 rounded-lg peer-checked:rounded-t-none peer-checked:border-b-2 peer-checked:rounded-br-lg mb:peer-checked:max-h-80 peer-checked:max-h-96">
                        <div class="p-4">
                            <ul class=" list-disc ml-10 mr-10">
                                <li class="mb-3">
                                    Mejorar la experiencia de los ciudadanos y las empresas en la realización de trámites y servicios.
                                </li>
                                <li class="mb-3">
                                    Desarrollar mecanismos participativos para sumar las propuestas de la ciudadanía a la mejora del espacio público.
                                </li>
                                <li class="mb-3">
                                    Implementar una plataforma de transparencia proactiva con datos abiertos y descargables.
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>       
        </div>
    </div>
</template>
<style>
@import url('https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;700&display=swap');
.font {
    font-family: 'DM Sans', sans-serif!important;
}
</style>