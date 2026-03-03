# agencia-activos-ia <!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dashboard de Operaciones | Agencia IA</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        body { background-color: #0f172a; color: #f8fafc; font-family: 'Inter', sans-serif; }
        .glass { background: rgba(30, 41, 59, 0.7); backdrop-filter: blur(10px); border: 1px solid rgba(255,255,255,0.1); }
        .glow { box-shadow: 0 0 15px rgba(34, 197, 94, 0.2); }
    </style>
</head>
<body class="p-6">
    <div class="max-w-6xl mx-auto">
        <header class="flex justify-between items-center mb-10 border-b border-slate-700 pb-6">
            <div>
                <h1 class="text-3xl font-bold text-green-400 tracking-tighter">SISTEMA GÉNESIS <span class="text-slate-500 text-sm font-mono">v1.1</span></h1>
                <p class="text-slate-400">Comandante: Sesión Activa</p>
            </div>
            <div class="flex gap-4">
                <div class="glass px-4 py-2 rounded-lg glow border-green-500/30">
                    <span class="text-xs text-slate-400 block uppercase">Estado Global</span>
                    <span class="text-green-400 font-bold flex items-center gap-2">
                        <span class="relative flex h-3 w-3">
                            <span class="animate-ping absolute inline-flex h-full w-full rounded-full bg-green-400 opacity-75"></span>
                            <span class="relative inline-flex rounded-full h-3 w-3 bg-green-500"></span>
                        </span>
                        OPERATIVO
                    </span>
                </div>
            </div>
        </header>

        <div class="grid grid-cols-1 md:grid-cols-4 gap-4 mb-10">
            <div class="glass p-4 rounded-xl">
                <h3 class="text-slate-400 text-xs font-bold uppercase mb-2">Unidad RADAR</h3>
                <p class="text-xl font-mono text-green-400">BUSCANDO NICHOS</p>
            </div>
            <div class="glass p-4 rounded-xl">
                <h3 class="text-slate-400 text-xs font-bold uppercase mb-2">Unidad ESTRUCTURA</h3>
                <p class="text-xl font-mono text-blue-400">ESPERANDO ORDEN</p>
            </div>
            <div class="glass p-4 rounded-xl border-l-4 border-yellow-500">
                <h3 class="text-slate-400 text-xs font-bold uppercase mb-2">Unidad PLUMA</h3>
                <p class="text-xl font-mono text-yellow-500">STAND-BY</p>
            </div>
            <div class="glass p-4 rounded-xl">
                <h3 class="text-slate-400 text-xs font-bold uppercase mb-2">MONETIZACIÓN</h3>
                <p class="text-xl font-mono text-slate-500">INACTIVO</p>
            </div>
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-3 gap-6">
            <div class="lg:col-span-2 glass p-6 rounded-2xl">
                <h2 class="text-xl font-bold mb-4 flex items-center gap-2">
                    <i class="fas fa-list-ul text-green-400"></i> Registro Cronológico
                </h2>
                <div class="space-y-4 font-mono text-sm">
                    <div class="border-l-2 border-slate-700 pl-4 py-1">
                        <span class="text-slate-500">[2026-03-02 21:00]</span> 
                        <span class="text-green-400">SISTEMA:</span> Conexión exitosa con Vercel.
                    </div>
                    <div class="border-l-2 border-slate-700 pl-4 py-1">
                        <span class="text-slate-500">[2026-03-02 21:05]</span> 
                        <span class="text-blue-400">ESTRUCTURA:</span> Dashboard Genesis v1.1 desplegado.
                    </div>
                    <div class="border-l-2 border-slate-700 pl-4 py-1 opacity-50">
                        <span class="text-slate-500">[Siguiente Paso]</span> 
                        <span class="text-slate-300">Esperando despliegue de Calculadora Energética...</span>
                    </div>
                </div>
            </div>

            <div class="glass p-6 rounded-2xl border-t-4 border-green-500">
                <h2 class="text-xl font-bold mb-4">Acciones Rápidas</h2>
                <div class="space-y-3">
                    <button class="w-full bg-green-600 hover:bg-green-500 text-white font-bold py-3 rounded-lg transition-all">
                        LANZAR NUEVO PROYECTO
                    </button>
                    <button class="w-full bg-slate-700 hover:bg-slate-600 text-white py-3 rounded-lg transition-all text-sm">
                        CONFIGURAR APIS
                    </button>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
