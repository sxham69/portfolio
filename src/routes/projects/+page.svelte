<script>
  import avatar from "$lib/assets/avatar.png";
</script>

<div class="pt-4 font-mono">
  <h1 class="pt-4 font-mono font-semibold text-2xl text-center">Projects</h1>
  <div class="flex flex-col items-center">
    
    <!-- First Project Card -->
    <div class="flex items-center group p-4 m-4 gap-4 rounded-md border border-border hover:border-white transition-colors duration-300 w-96">
      <img
        src={avatar} 
        alt="avatar"
        class="rounded-full group-hover:border group-hover:border-white bor transition-colors duraiton-300 h-12 w-12 ml-2"
      />
      <div class="flex flex-col">
        <a href="https://apollo-bot.xyz" class="font-bold hover:underline">Apollo Bot (sold)</a>
        <p class="text-slate-300">A utility Discord bot</p>
      </div>
    </div>

    <!-- Second Project Card (This was left open) -->
    <div class="flex items-center group p-4 m-4 gap-4 rounded-md border border-border hover:border-white transition-colors duration-300 w-96">
      <!-- Add your second project info here later -->
      <p class="text-slate-400">Project 2 Coming Soon</p>
    </div> <!-- Added missing tag -->

  </div> <!-- Added missing tag for flex container -->
</div> <!-- Added missing tag for outer layout wrapper -->
