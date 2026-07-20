<script>
  import avatar from "$lib/assets/avatar.png";
  import novaai from "$lib/assets/NovaAI.png";
</script>

<div class="pt-4 font-mono">
  <h1 class="pt-4 font-mono font-semibold text-2xl text-center">Projects</h1>
  
  <div class="flex flex-col items-center">
    <!-- Nova AI -->
    <div class="flex items-center group p-4 m-4 gap-4 rounded-md border border-border hover:border-white transition-colors duration-300 w-96">
      <img
        src={novaai} 
        alt="avatar"
        class="rounded-full group-hover:border group-hover:border-white bor transition-colors duraiton-300 h-12 w-12 ml-2"
      />
      <div class="flex flex-col">
        <a href="" class="font-bold hover:underline">
          Nova AI (Coming Soon)
        </a>
        <p class="text-slate-300">Nova AI—your personal AI girlfriend or boyfriend. Talk about your day, express your emotions, and be yourself in a safe, private, and judgment-free space.</p>
      </div>
    </div>
  </div> 
</div>
