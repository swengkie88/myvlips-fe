<template>
  <header class="py-6">
    <div class="main-container">
      <div class="flex items-center justify-between">
        <AppBrand />
        <div class="flex flex-row items-center">
          <NavBar class="mx-3" />
          <SecondaryButton class="mx-2">
            Sign In
          </SecondaryButton>
          <PrimaryButton>Sign Up</PrimaryButton>
        </div>
      </div>
    </div>
  </header>
</template>
<script>
export default {
  name: 'AppHeader'
}
</script>
