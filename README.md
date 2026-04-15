<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta
      name="viewport"
      content="width=device-width, initial-scale=1.0, user-scalable=no"
    />
    <title>
      Muhammad Yasin Khan | AI/ML Architect | Advanced Neural Header
    </title>
    <!-- Google Fonts for premium typography -->
    <link
      href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;500;600;700;800;900&family=Inter:wght@300;400;500;600;700&display=swap"
      rel="stylesheet"
    />
    <!-- Font Awesome 6 (free icons) -->
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css"
    />
    <style>
      * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
      }

      body {
        background: radial-gradient(circle at 20% 30%, #0a0f1e, #03060c);
        min-height: 100vh;
        display: flex;
        justify-content: center;
        align-items: center;
        font-family: "Inter", "Orbitron", sans-serif;
        overflow-x: hidden;
        position: relative;
        padding: 2rem;
      }

      /* animated grain texture */
      body::before {
        content: "";
        position: fixed;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background-image: url("data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIzMDAiIGhlaWdodD0iMzAwIj48ZmlsdGVyIGlkPSJmIj48ZmVUdXJidWxlbmNlIHR5cGU9ImZyYWN0YWxOb2lzZSIgYmFzZUZyZXF1ZW5jeT0iLjYiIG51bU9jdGF2ZXM9IjMiLz48L2ZpbHRlcj48cmVjdCB3aWR0aD0iMTAwJSIgaGVpZ2h0PSIxMDAlIiBmaWx0ZXI9InVybCgjZikiIG9wYWNpdHk9IjAuMDYiLz48L3N2Zz4=");
        opacity: 0.15;
        pointer-events: none;
        z-index: 1;
      }

      /* main card container with glassmorphic deep glow */
      .neural-header {
        position: relative;
        max-width: 1100px;
        width: 100%;
        background: rgba(5, 12, 20, 0.55);
        backdrop-filter: blur(12px);
        border-radius: 3.5rem;
        padding: 2.8rem 2.2rem 3rem 2.2rem;
        box-shadow: 0 25px 45px rgba(0, 0, 0, 0.5),
          0 0 0 2px rgba(0, 255, 100, 0.15),
          inset 0 1px 1px rgba(255, 255, 255, 0.08);
        border: 1px solid rgba(0, 255, 136, 0.25);
        transition: all 0.4s ease;
        z-index: 10;
        overflow: hidden;
      }

      /* animated orbital rings background */
      .neural-header::before {
        content: "";
        position: absolute;
        top: -50%;
        left: -50%;
        width: 200%;
        height: 200%;
        background: radial-gradient(
          circle at 30% 40%,
          rgba(0, 255, 160, 0.08),
          transparent 70%
        );
        animation: rotateOrbital 32s linear infinite;
        pointer-events: none;
        z-index: 0;
      }

      @keyframes rotateOrbital {
        0% {
          transform: rotate(0deg);
        }
        100% {
          transform: rotate(360deg);
        }
      }

      /* AI animated neural network canvas (3d-like web) */
      #aiCanvas {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        border-radius: 3.5rem;
        pointer-events: none;
        z-index: 2;
        opacity: 0.55;
      }

      /* content layer above canvas */
      .content {
        position: relative;
        z-index: 15;
        text-align: center;
      }

      /* advanced typing glitch container */
      .glitch-typing {
        margin-bottom: 1rem;
      }

      .typing-svg {
        filter: drop-shadow(0 0 12px #00ff88);
      }

      /* main name with ai neon */
      .ai-name {
        font-family: "Orbitron", monospace;
        font-weight: 900;
        font-size: 3.5rem;
        background: linear-gradient(135deg, #e0ffe0, #00ffaa, #00ccff);
        background-size: 300% auto;
        -webkit-background-clip: text;
        background-clip: text;
        color: transparent;
        animation: shimmer 6s linear infinite,
          textPulse 2.5s ease-in-out infinite;
        letter-spacing: 2px;
        margin: 0.5rem 0;
        text-shadow: 0 0 8px rgba(0, 255, 140, 0.3);
      }

      @keyframes shimmer {
        0% {
          background-position: 0% 50%;
        }
        50% {
          background-position: 100% 50%;
        }
        100% {
          background-position: 0% 50%;
        }
      }

      @keyframes textPulse {
        0% {
          opacity: 0.95;
          text-shadow: 0 0 2px #0f0;
        }
        50% {
          opacity: 1;
          text-shadow: 0 0 18px #0f0, 0 0 5px #0f0;
        }
        100% {
          opacity: 0.95;
          text-shadow: 0 0 2px #0f0;
        }
      }

      /* role badge with AI chip */
      .role-badge {
        display: inline-flex;
        align-items: center;
        gap: 12px;
        background: rgba(0, 20, 15, 0.7);
        backdrop-filter: blur(12px);
        padding: 0.7rem 1.8rem;
        border-radius: 80px;
        margin: 1rem 0;
        border: 1px solid #00ff8844;
        box-shadow: 0 0 15px rgba(0, 255, 136, 0.2);
      }

      .role-badge i {
        font-size: 1.8rem;
        color: #00ffaa;
        filter: drop-shadow(0 0 5px #00ffaa);
      }

      .role-text {
        font-family: "Orbitron", monospace;
        font-weight: 600;
        font-size: 1.2rem;
        letter-spacing: 2px;
        color: #ccfff0;
      }

      /* premium badge row with animated borders */
      .badge-row {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        gap: 1.2rem;
        margin: 1.5rem 0;
      }

      .premium-badge {
        display: inline-flex;
        align-items: center;
        gap: 12px;
        background: rgba(12, 22, 35, 0.7);
        padding: 0.65rem 1.4rem;
        border-radius: 60px;
        backdrop-filter: blur(8px);
        transition: all 0.3s cubic-bezier(0.2, 0.9, 0.4, 1.1);
        border-left: 2px solid #00ffaa;
        border-right: 2px solid #00aaff;
        cursor: pointer;
        text-decoration: none;
      }

      .premium-badge:hover {
        transform: translateY(-5px) scale(1.03);
        background: rgba(0, 255, 136, 0.15);
        box-shadow: 0 8px 25px rgba(0, 255, 136, 0.3);
        border-left: 2px solid #ffff88;
      }

      .premium-badge i {
        font-size: 1.5rem;
        transition: transform 0.2s;
      }

      .premium-badge span {
        font-weight: 600;
        letter-spacing: 1px;
        font-size: 0.9rem;
        color: #eef5ff;
      }

      /* Location & status group with glowing indicators */
      .info-panel {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        gap: 1.2rem;
        margin: 2rem 0 1rem;
      }

      .info-chip {
        background: rgba(0, 0, 0, 0.55);
        backdrop-filter: blur(10px);
        padding: 0.5rem 1.5rem;
        border-radius: 40px;
        display: flex;
        align-items: center;
        gap: 10px;
        font-weight: 500;
        font-size: 0.9rem;
        border: 1px solid rgba(0, 255, 170, 0.5);
        color: #bffff0;
      }

      .pulse-dot {
        width: 10px;
        height: 10px;
        background: #00ff88;
        border-radius: 50%;
        box-shadow: 0 0 8px #00ff88;
        animation: pulseLive 1.8s infinite;
      }

      @keyframes pulseLive {
        0% {
          opacity: 0.4;
          transform: scale(0.8);
        }
        100% {
          opacity: 1;
          transform: scale(1.2);
        }
      }

      /* animated wave divider */
      .wave-divider {
        margin: 1.8rem 0;
        width: 100%;
        height: 2px;
        background: linear-gradient(
          90deg,
          transparent,
          #00ff88,
          #00aaff,
          transparent
        );
        animation: waveFlow 3s infinite;
      }

      @keyframes waveFlow {
        0% {
          background-position: -200% 0;
          background-size: 200% 2px;
        }
        100% {
          background-position: 200% 0;
          background-size: 200% 2px;
        }
      }

      /* AI/ML 3D animated brain globe (CSS only) */
      .ml-sphere {
        margin: 20px auto 10px;
        width: 100px;
        height: 100px;
        position: relative;
        display: flex;
        justify-content: center;
        align-items: center;
      }

      .neural-orbit {
        position: relative;
        width: 100%;
        height: 100%;
        animation: spinGlobe 12s infinite linear;
      }

      .neural-orbit::before,
      .neural-orbit::after {
        content: "";
        position: absolute;
        border-radius: 50%;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
      }

      .neural-orbit::before {
        width: 80px;
        height: 80px;
        background: radial-gradient(circle, #00ff8822, #00aaff11);
        box-shadow: 0 0 30px #00ff88, inset 0 0 15px #00ff88;
        animation: glowPulse 2s infinite alternate;
      }

      .neural-orbit::after {
        width: 30px;
        height: 30px;
        background: #00ffcc;
        box-shadow: 0 0 20px #0f0;
        filter: blur(2px);
        animation: corePulse 1.5s infinite alternate;
      }

      @keyframes spinGlobe {
        0% {
          transform: rotate(0deg);
        }
        100% {
          transform: rotate(360deg);
        }
      }

      @keyframes glowPulse {
        0% {
          opacity: 0.5;
          box-shadow: 0 0 5px #0f0;
          width: 70px;
          height: 70px;
        }
        100% {
          opacity: 1;
          box-shadow: 0 0 35px #0f0;
          width: 85px;
          height: 85px;
        }
      }

      @keyframes corePulse {
        0% {
          transform: translate(-50%, -50%) scale(0.9);
          background: #00ffaa;
        }
        100% {
          transform: translate(-50%, -50%) scale(1.2);
          background: #aaffff;
        }
      }

      /* floating particles container */
      .particles {
        position: absolute;
        width: 100%;
        height: 100%;
        top: 0;
        left: 0;
        pointer-events: none;
        z-index: 3;
      }

      /* responsive */
      @media (max-width: 680px) {
        .ai-name {
          font-size: 2rem;
        }
        .neural-header {
          padding: 1.8rem;
        }
        .premium-badge {
          padding: 0.4rem 1rem;
        }
        .role-text {
          font-size: 0.85rem;
        }
      }
    </style>
  </head>
  <body>
    <div class="neural-header">
      <!-- Neural network interactive canvas (AI/ML animated bou) -->
      <canvas id="aiCanvas"></canvas>

      <!-- Dynamic floating particles (js) -->
      <div class="particles" id="particleContainer"></div>

      <div class="content">
        <!-- Advanced Typing Glitch with SVG simulation (custom typing using data-text) -->
        <div class="glitch-typing">
          <img
            src="https://readme-typing-svg.herokuapp.com?font=Orbitron&weight=800&size=38&duration=2200&pause=700&color=00FF88&center=true&vCenter=true&multiline=false&width=750&height=80&lines=%E2%96%B3+NEURAL+INTERFACE+ACTIVE+%E2%96%B3;%5BAI+%26+ML+ARCHITECT%5D;%3E+SYSTEM_ONLINE"
            alt="Typing SVG"
            class="typing-svg"
            style="max-width: 100%"
          />
        </div>

        <!-- Main glowing name with 3D effect -->
        <h1 class="ai-name">MUHAMMAD YASIN KHAN</h1>

        <!-- AI Role with animated microchip icon -->
        <div class="role-badge">
          <i class="fas fa-microchip"></i>
          <span class="role-text"
            >AI & MACHINE LEARNING ARCHITECT | DEEP LEARNING ENGINEER</span
          >
          <i class="fas fa-brain"></i>
        </div>

        <!-- Premium Badges with interaction -->
        <div class="badge-row">
          <a
            href="https://www.linkedin.com/in/engr-m-yasin-khan"
            target="_blank"
            class="premium-badge"
          >
            <i class="fab fa-linkedin-in" style="color: #0a66c2"></i>
            <span>LINKEDIN / PROFILE</span>
            <i class="fas fa-external-link-alt" style="font-size: 0.8rem"></i>
          </a>
          <a href="mailto:engr.yasin.ai@gmail.com" class="premium-badge">
            <i class="fas fa-envelope" style="color: #ea4335"></i>
            <span>ENGINEER@AI</span>
            <i class="fas fa-paper-plane"></i>
          </a>
          <a href="#" class="premium-badge">
            <i class="fab fa-github" style="color: #ffffff"></i>
            <span>GITHUB / NEURAL LABS</span>
            <i class="fas fa-code-branch"></i>
          </a>
        </div>

        <!-- Neural animated AI Sphere + Location row -->
        <div class="ml-sphere">
          <div class="neural-orbit"></div>
        </div>

        <!-- Advanced location + status row with active pulse -->
        <div class="info-panel">
          <div class="info-chip">
            <i class="fas fa-map-marker-alt" style="color: #ff6b6b"></i>
            <span>📍 SWAT VALLEY, PAKISTAN</span>
          </div>
          <div class="info-chip">
            <div class="pulse-dot"></div>
            <span>🟢 LIVE STATUS: ACTIVE</span>
          </div>
          <div class="info-chip">
            <i class="fas fa-briefcase" style="color: #ffd700"></i>
            <span>💼 OPEN FOR WORK & COLLABORATION</span>
            <i class="fas fa-chart-line" style="color: #00ffaa"></i>
          </div>
        </div>

        <!-- Animated Gradient Wave Divider -->
        <div class="wave-divider"></div>

        <!-- additional ML/AI text glow tagline -->
        <div
          style="
            margin-top: 1rem;
            font-size: 0.85rem;
            letter-spacing: 1.5px;
            color: #77ffaa;
            font-family: monospace;
          "
        >
          <i class="fas fa-robot"></i> [ DEEP LEARNING | COMPUTER VISION | LLMs
          | TENSOR FLOW | PYTORCH ] <i class="fas fa-chart-network"></i>
        </div>
      </div>
    </div>

    <script>
      // ========== ADVANCED AI/ML ANIMATED "BOU" (Neural Network / Particle System) ==========
      const canvas = document.getElementById("aiCanvas");
      const ctx = canvas.getContext("2d");
      let width, height;
      let nodes = [];
      let edges = [];
      let mouseX = 0,
        mouseY = 0;
      let frame = 0;

      // colors for neural style
      const neonColors = [
        "#00ff88",
        "#33ffaa",
        "#00ccff",
        "#88ffcc",
        "#0affb3",
      ];

      function initCanvas() {
        const container = document.querySelector(".neural-header");
        const rect = container.getBoundingClientRect();
        width = rect.width;
        height = rect.height;
        canvas.width = width;
        canvas.height = height;
        canvas.style.width = `${width}px`;
        canvas.style.height = `${height}px`;
        generateNodes();
      }

      function generateNodes() {
        nodes = [];
        // number of neurons based on area (dynamic)
        let numNodes = Math.min(65, Math.floor((width * height) / 9000) + 32);
        for (let i = 0; i < numNodes; i++) {
          nodes.push({
            x: Math.random() * width,
            y: Math.random() * height,
            vx: (Math.random() - 0.5) * 0.35,
            vy: (Math.random() - 0.5) * 0.35,
            radius: 2 + Math.random() * 3.5,
            color: neonColors[Math.floor(Math.random() * neonColors.length)],
            pulse: Math.random() * Math.PI * 2,
          });
        }
        // create edges based on proximity
        updateEdges();
      }

      function updateEdges() {
        edges = [];
        const maxDist = Math.min(width, height) * 0.19;
        for (let i = 0; i < nodes.length; i++) {
          for (let j = i + 1; j < nodes.length; j++) {
            const dx = nodes[i].x - nodes[j].x;
            const dy = nodes[i].y - nodes[j].y;
            const dist = Math.hypot(dx, dy);
            if (dist < maxDist) {
              edges.push({ from: i, to: j, dist: dist, maxDist: maxDist });
            }
          }
        }
      }

      function animateNeuralNetwork() {
        if (!ctx) return;
        ctx.clearRect(0, 0, width, height);

        // subtle dark gradient overlay for depth
        ctx.fillStyle = "rgba(3, 8, 18, 0.35)";
        ctx.fillRect(0, 0, width, height);

        // update node positions (gentle drift + mouse influence)
        for (let i = 0; i < nodes.length; i++) {
          let n = nodes[i];
          // mouse attraction (AI interactive field)
          const dxMouse = mouseX - n.x;
          const dyMouse = mouseY - n.y;
          const distMouse = Math.hypot(dxMouse, dyMouse);
          if (distMouse < 130 && distMouse > 5) {
            const force = (130 - distMouse) / 300;
            n.vx += dxMouse * force * 0.008;
            n.vy += dyMouse * force * 0.008;
          }
          // boundaries + bounce with damping
          n.vx *= 0.995;
          n.vy *= 0.995;
          n.x += n.vx;
          n.y += n.vy;
          if (n.x < 0) {
            n.x = 0;
            n.vx *= -0.6;
          }
          if (n.x > width) {
            n.x = width;
            n.vx *= -0.6;
          }
          if (n.y < 0) {
            n.y = 0;
            n.vy *= -0.6;
          }
          if (n.y > height) {
            n.y = height;
            n.vy *= -0.6;
          }

          // pulse factor for glow
          n.pulse += 0.02;
        }

        // update edges after movement (recalculate distances but we keep edges alive, dynamic edge recalculation each few frames for efficiency)
        if (frame % 45 === 0) updateEdges();

        // draw glowing edges first
        for (let edge of edges) {
          const fromNode = nodes[edge.from];
          const toNode = nodes[edge.to];
          if (!fromNode || !toNode) continue;
          const alpha = Math.min(0.7, 1 - edge.dist / edge.maxDist) * 0.55;
          ctx.beginPath();
          ctx.moveTo(fromNode.x, fromNode.y);
          ctx.lineTo(toNode.x, toNode.y);
          ctx.strokeStyle = `rgba(0, 255, 150, ${alpha * 0.8 + 0.1})`;
          ctx.lineWidth = 1.2 + (1 - edge.dist / edge.maxDist) * 1.2;
          ctx.shadowBlur = 6;
          ctx.shadowColor = "#00ffaa";
          ctx.stroke();
        }
        ctx.shadowBlur = 0;

        // draw nodes with advanced glow effect
        for (let n of nodes) {
          ctx.beginPath();
          const glowIntensity = Math.sin(n.pulse) * 0.3 + 0.7;
          ctx.arc(n.x, n.y, n.radius + 0.5, 0, Math.PI * 2);
          ctx.fillStyle = n.color;
          ctx.shadowBlur = 12;
          ctx.shadowColor = n.color;
          ctx.fill();
          ctx.beginPath();
          ctx.arc(n.x, n.y, n.radius * 0.65, 0, Math.PI * 2);
          ctx.fillStyle = "#ffffffcc";
          ctx.fill();
        }
        ctx.shadowBlur = 0;
        frame++;
        requestAnimationFrame(animateNeuralNetwork);
      }

      // update canvas on resize
      function resizeCanvas() {
        const container = document.querySelector(".neural-header");
        const rect = container.getBoundingClientRect();
        width = rect.width;
        height = rect.height;
        canvas.width = width;
        canvas.height = height;
        canvas.style.width = `${width}px`;
        canvas.style.height = `${height}px`;
        generateNodes();
      }

      // mouse tracking for AI interactive field
      function handleMouseMove(e) {
        const rect = canvas.getBoundingClientRect();
        const scaleX = canvas.width / rect.width;
        const scaleY = canvas.height / rect.height;
        let clientX, clientY;
        if (e.touches) {
          clientX = e.touches[0].clientX;
          clientY = e.touches[0].clientY;
        } else {
          clientX = e.clientX;
          clientY = e.clientY;
        }
        let canvasX = (clientX - rect.left) * scaleX;
        let canvasY = (clientY - rect.top) * scaleY;
        if (
          canvasX >= 0 &&
          canvasX <= width &&
          canvasY >= 0 &&
          canvasY <= height
        ) {
          mouseX = canvasX;
          mouseY = canvasY;
        } else {
          mouseX = -1000;
          mouseY = -1000;
        }
      }

      // particle system for extra "AI/MAGIC" dust (floating dots)
      class Particle {
        constructor(x, y, size, speedX, speedY, life) {
          this.x = x;
          this.y = y;
          this.size = size;
          this.speedX = speedX;
          this.speedY = speedY;
          this.life = life;
          this.maxLife = life;
          this.color = `hsl(${Math.random() * 80 + 100}, 80%, 60%)`;
        }
        update() {
          this.x += this.speedX;
          this.y += this.speedY;
          this.life -= 1.5;
          return this.life > 0;
        }
        draw(ctxPart) {
          ctxPart.globalAlpha = Math.min(1, (this.life / this.maxLife) * 0.7);
          ctxPart.fillStyle = this.color;
          ctxPart.shadowBlur = 6;
          ctxPart.shadowColor = "#00ffaa";
          ctxPart.beginPath();
          ctxPart.arc(
            this.x,
            this.y,
            this.size * (this.life / this.maxLife),
            0,
            Math.PI * 2
          );
          ctxPart.fill();
        }
      }

      let particles = [];
      function createParticleBurst(x, y) {
        for (let i = 0; i < 3; i++) {
          particles.push(
            new Particle(
              x,
              y,
              1.5 + Math.random() * 2.5,
              (Math.random() - 0.5) * 0.9,
              (Math.random() - 0.5) * 0.9 - 0.8,
              45 + Math.random() * 30
            )
          );
        }
      }

      function animateParticles() {
        const partCanvas = document.createElement("canvas");
        // we use existing canvas context overlay? Actually we draw particles on top of canvas? we can draw them onto same canvas but careful not to conflict.
        // simpler: use same canvas but draw after neural network in same animation loop? We'll embed particle drawing inside main animateNeuralNetwork
        // But easier: we integrate particles into main canvas drawing via global particle array and draw inside animateNeuralNetwork after nodes.
        // That way it's unified.
        // So we add particle drawing in animateNeuralNetwork.
      }

      // override animateNeuralNetwork to also draw particles and generate occasionally
      const originalAnimate = animateNeuralNetwork;
      window.animateNeuralNetwork = function () {
        if (!ctx) return;
        // call update & draw edges and nodes by reusing the main logic but we need to inject particle updates.
        // Let's re-declare the main loop fully integrated with particles:
        // We'll redefine the function to combine neural net and particles.
        // But we already declared animateNeuralNetwork, let's override with full version that includes particles.
      };

      // Final complete animation loop integration
      let particleArray = [];
      function addRandomParticle() {
        if (Math.random() < 0.2 && particleArray.length < 110) {
          let x = Math.random() * width;
          let y = Math.random() * height;
          particleArray.push(
            new Particle(
              x,
              y,
              1.5 + Math.random() * 2,
              (Math.random() - 0.5) * 0.5,
              (Math.random() - 0.5) * 0.5 - 0.2,
              55 + Math.random() * 45
            )
          );
        }
      }

      const finalLoop = () => {
        if (!ctx) return;
        ctx.clearRect(0, 0, width, height);
        ctx.fillStyle = "rgba(3, 8, 18, 0.3)";
        ctx.fillRect(0, 0, width, height);
        // update nodes & edges (same logic as before)
        for (let n of nodes) {
          const dxMouse = mouseX - n.x;
          const dyMouse = mouseY - n.y;
          const distMouse = Math.hypot(dxMouse, dyMouse);
          if (distMouse < 130 && distMouse > 5) {
            const force = (130 - distMouse) / 270;
            n.vx += dxMouse * force * 0.007;
            n.vy += dyMouse * force * 0.007;
          }
          n.vx *= 0.995;
          n.vy *= 0.995;
          n.x += n.vx;
          n.y += n.vy;
          if (n.x < 0) {
            n.x = 0;
            n.vx *= -0.5;
          }
          if (n.x > width) {
            n.x = width;
            n.vx *= -0.5;
          }
          if (n.y < 0) {
            n.y = 0;
            n.vy *= -0.5;
          }
          if (n.y > height) {
            n.y = height;
            n.vy *= -0.5;
          }
          n.pulse += 0.025;
        }
        if (frame % 40 === 0) updateEdges();
        for (let edge of edges) {
          const f = nodes[edge.from],
            t = nodes[edge.to];
          if (f && t) {
            const alpha =
              Math.min(
                0.65,
                1 - Math.hypot(f.x - t.x, f.y - t.y) / edge.maxDist
              ) * 0.55;
            ctx.beginPath();
            ctx.moveTo(f.x, f.y);
            ctx.lineTo(t.x, t.y);
            ctx.strokeStyle = `rgba(80, 255, 150, ${alpha + 0.1})`;
            ctx.lineWidth = 1.2;
            ctx.shadowBlur = 4;
            ctx.stroke();
          }
        }
        for (let n of nodes) {
          ctx.beginPath();
          ctx.arc(n.x, n.y, n.radius + 0.4, 0, Math.PI * 2);
          ctx.fillStyle = n.color;
          ctx.shadowBlur = 10;
          ctx.fill();
          ctx.beginPath();
          ctx.arc(n.x, n.y, n.radius * 0.6, 0, Math.PI * 2);
          ctx.fillStyle = "#eaffff";
          ctx.fill();
        }
        // particles update & draw
        for (let i = particleArray.length - 1; i >= 0; i--) {
          if (!particleArray[i].update()) {
            particleArray.splice(i, 1);
            continue;
          }
          particleArray[i].draw(ctx);
        }
        addRandomParticle();
        if (
          Math.random() < 0.05 &&
          mouseX > 0 &&
          mouseX < width &&
          mouseY > 0 &&
          mouseY < height
        )
          createParticleBurst(mouseX, mouseY);
        function createParticleBurst(xx, yy) {
          for (let q = 0; q < 2; q++)
            particleArray.push(
              new Particle(
                xx,
                yy,
                1.8,
                (Math.random() - 0.5) * 1.2,
                (Math.random() - 0.5) * 1.2 - 0.4,
                40
              )
            );
        }
        ctx.shadowBlur = 0;
        frame++;
        requestAnimationFrame(finalLoop);
      };

      // attach events
      window.addEventListener("resize", () => {
        resizeCanvas();
        setTimeout(() => {
          particleArray = [];
        }, 100);
      });
      canvas.addEventListener("mousemove", handleMouseMove);
      canvas.addEventListener("touchmove", (e) => {
        e.preventDefault();
        handleMouseMove(e);
      });

      initCanvas();
      // start final combined loop (neural + particles)
      requestAnimationFrame(() => {
        finalLoop();
      });
    </script>
  </body>
</html>
