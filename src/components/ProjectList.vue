<template>
    <div>
        <ul>
        <ProjectItem />
        </ul>
    </div>
</template>

<script setup lang="ts">
import ProjectData from '@/data/ProjectData';
import ProjectItem from './ProjectItem.vue';
import {ref} from 'vue';

const projectName = ref('')
</script>

<style>

</style>