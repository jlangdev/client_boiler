<template>
  <div>
    <ModuleA/>
    <ModuleB/>
    <ModuleC/>
    <ModuleD/>
  </div>
</template>

<script>
// @ is an alias to /src
import ModuleA from '@/components/ModuleA.vue'
import ModuleB from '@/components/ModuleB.vue'
import ModuleC from '@/components/ModuleC.vue'
import ModuleD from '@/components/ModuleD.vue'


export default {
  name: 'Home',
  components: {
    ModuleA,
    ModuleB,
    ModuleC,
    ModuleD
  }
}
</script>
