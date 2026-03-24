<script setup>

</script>

<template>
  <main class="min-h-screen bg-slate-50 flex items-center justify-center p-6">
    
    <div class="max-w-sm bg-white rounded-3xl shadow-xl overflow-hidden border border-slate-100 transition-transform hover:scale-105 duration-300">
      
      <div class="relative">
        <img class="w-full h-48 object-cover" src="https://images.unsplash.com/photo-1523275335684-37898b6baf30?auto=format&fit=crop&q=80&w=600" alt="Producto">
        <span class="absolute top-4 left-4 bg-blue-600 text-white text-xs font-bold px-3 py-1 rounded-full uppercase tracking-wider">
          Nuevo
        </span>
      </div>

      <div class="p-6">
        <h2 class="text-2xl font-bold text-slate-800">Reloj Minimalista v4</h2>
        <p class="mt-2 text-slate-600 leading-relaxed">
          Diseño ultra delgado con integración nativa para desarrolladores Vue. 
          Estilizado completamente con utilidades de Tailwind CSS.
        </p>

        <div class="mt-6 flex items-center justify-between">
          <span class="text-3xl font-extrabold text-slate-900">$99.00</span>
          <button class="bg-slate-900 hover:bg-blue-600 text-white px-6 py-2 rounded-xl font-medium transition-colors duration-200 cursor-pointer">
            Añadir
          </button>
        </div>
      </div>

    </div>
  </main>
</template>
