<template>
    <div>
        <video autoplay loop id="ostiaPilotesVideo">
            <source src="@/assets/videos/5O8d_S9yqgtXWL03.mp4" type="video/mp4">
        </video>
    </div>
</template>

<script>
export default {
    props: ['videoSrc'],
}
</script>
<style>

#ostiaPilotesVideo {
  position: fixed;
  right: 0;
  bottom: 0;
  min-width: 100%;
  min-height: 100%;
}

</style>
