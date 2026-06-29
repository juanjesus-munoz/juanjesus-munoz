<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>TFG Aeroacústica | Juan Jesús Muñoz</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    html, body { background-color: #0f172a !important; }
    body { color: #f8fafc; font-family: 'Inter', sans-serif; }
    .accent-text { color: #38bdf8; }
    .mono { font-family: 'JetBrains Mono', monospace; }
  </style>
</head>
<body class="min-h-screen pt-24 px-6 pb-20">
  <nav class="fixed top-0 left-0 w-full bg-[#0f172a]/90 backdrop-blur-md border-b border-slate-800 px-6 py-4 flex justify-between items-center z-50">
    <a href="index.html" class="mono text-sm accent-text">&larr; Volver al inicio</a>
    <span class="mono text-xs uppercase text-slate-500 tracking-widest">Proyecto TFG</span>
  </nav>

  <article class="max-w-3xl mx-auto">
    <header class="mb-12">
      <h1 class="text-4xl md:text-5xl font-bold mb-6 leading-tight">Simulación aeroacústica mediante métodos de alto orden</h1>
      <div class="flex flex-wrap gap-6 text-sm mono text-slate-400 py-6 border-y border-slate-800">
        <div><span class="block accent-text mb-1 uppercase text-xs">Solver</span> PyFR</div>
        <div><span class="block accent-text mb-1 uppercase text-xs">Malla</span> Pointwise</div>
        <div><span class="block accent-text mb-1 uppercase text-xs">Entorno</span> Linux HPC</div>
      </div>
    </header>

    <div class="space-y-8 text-slate-300 leading-relaxed text-lg">
      <p>El proyecto aborda el desafío de predecir el ruido generado por el aire al fluir sobre superficies complejas. Utilizando <strong class="text-white">PyFR</strong>, ejecutamos simulaciones que aprovechan la potencia de las GPUs para obtener resultados mucho más precisos que los métodos tradicionales.</p>
      
      <div class="bg-slate-800/50 p-8 rounded-2xl border border-slate-700">
        <h2 class="text-white font-bold mb-4 text-xl">Metodología Aplicada</h2>
        <ul class="space-y-3 text-base">
          <li class="flex gap-3"><span class="accent-text font-bold">1.</span> Generación de mallas no estructuradas optimizadas.</li>
          <li class="flex gap-3"><span class="accent-text font-bold">2.</span> Configuración de solvers de flujo compresible de alto orden.</li>
          <li class="flex gap-3"><span class="accent-text font-bold">3.</span> Post-proceso en ParaView para visualizar vórtices y ondas de presión.</li>
        </ul>
      </div>
      
      <p>Los resultados fueron validados con datos experimentales de la literatura especializada, demostrando la alta capacidad de los métodos de flujo de reconstrucción (FR) para capturar la física acústica de pequeña escala.</p>
    </div>

    <div class="mt-16 flex gap-4">
      <a href="https://github.com/juanjesus-munoz" class="bg-[#38bdf8] text-[#0f172a] px-6 py-3 rounded-xl font-bold hover:bg-[#0284c7] transition-all">Ver Repositorio</a>
    </div>
  </article>

  <footer class="max-w-3xl mx-auto mt-20 pt-8 border-t border-slate-800 text-center text-sm text-slate-500">
    Desarrollado por Juan Jesús Muñoz Aguilera
  </footer>
</body>
</html>
