<template>
    <aside class="aside-bar px-5 py-8 bg-sidebar h-full relative">
        <button class="absolute top-2 right-3 transition-colors hover:text-primary">
            <Icon name="line-md:logout" size="30"  />
        </button>

        <NuxtLink class="mb-10 block" to="/">
            <NuxtImg src="/logo.png" alt="" width="120px" class="mx-auto" />
        </NuxtLink>

        <LayoutsMenu />
        <LayoutsLoader />

    </aside>
</template>
