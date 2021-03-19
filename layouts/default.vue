<template>
  <div class="flex">
    <div class="bg-blue-700 text-white h-screen p-5 flex flex-col items-center justify-between">
      <div class="flex flex-col items-center space-y-6">
        <h1>
          <NuxtLink to="/project">
            <svg class="w-8 h-8" viewBox="0 0 500 500">
              <defs>
                <pattern id="stripes" patternUnits="userSpaceOnUse" width="80" height="80">
                  <path stroke-width="30" stroke="currentColor" d="M 0 80 l 80 -80 M -20 20 l 40 -40 M 60 100 l 40 -40" />
                </pattern>
              </defs>
              <path stroke-width="20" stroke="currentColor" fill="url(#stripes)" d="M  10  10 L 490  10 L 490 170 L 320 170 L 320 490 L 160 490 L 160 170 L  10 170 Z" />
            </svg>
          </NuxtLink>
        </h1>

        <NuxtLink to="/project/issues/new" title="Create new issue">
          <svg class="w-8 h-8" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10" /><line x1="12" y1="8" x2="12" y2="16" /><line x1="8" y1="12" x2="16" y2="12" /></svg>
        </NuxtLink>
      </div>

      <div class="flex flex-col items-center space-y-6">
        <NuxtLink to="/settings" title="Settings">
          <svg class="w-6 h-6" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="3"></circle><path d="M19.4 15a1.65 1.65 0 0 0 .33 1.82l.06.06a2 2 0 0 1 0 2.83 2 2 0 0 1-2.83 0l-.06-.06a1.65 1.65 0 0 0-1.82-.33 1.65 1.65 0 0 0-1 1.51V21a2 2 0 0 1-2 2 2 2 0 0 1-2-2v-.09A1.65 1.65 0 0 0 9 19.4a1.65 1.65 0 0 0-1.82.33l-.06.06a2 2 0 0 1-2.83 0 2 2 0 0 1 0-2.83l.06-.06a1.65 1.65 0 0 0 .33-1.82 1.65 1.65 0 0 0-1.51-1H3a2 2 0 0 1-2-2 2 2 0 0 1 2-2h.09A1.65 1.65 0 0 0 4.6 9a1.65 1.65 0 0 0-.33-1.82l-.06-.06a2 2 0 0 1 0-2.83 2 2 0 0 1 2.83 0l.06.06a1.65 1.65 0 0 0 1.82.33H9a1.65 1.65 0 0 0 1-1.51V3a2 2 0 0 1 2-2 2 2 0 0 1 2 2v.09a1.65 1.65 0 0 0 1 1.51 1.65 1.65 0 0 0 1.82-.33l.06-.06a2 2 0 0 1 2.83 0 2 2 0 0 1 0 2.83l-.06.06a1.65 1.65 0 0 0-.33 1.82V9a1.65 1.65 0 0 0 1.51 1H21a2 2 0 0 1 2 2 2 2 0 0 1-2 2h-.09a1.65 1.65 0 0 0-1.51 1z"></path></svg>
        </NuxtLink>
        <NuxtLink to="/profile" title="Profile">
          <img class="w-8 h-8 rounded-full border-white border-2" alt="travishorn profile photo" src="/profile-photo/travishorn.jpg" />
        </NuxtLink>
      </div>
    </div>
    <Nuxt />
  </div>
</template>
