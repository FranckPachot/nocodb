<template>
  <div class="flex flex-col">
    <NcPageHeader>
      <template #icon>
        <GeneralIcon icon="appStore" class="flex-none text-gray-700 text-[20px] h-5 w-5" />
      </template>
      <template #title>
        <span data-rec="true">
          {{ $t('title.appStore') }}
        </span>
      </template>
    </NcPageHeader>
    <div class="p-6 h-[calc(100vh_-_100px)] border-t-1 border-gray-200 flex flex-col gap-6 overflow-auto nc-scrollbar-thin">
      <div>
        <LazyDashboardSettingsAppStore />
      </div>
    </div>
  </div>
</template>
