<template>
  <div class="p-5">
    <MainHeader>Issues</MainHeader>

    <SiteButton class="flex items-center" to="/project/issues/new">
      <svg class="w-5 h-5 mr-1" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10" /><line x1="12" y1="8" x2="12" y2="16" /><line x1="8" y1="12" x2="16" y2="12" /></svg>
      Create new issue
    </SiteButton>
  </div>
</template>

<script>
import MainHeader from '@/components/MainHeader';
import SiteButton from '@/components/SiteButton';

export default {
  components: {
    MainHeader,
    SiteButton
  }
}
</script>
