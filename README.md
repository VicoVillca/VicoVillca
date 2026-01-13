<!-- Primero, necesitas agregar estos scripts en tu README.md -->
<!-- Nota: GitHub Markdown soporta HTML limitado, esto funcionará en tu portafolio web -->

<div align="center">

<!-- 🌟 HEADER CON ANIMACIÓN TIPO MATRIX -->
<div class="matrix-container" style="position: relative; height: 100px; margin: 20px 0;">
  <canvas id="matrixCanvas" width="800" height="100" style="border-radius: 10px; background: #0a1929;"></canvas>
  <div style="position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%);">
    <h1 style="color: #00ff41; font-family: 'Courier New', monospace; text-shadow: 0 0 10px #00ff41;">
      🚀 ABRAHAM VILLCA ALARCÓN
    </h1>
  </div>
</div>

<!-- ✨ BADGES ANIMADOS -->
<div class="badges-container" style="display: flex; flex-wrap: wrap; justify-content: center; gap: 10px; margin: 20px 0;">
  <div class="badge-animated" style="
    padding: 8px 16px;
    background: linear-gradient(45deg, #0563bb, #0a5ca8);
    border-radius: 20px;
    color: white;
    font-weight: bold;
    animation: float 3s ease-in-out infinite;
    box-shadow: 0 0 15px rgba(5, 99, 187, 0.5);
  ">
    <i class="fas fa-map-marker-alt"></i> La Paz, Bolivia
  </div>
  
  <div class="badge-animated" style="
    padding: 8px 16px;
    background: linear-gradient(45deg, #D14836, #C23321);
    border-radius: 20px;
    color: white;
    font-weight: bold;
    animation: float 3s ease-in-out infinite 0.5s;
    box-shadow: 0 0 15px rgba(209, 72, 54, 0.5);
  ">
    <i class="fas fa-envelope"></i> vicovillca@gmail.com
  </div>
</div>

<!-- 🎯 TECNOLOGÍAS CON EFECTO HOVER 3D -->
<h2 style="color: #0563bb; margin-top: 40px;">🛠️ Stack Tecnológico Interactivo</h2>

<div class="tech-grid" style="
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
  gap: 15px;
  margin: 30px 0;
  perspective: 1000px;
">

<div class="tech-card" style="
  background: linear-gradient(135deg, #0a1929, #112240);
  padding: 20px;
  border-radius: 15px;
  text-align: center;
  transition: all 0.3s ease;
  border: 2px solid transparent;
  position: relative;
  overflow: hidden;
  cursor: pointer;
" 
onmouseover="this.style.transform='rotateY(10deg) scale(1.05)'; this.style.boxShadow='0 20px 40px rgba(5, 99, 187, 0.3)'; this.style.borderColor='#0563bb'"
onmouseout="this.style.transform='rotateY(0deg) scale(1)'; this.style.boxShadow='0 5px 15px rgba(0,0,0,0.1)'; this.style.borderColor='transparent'">
  <div style="font-size: 40px; color: #ED8B00; margin-bottom: 10px;">☕</div>
  <span style="color: white; font-weight: bold;">Java</span>
  <div style="
    position: absolute;
    bottom: 0;
    left: 0;
    right: 0;
    height: 3px;
    background: linear-gradient(90deg, #ED8B00, #FF9800);
    transform: scaleX(0);
    transition: transform 0.3s ease;
  " class="progress-bar"></div>
</div>

<div class="tech-card" style="
  background: linear-gradient(135deg, #0a1929, #112240);
  padding: 20px;
  border-radius: 15px;
  text-align: center;
  transition: all 0.3s ease;
  border: 2px solid transparent;
  position: relative;
  overflow: hidden;
  cursor: pointer;
" 
onmouseover="this.style.transform='rotateY(10deg) scale(1.05)'; this.style.boxShadow='0 20px 40px rgba(93, 179, 51, 0.3)'; this.style.borderColor='#6DB33F'"
onmouseout="this.style.transform='rotateY(0deg) scale(1)'; this.style.boxShadow='0 5px 15px rgba(0,0,0,0.1)'; this.style.borderColor='transparent'">
  <div style="font-size: 40px; color: #6DB33F; margin-bottom: 10px;">🌱</div>
  <span style="color: white; font-weight: bold;">Spring Boot</span>
</div>

<div class="tech-card" style="
  background: linear-gradient(135deg, #0a1929, #112240);
  padding: 20px;
  border-radius: 15px;
  text-align: center;
  transition: all 0.3s ease;
  border: 2px solid transparent;
  position: relative;
  overflow: hidden;
  cursor: pointer;
" 
onmouseover="this.style.transform='rotateY(10deg) scale(1.05)'; this.style.boxShadow='0 20px 40px rgba(221, 0, 49, 0.3)'; this.style.borderColor='#DD0031'"
onmouseout="this.style.transform='rotateY(0deg) scale(1)'; this.style.boxShadow='0 5px 15px rgba(0,0,0,0.1)'; this.style.borderColor='transparent'">
  <div style="font-size: 40px; color: #DD0031; margin-bottom: 10px;">🅰️</div>
  <span style="color: white; font-weight: bold;">Angular</span>
</div>

<!-- Añade más tarjetas para cada tecnología -->
</div>

<!-- 🌟 CITA ANIMADA -->
<div class="quote-container" style="
  background: linear-gradient(135deg, rgba(5, 99, 187, 0.1), rgba(10, 25, 41, 0.1));
  padding: 30px;
  border-radius: 20px;
  margin: 40px 0;
  border-left: 5px solid #0563bb;
  animation: pulse 2s infinite;
">
  <blockquote style="
    font-size: 1.2em;
    color: #333;
    font-style: italic;
    text-align: center;
    margin: 0;
  ">
    "La excelencia técnica no se trata solo de escribir código funcional, 
    <br>sino de crear <span style="color: #0563bb; font-weight: bold;">arquitecturas que escalen</span>, 
    <span style="color: #00ff41; font-weight: bold;">soluciones que perduren</span> 
    y <span style="color: #ff6b6b; font-weight: bold;">sistemas que inspiren</span>."
  </blockquote>
</div>

<!-- 📊 EXPERIENCIA TIMELINE ANIMADA -->
<h2 style="color: #0563bb; margin-top: 40px;">⏳ Línea de Tiempo Profesional</h2>

<div class="timeline" style="position: relative; max-width: 800px; margin: 40px auto;">

<div class="timeline-item" style="
  position: relative;
  margin: 20px 0;
  padding: 20px;
  background: white;
  border-radius: 10px;
  box-shadow: 0 5px 15px rgba(0,0,0,0.1);
  border-left: 5px solid #0563bb;
  animation: slideInLeft 0.5s ease-out;
">
  <div style="display: flex; justify-content: space-between; align-items: center;">
    <h3 style="margin: 0; color: #0563bb;">ENDE Corporación</h3>
    <span style="background: #0563bb; color: white; padding: 5px 10px; border-radius: 15px; font-size: 0.9em;">
      Mar 2024 - Presente
    </span>
  </div>
  <p style="color: #666; margin: 10px 0 0 0;">
    <strong>Arquitectura Base:</strong> Microservicios & Microfrontends para SICOMEL
  </p>
</div>

<div class="timeline-item" style="
  position: relative;
  margin: 20px 0;
  padding: 20px;
  background: white;
  border-radius: 10px;
  box-shadow: 0 5px 15px rgba(0,0,0,0.1);
  border-left: 5px solid #00ff41;
  animation: slideInLeft 0.5s ease-out 0.2s;
  animation-fill-mode: both;
">
  <div style="display: flex; justify-content: space-between; align-items: center;">
    <h3 style="margin: 0; color: #00ff41;">GAMLP</h3>
    <span style="background: #00ff41; color: #0a1929; padding: 5px 10px; border-radius: 15px; font-size: 0.9em;">
      Ago 2023 - Dic 2023
    </span>
  </div>
  <p style="color: #666; margin: 10px 0 0 0;">
    <strong>Plataforma Municipal:</strong> iGob 24/7 Plus & Travel La Paz
  </p>
</div>

</div>

<!-- 🎮 BOTONES INTERACTIVOS -->
<h2 style="color: #0563BB; margin-top: 40px;">📬 ¡Conectemos!</h2>

<div class="buttons-container" style="display: flex; justify-content: center; gap: 20px; margin: 30px 0; flex-wrap: wrap;">

<a href="mailto:vicovillca@gmail.com" 
   style="text-decoration: none;"
   onmouseover="this.querySelector('.btn-icon').style.transform='translateY(-5px) scale(1.2)'"
   onmouseout="this.querySelector('.btn-icon').style.transform='translateY(0) scale(1)'">
  <div class="contact-btn" style="
    background: linear-gradient(45deg, #D14836, #C23321);
    color: white;
    padding: 15px 30px;
    border-radius: 50px;
    display: flex;
    align-items: center;
    gap: 10px;
    font-weight: bold;
    transition: all 0.3s ease;
    box-shadow: 0 5px 15px rgba(209, 72, 54, 0.3);
    cursor: pointer;
  ">
    <span class="btn-icon" style="transition: transform 0.3s ease;">📧</span>
    <span>Enviar Email</span>
  </div>
</a>

<a href="https://bo.linkedin.com/in/abraham-villca-0169301a1" 
   target="_blank"
   style="text-decoration: none;"
   onmouseover="this.querySelector('.btn-icon').style.transform='translateY(-5px) scale(1.2)'"
   onmouseout="this.querySelector('.btn-icon').style.transform='translateY(0) scale(1)'">
  <div class="contact-btn" style="
    background: linear-gradient(45deg, #0077B5, #005582);
    color: white;
    padding: 15px 30px;
    border-radius: 50px;
    display: flex;
    align-items: center;
    gap: 10px;
    font-weight: bold;
    transition: all 0.3s ease;
    box-shadow: 0 5px 15px rgba(0, 119, 181, 0.3);
    cursor: pointer;
  ">
    <span class="btn-icon" style="transition: transform 0.3s ease;">💼</span>
    <span>LinkedIn</span>
  </div>
</a>

</div>

<!-- 🎨 EFECTO DE PARTÍCULAS (SIMULADO) -->
<div style="
  position: relative;
  height: 100px;
  margin: 40px 0;
  overflow: hidden;
  border-radius: 10px;
  background: linear-gradient(135deg, #0a1929, #112240);
">
  <div style="
    position: absolute;
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    color: #00ff41;
    font-family: 'Courier New', monospace;
    font-size: 1.2em;
    text-shadow: 0 0 10px #00ff41;
  ">
    <<< CÓDIGO_PASIÓN_INNOVACIÓN >>>
  </div>
</div>

</div>

<!-- 🎬 ANIMACIONES CSS INLINE -->
<style>
@keyframes float {
  0%, 100% { transform: translateY(0); }
  50% { transform: translateY(-10px); }
}

@keyframes pulse {
  0%, 100% { box-shadow: 0 0 0 0 rgba(5, 99, 187, 0.4); }
  50% { box-shadow: 0 0 0 10px rgba(5, 99, 187, 0); }
}

@keyframes slideInLeft {
  from {
    opacity: 0;
    transform: translateX(-30px);
  }
  to {
    opacity: 1;
    transform: translateX(0);
  }
}

@keyframes glow {
  0%, 100% { text-shadow: 0 0 5px #0563bb; }
  50% { text-shadow: 0 0 20px #0563bb, 0 0 30px #0563bb; }
}

.tech-card:hover .progress-bar {
  transform: scaleX(1);
}
</style>

<!-- ⚡ SCRIPT PARA EFECTO MATRIX (OPCIONAL) -->
<script>
// Efecto Matrix simple para el canvas
window.addEventListener('DOMContentLoaded', (event) => {
  const canvas = document.getElementById('matrixCanvas');
  if (canvas) {
    const ctx = canvas.getContext('2d');
    const letters = 'ABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789$+-*/=%"#&_()';
    const fontSize = 14;
    const columns = canvas.width / fontSize;
    const drops = [];
    
    for(let i = 0; i < columns; i++) drops[i] = 1;
    
    function drawMatrix() {
      ctx.fillStyle = 'rgba(10, 25, 41, 0.1)';
      ctx.fillRect(0, 0, canvas.width, canvas.height);
      
      ctx.fillStyle = '#00ff41';
      ctx.font = `${fontSize}px monospace`;
      
      for(let i = 0; i < drops.length; i++) {
        const text = letters[Math.floor(Math.random() * letters.length)];
        ctx.fillText(text, i * fontSize, drops[i] * fontSize);
        
        if(drops[i] * fontSize > canvas.height && Math.random() > 0.975) {
          drops[i] = 0;
        }
        drops[i]++;
      }
    }
    
    setInterval(drawMatrix, 50);
  }
});
</script>

<!-- 📱 RESPONSIVE -->
<style>
@media (max-width: 768px) {
  .tech-grid {
    grid-template-columns: repeat(2, 1fr);
  }
  
  .buttons-container {
    flex-direction: column;
    align-items: center;
  }
  
  .contact-btn {
    width: 100%;
    max-width: 300px;
    justify-content: center;
  }
}
</style>
