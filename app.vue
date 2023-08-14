<template>
  <div>
    <ElMenu
        mode="horizontal"
    >
        <ElSubMenu index="1">
            <template #title>
                title 1
            </template>
            <ElSubMenu index="1-1">
                <template #title>
                    title 1-1
                </template>
                <ElMenuItem index="1-1-1"> Item 1-1-1 </ElMenuItem>
            </ElSubMenu>
        </ElSubMenu>
    </ElMenu>
    <ElMenu
        mode="vertical"
    >
        <ElSubMenu index="2">
            <template #title>
                title 2
            </template>
            <ElSubMenu index="2-1">
                <template #title>
                    title 2-1
                </template>
                <ElMenuItem index="2-1-1"> Item 2-1-1 </ElMenuItem>
            </ElSubMenu>
        </ElSubMenu>
    </ElMenu>
  </div>
</template>
