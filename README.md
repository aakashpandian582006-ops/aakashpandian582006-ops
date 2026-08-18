<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Aakash Pandian | Cloud Architect & Systems Designer</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css"/>
  <style>
    body { background-color: #0b0f19; color: #f3f4f6; font-family: 'Inter', sans-serif; }
    .glass-card { background: rgba(17, 24, 39, 0.7); backdrop-filter: blur(12px); border: 1px solid rgba(255, 255, 255, 0.08); }
    .glow-purple { box-shadow: 0 0 50px -10px rgba(147, 51, 234, 0.3); }
    .gradient-text { background: linear-gradient(135deg, #a855f7 0%, #3b82f6 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }
  </style>
</head>
<body class="antialiased">

  <!-- NAVBAR -->
  <nav class="flex items-center justify-between px-8 py-6 max-w-7xl mx-auto">
    <div class="text-2xl font-bold tracking-wide flex items-center gap-2">
      <span class="text-purple-500">&lt;/&gt;</span> Aakash.ops
    </div>
    <div class="hidden md:flex gap-8 text-gray-400 font-medium text-sm">
      <a href="#about" class="hover:text-white transition">About</a>
      <a href="#skills" class="hover:text-white transition">Skills</a>
      <a href="#projects" class="hover:text-white transition">Projects</a>
      <a href="#contact" class="hover:text-white transition">Contact</a>
    </div>
    <a href="mailto:aakashpandian.5.8.2006@gmail.com" class="bg-purple-600 hover:bg-purple-700 text-white px-5 py-2.5 rounded-lg text-sm font-semibold transition shadow-lg shadow-purple-600/30">Hire Me <i class="fa-solid fa-arrow-up-right-from-square ml-1 text-xs"></i></a>
  </nav>

  <!-- HERO SECTION -->
  <section class="max-w-7xl mx-auto px-8 py-16 grid grid-cols-1 md:grid-cols-2 gap-12 items-center">
    <div>
      <span class="bg-purple-900/50 text-purple-400 text-xs font-semibold px-3 py-1 rounded-full border border-purple-500/30 uppercase tracking-wider">Cloud Systems Architect</span>
      <h1 class="text-5xl md:text-6xl font-extrabold mt-4 mb-6 leading-tight">
        Hi, I'm <span class="gradient-text">Aakash</span><br/>
        I design cloud infrastructure & UI/UX systems.
      </h1>
      <p class="text-gray-400 text-lg mb-8 leading-relaxed">
        Specializing in high-availability AWS architecture, automated Infrastructure as Code (Terraform), and clean visual topologies for production environments.
      </p>
      <div class="flex gap-4">
        <a href="#projects" class="bg-purple-600 hover:bg-purple-700 px-6 py-3 rounded-lg font-semibold text-sm transition">View Work <i class="fa-solid fa-arrow-right ml-2"></i></a>
        <a href="http://mybucky123-nx2026.s3-website.eu-north-1.amazonaws.com/" target="_blank" class="glass-card hover:bg-gray-800 px-6 py-3 rounded-lg font-semibold text-sm transition border border-gray-700">Live S3 Demo <i class="fa-solid fa-download ml-2"></i></a>
      </div>
    </div>
    
    <!-- CODE WINDOW CARD -->
    <div class="relative flex justify-center">
      <div class="absolute w-72 h-72 bg-purple-600/20 rounded-full blur-3xl -z-10"></div>
      <div class="glass-card p-6 rounded-2xl w-full max-w-md border border-gray-800 shadow-2xl">
        <div class="flex gap-2 mb-4">
          <span class="w-3 h-3 bg-red-500 rounded-full"></span>
          <span class="w-3 h-3 bg-yellow-500 rounded-full"></span>
          <span class="w-3 h-3 bg-green-500 rounded-full"></span>
        </div>
        <pre class="text-xs text-purple-300 font-mono leading-relaxed"><code><span class="text-purple-400">const</span> architect = {
  name: <span class="text-green-400">"Aakash Pandian"</span>,
  domain: <span class="text-green-400">"Cloud & Systems UI/UX"</span>,
  stack: [<span class="text-green-400">"AWS"</span>, <span class="text-green-400">"Terraform"</span>, <span class="text-green-400">"Docker"</span>],
  focus: <span class="text-green-400">"Building enterprise infrastructure"</span>
};</code></pre>
      </div>
    </div>
  </section>

  <!-- SKILLS SECTION -->
  <section id="skills" class="max-w-7xl mx-auto px-8 py-16">
    <div class="text-center mb-12">
      <span class="text-purple-400 font-semibold text-sm uppercase tracking-wider">MY SKILLS</span>
      <h2 class="text-3xl font-bold mt-2">Technologies I Master</h2>
    </div>

    <div class="grid grid-cols-1 md:grid-cols-2 gap-8 max-w-4xl mx-auto">
      <div>
        <div class="flex justify-between text-sm font-semibold mb-2"><span>AWS Cloud Infrastructure</span><span class="text-purple-400">95%</span></div>
        <div class="w-full bg-gray-800 h-2 rounded-full"><div class="bg-purple-500 h-2 rounded-full w-[95%]"></div></div>
      </div>
      <div>
        <div class="flex justify-between text-sm font-semibold mb-2"><span>Terraform & IaC</span><span class="text-purple-400">90%</span></div>
        <div class="w-full bg-gray-800 h-2 rounded-full"><div class="bg-blue-500 h-2 rounded-full w-[90%]"></div></div>
      </div>
      <div>
        <div class="flex justify-between text-sm font-semibold mb-2"><span>Docker & Kubernetes</span><span class="text-purple-400">85%</span></div>
        <div class="w-full bg-gray-800 h-2 rounded-full"><div class="bg-purple-500 h-2 rounded-full w-[85%]"></div></div>
      </div>
      <div>
        <div class="flex justify-between text-sm font-semibold mb-2"><span>System Topology & Figma UI</span><span class="text-purple-400">90%</span></div>
        <div class="w-full bg-gray-800 h-2 rounded-full"><div class="bg-blue-500 h-2 rounded-full w-[90%]"></div></div>
      </div>
    </div>
  </section>

  <!-- PROJECTS SECTION -->
  <section id="projects" class="max-w-7xl mx-auto px-8 py-16">
    <div class="text-center mb-12">
      <span class="text-purple-400 font-semibold text-sm uppercase tracking-wider">FEATURED DEPLOYMENTS</span>
      <h2 class="text-3xl font-bold mt-2">Some of My Recent Work</h2>
    </div>

    <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
      <div class="glass-card p-6 rounded-2xl hover:border-purple-500/50 transition">
        <h3 class="text-xl font-bold mb-2">Serverless API Engine</h3>
        <p class="text-gray-400 text-sm mb-4">AWS API Gateway + Lambda + DynamoDB framework fully automated with Terraform.</p>
        <span class="text-xs bg-purple-900/40 text-purple-300 px-2.5 py-1 rounded">AWS / IaC</span>
      </div>
      <div class="glass-card p-6 rounded-2xl hover:border-purple-500/50 transition">
        <h3 class="text-xl font-bold mb-2">Sovereign Multi-Region Infrastructure</h3>
        <p class="text-gray-400 text-sm mb-4">High-availability VPC network topologies featuring cross-region failover automation.</p>
        <span class="text-xs bg-blue-900/40 text-blue-300 px-2.5 py-1 rounded">Terraform</span>
      </div>
      <div class="glass-card p-6 rounded-2xl hover:border-purple-500/50 transition">
        <h3 class="text-xl font-bold mb-2">FinOps Cost Optimization Hub</h3>
        <p class="text-gray-400 text-sm mb-4">Real-time resource drift monitoring system reducing operational cloud idle spend.</p>
        <span class="text-xs bg-purple-900/40 text-purple-300 px-2.5 py-1 rounded">Python / AWS</span>
      </div>
    </div>
  </section>

  <!-- FOOTER -->
  <footer class="border-t border-gray-800 py-8 text-center text-gray-500 text-sm">
    © 2026 Aakash Pandian. All rights reserved.
  </footer>

</body>
</html>
