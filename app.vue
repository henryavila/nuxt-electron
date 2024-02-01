<template>
  <div>
    <NuxtWelcome/>
  </div>
</template>

<script setup>
import {onMounted} from 'vue'
import {ipcRenderer} from 'electron'
import fs from 'node:fs'

onMounted(async () => {
  console.log('ipcRenderer:', ipcRenderer)
  console.log('fs:', fs)
  console.log('process', process)
  console.log(await ipcRenderer.invoke('ping'))
})
</script>
