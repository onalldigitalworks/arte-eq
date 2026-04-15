<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Asesoramiento Experto en Insumos | Tu Socio Creativo</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700;800&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Inter', sans-serif; scroll-behavior: smooth; }
        .bg-mesh {
            background-color: #ffffff;
            background-image: radial-gradient(at 0% 0%, rgba(249, 115, 22, 0.05) 0px, transparent 50%),
                              radial-gradient(at 100% 0%, rgba(249, 115, 22, 0.05) 0px, transparent 50%);
        }
        .cta-shadow:hover {
            box-shadow: 0 20px 25px -5px rgba(249, 115, 22, 0.4), 0 10px 10px -5px rgba(249, 115, 22, 0.1);
        }
        .form-input {
            transition: all 0.2s ease;
        }
        .form-input:focus {
            border-color: #f97316;
            box-shadow: 0 0 0 4px rgba(249, 115, 22, 0.1);
        }
        .time-slot:hover {
            border-color: #f97316;
            background-color: #fff7ed;
        }
        .time-slot.selected {
            background-color: #f97316;
            color: white;
            border-color: #f97316;
        }
    </style>
</head>
<body class="bg-mesh text-gray-900">

    <section class="relative pt-16 pb-20 lg:pt-24 lg:pb-32 overflow-hidden">
        <div class="container mx-auto px-6 relative z-10">
            <div class="flex flex-col lg:flex-row items-center">
                <div class="lg:w-7/12 text-center lg:text-left">
                    <div class="inline-flex items-center space-x-2 bg-orange-50 border border-orange-100 px-3 py-1 rounded-full mb-6">
                        <span class="flex h-2 w-2 rounded-full bg-orange-500 animate-pulse"></span>
                        <span class="text-orange-700 text-xs font-bold uppercase tracking-wider">Acceso Mayorista Intermedio</span>
                    </div>
                    <h1 class="text-4xl md:text-6xl font-extrabold tracking-tight text-gray-900 leading-[1.1] mb-6">
                        Impulsá tu taller con <span class="text-orange-500">precios directos</span> y asesoría a medida
                    </h1>
                    <p class="text-lg md:text-xl text-gray-600 mb-8 max-w-2xl mx-auto lg:mx-0">
                        Dejá de pagar de más por tus insumos. Recibí una selección personalizada según tu producción y accedé a beneficios exclusivos que solo damos a emprendedores.
                    </p>
                    <div class="flex flex-col sm:flex-row items-center justify-center lg:justify-start gap-4">
                        <a href="#formulario" class="w-full sm:w-auto px-8 py-5 bg-orange-500 text-white font-bold rounded-2xl cta-shadow transition-all text-lg text-center transform hover:-translate-y-1 uppercase tracking-tight">
                            Quiero mi selección personalizada
                        </a>
                    </div>
                </div>
                <div class="lg:w-5/12 mt-12 lg:mt-0 relative">
                    <div class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-72 h-72 bg-orange-200 rounded-full blur-3xl opacity-30"></div>
                    <img src="https://images.unsplash.com/photo-1513364776144-60967b0f800f?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80" alt="Materiales artísticos" class="relative rounded-[2.5rem] shadow-2xl border-8 border-white transform rotate-2">
                </div>
            </div>
        </div>
    </section>

    <section class="py-10 bg-gray-50/50 border-y border-gray-100">
        <div class="container mx-auto px-6 text-center">
            <h2 class="text-xl font-bold text-gray-800">Más de 500 emprendedores ya optimizaron sus costos</h2>
        </div>
    </section>

    <section id="formulario" class="py-24 bg-gray-50">
        <div class="container mx-auto px-6">
            <div class="max-w-4xl mx-auto bg-white rounded-[2.5rem] shadow-2xl overflow-hidden flex flex-col md:flex-row border border-gray-100 min-h-[600px]">
                
                <div class="md:w-1/3 bg-gray-900 p-10 text-white flex flex-col justify-center">
                    <h3 class="text-2xl font-bold mb-6 italic" id="sidebar-title">Solo 30 segundos...</h3>
                    <div class="space-y-6" id="sidebar-features">
                        <div class="flex items-center space-x-3">
                            <div class="w-8 h-8 bg-green-500 rounded-full flex items-center justify-center"><svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg></div>
                            <span class="text-sm font-medium">Sin compromiso</span>
                        </div>
                        <div class="flex items-center space-x-3">
                            <div class="w-8 h-8 bg-blue-500 rounded-full flex items-center justify-center"><svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path></svg></div>
                            <span class="text-sm font-medium">Respuesta rápida</span>
                        </div>
                    </div>
                    <div id="sidebar-agenda" class="hidden space-y-4">
                        <p class="text-sm text-gray-400">Seleccioná un horario disponible para analizar tu lista de insumos.</p>
                    </div>
                </div>

                <div class="md:w-2/3 p-10 lg:p-14 flex flex-col justify-center">
                    
                    <form id="leadForm" action="https://formsubmit.co/ajax/TU_CORREO@EMAIL.COM" method="POST" class="space-y-5">
                        
                        <input type="hidden" name="_captcha" value="false">
                        <input type="hidden" name="_subject" value="Nuevo Lead: Asesoría de Insumos">

                        <div class="grid grid-cols-1 md:grid-cols-2 gap-5">
                            <div>
                                <label class="block text-xs font-bold uppercase tracking-widest text-gray-400 mb-2">Nombre Completo</label>
                                <input type="text" name="Nombre" required class="form-input w-full px-5 py-4 rounded-xl bg-gray-50 border border-gray-100 outline-none" placeholder="Tu nombre">
                            </div>
                            <div>
                                <label class="block text-xs font-bold uppercase tracking-widest text-gray-400 mb-2">WhatsApp</label>
                                <input type="tel" name="WhatsApp" required class="form-input w-full px-5 py-4 rounded-xl bg-gray-50 border border-gray-100 outline-none" placeholder="+54 9 ...">
                            </div>
                        </div>
                        <div>
                            <label class="block text-xs font-bold uppercase tracking-widest text-gray-400 mb-2">¿A qué técnica te dedicás?</label>
                            <input type="text" name="Tecnica" required class="form-input w-full px-5 py-4 rounded-xl bg-gray-50 border border-gray-100 outline-none" placeholder="Pintura, Resina, etc.">
                        </div>
                        <div class="grid grid-cols-1 md:grid-cols-2 gap-5">
                            <div>
                                <label class="block text-xs font-bold uppercase tracking-widest text-gray-400 mb-2">Insumo que más usás</label>
                                <input type="text" name="Insumo_Principal" required class="form-input w-full px-5 py-4 rounded-xl bg-gray-50 border border-gray-100 outline-none" placeholder="Acrílicos, etc.">
                            </div>
                            <div>
                                <label class="block text-xs font-bold uppercase tracking-widest text-gray-400 mb-2">Volumen de compra</label>
                                <select name="Volumen" required class="form-input w-full px-5 py-4 rounded-xl bg-gray-50 border border-gray-100 outline-none appearance-none">
                                    <option value="" disabled selected>Seleccioná</option>
                                    <option value="bajo">Bajo (Uso personal)</option>
                                    <option value="medio">Medio (Tallerista)</option>
                                    <option value="alto">Alto (Masivo)</option>
                                </select>
                            </div>
                        </div>
                        <div class="pt-4">
                            <button type="submit" id="submitBtn" class="w-full py-5 bg-orange-500 hover:bg-orange-600 text-white font-extrabold rounded-2xl transition-all shadow-xl text-lg uppercase tracking-tight">
                                Quiero mi selección personalizada
                            </button>
                        </div>
                    </form>

                    <div id="thank-you-view" class="hidden text-center">
                        <div class="w-16 h-16 bg-green-100 text-green-600 rounded-full flex items-center justify-center mx-auto mb-6">
                            <svg class="w-8 h-8" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>
                        </div>
                        <h3 class="text-3xl font-black mb-2">¡Casi listo!</h3>
                        <p class="text-gray-600 mb-8">Tus datos fueron enviados. Si querés acelerar el proceso:</p>
                        <div class="bg-orange-50 p-8 rounded-3xl border-2 border-dashed border-orange-200">
                            <button onclick="showAgenda()" class="w-full py-4 bg-gray-900 text-white font-bold rounded-xl shadow-lg">
                                Agendar llamada ahora
                            </button>
                        </div>
                    </div>

                    <div id="agenda-view" class="hidden">
                        <h3 class="text-2xl font-black mb-4">Elegí tu horario</h3>
                        <div class="grid grid-cols-3 gap-3 mb-8">
                            <button onclick="selectSlot(this)" class="time-slot py-3 border border-gray-100 rounded-xl text-sm font-bold bg-gray-50">09:00 AM</button>
                            <button onclick="selectSlot(this)" class="time-slot py-3 border border-gray-100 rounded-xl text-sm font-bold bg-gray-50">10:30 AM</button>
                            <button onclick="selectSlot(this)" class="time-slot py-3 border border-gray-100 rounded-xl text-sm font-bold bg-gray-50">04:30 PM</button>
                        </div>
                        <button id="confirmAgenda" disabled class="w-full py-5 bg-orange-500 text-white font-extrabold rounded-2xl opacity-50 cursor-not-allowed">
                            Confirmar Turno
                        </button>
                    </div>

                    <div id="final-success" class="hidden text-center">
                        <h3 class="text-3xl font-black mb-2 text-orange-600">¡Turno Reservado!</h3>
                        <p class="text-gray-600">Te contactaremos a las <span class="font-bold" id="selected-time"></span>.</p>
                    </div>

                </div>
            </div>
        </div>
    </section>

    <footer class="py-12 text-center text-gray-400 text-sm">
        <p>&copy; 2024 Nuestra Artística.</p>
    </footer>

    <script>
        const leadForm = document.getElementById('leadForm');
        const thankYouView = document.getElementById('thank-you-view');
        const agendaView = document.getElementById('agenda-view');
        const finalSuccess = document.getElementById('final-success');
        const sidebarTitle = document.getElementById('sidebar-title');
        const sidebarFeatures = document.getElementById('sidebar-features');
        const sidebarAgenda = document.getElementById('sidebar-agenda');
        const confirmBtn = document.getElementById('confirmAgenda');
        const submitBtn = document.getElementById('submitBtn');

        let selectedTimeValue = "";

        // ENVÍO DEL FORMULARIO
        leadForm.addEventListener('submit', function(e) {
            e.preventDefault();
            submitBtn.innerText = "Enviando...";
            submitBtn.disabled = true;

            const formData = new FormData(this);
            const object = {};
            formData.forEach((value, key) => object[key] = value);
            const json = JSON.stringify(object);

            fetch("https://formsubmit.co/ajax/" + this.action.split('/').pop(), {
                method: "POST",
                headers: { 
                    "Content-Type": "application/json",
                    "Accept": "application/json"
                },
                body: json
            })
            .then(res => res.json())
            .then(data => {
                leadForm.classList.add('hidden');
                thankYouView.classList.remove('hidden');
                document.getElementById('formulario').scrollIntoView({ behavior: 'smooth' });
            })
            .catch(err => {
                alert("Error al enviar. Por favor revisa el email configurado.");
                submitBtn.innerText = "Quiero mi selección personalizada";
                submitBtn.disabled = false;
            });
        });

        function showAgenda() {
            thankYouView.classList.add('hidden');
            agendaView.classList.remove('hidden');
            sidebarTitle.innerText = "Agendá tu Llamada";
            sidebarFeatures.classList.add('hidden');
            sidebarAgenda.classList.remove('hidden');
        }

        function selectSlot(element) {
            document.querySelectorAll('.time-slot').forEach(slot => slot.classList.remove('selected'));
            element.classList.add('selected');
            selectedTimeValue = element.innerText;
            confirmBtn.disabled = false;
            confirmBtn.classList.remove('opacity-50', 'cursor-not-allowed');
        }

        confirmBtn.addEventListener('click', function() {
            agendaView.classList.add('hidden');
            finalSuccess.classList.remove('hidden');
            document.getElementById('selected-time').innerText = selectedTimeValue;
        });
    </script>
</body>
</html>
