<script setup>
import { Timeline, TimelineItem, TimelinePoint, TimelineTime, TimelineContent, TimelineTitle } from 'flowbite-vue'
</script>
<template>
  <p class="m-5 mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Pengalaman</p>
  <div class="flex flex-row">
  <div class="basis-1/2">
    <p class="m-5">
    <Timeline>
    <timeline-item>
      <timeline-point>
      </timeline-point>
      <timeline-content>
        <timeline-time>
          Kelas 4-5 SD
        </timeline-time>
        <timeline-title>
          Pernah Mengikuti Eskul Karawitan
        </timeline-title>
      </timeline-content>
    </timeline-item>

    <timeline-item>
      <timeline-point>
      </timeline-point>
      <timeline-content>
        <timeline-time>
          Kelas 7-8 SMP
        </timeline-time>
        <timeline-title>
          Pernah Mengikuti Les Badminton
        </timeline-title>
      </timeline-content>
    </timeline-item>

    <timeline-item>
      <timeline-point>
      </timeline-point>
      <timeline-content>
        <timeline-time>
          Sekarang 
        </timeline-time>
        <timeline-title>
          Pernah Membuat Website Pembelajaran
        </timeline-title>
      </timeline-content>
    </timeline-item>

  </Timeline>
  </p>

  </div>
  <div class="basis-1/2">
      <img class="h-auto max-w-full rounded-lg " src="https://cdn.dribbble.com/users/472667/screenshots/15522562/media/92eb48276be12667fcbec8c5d6105a87.gif" alt="image description">
  </div>
</div>
  
</template>

