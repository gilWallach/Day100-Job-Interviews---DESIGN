<template>
<section class="app-features">
        <div class="feature flex flex-column align-center">
            <icon-access-anywhere />
            <h3>Access your files, anywhere</h3>
            <p>The ability to use a smartphone, tablet, or computer to access your account means your files follow you everywhere.</p>
        </div>
        <div class="feature flex flex-column align-center">
            <icon-security />
            <h3>Security you can trust</h3>
            <p>2-factor authentication and user-controlled encryption are just a couple of the security features we allow to help secure your files.</p>
        </div>
        <div class="feature flex flex-column align-center">
            <icon-collaboration />
            <h3>Real-time collaboration</h3>
            <p>Securely share files and folders with friends, family and colleagues for live collaboration. No email attachments required.</p>
        </div>
        <div class="feature flex flex-column align-center">
            <icon-any-file />
            <h3>Store any type of file</h3>
            <p>Whether you're sharing holidays photos or work documents, Fylo has you covered allowing for all file types to be securely stored and shared.</p>
        </div>
</section>
</template>

<script>
import iconAccessAnywhere from '../assets/svg/icon-access-anywhere.vue'
import iconCollaboration from '../assets/svg/icon-collaboration.vue'
import iconSecurity from '../assets/svg/icon-security.vue'
import iconAnyFile from '../assets/svg/icon-any-file.vue'
 export default {
name: 'app-features',
  props: {},
  data() {
 return{}},
  created(){},
 methods: {},
 computed: {},
 components: {
    iconAccessAnywhere,
    iconCollaboration,
    iconSecurity,
    iconAnyFile
 }
  }
 </script>