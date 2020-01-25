<template>
   <div class="container">
        <div class="row justify-content-center">
            <div class="col-md-9">
                <div class="card card-default">
                    <div class="card-header">Upload Your Images</div>

                    <div class="card-body">
                        <image-uploader></image-uploader>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
import ImageUploader from './components/ImageUploader.vue'

export default {
  name: 'app',
 
        components: {
            ImageUploader
        }
}
</script>

<style>

</style>
